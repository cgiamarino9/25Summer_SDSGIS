---
marp: true
theme: uncover
headingDivider: 3
footer: UP221 | Intro to GIS and Spatial Data Science ![width:30px](../images/globe.png)
paginate: true

---

<style>
kesmall {font-size:0.6em}
medium {font-size:0.9em}
large {font-size:2em}
xlarge {font-size:4em}
gray {padding:20px;background-color:whitesmoke;font-weight:800}
plum {padding:20px;background-color:plum;line-height:3}
xl { font-size:2.5em;font-weight:100;line-height:1}
h1,h2,h3,h4,h5{font-family:serif}
section {font-size:2em;font-weight:300;}
</style>

# Week 2

<xl>

Spatial Data Exploration

</xl>

[Recurring Zoom link for Winter 2025](https://ucla.zoom.us/j/92932552160?pwd=1SjIMPWzWJv8mmyb7pbQX1IOickbAp.1)

January 13, 2025

##
<xl>

*Note that this course will be recorded🎥

</xl>

##

<xl>
2025 LA Wildfires: Recovery Resources
</xl>

##

<xl> Volunteer, recovery, and relief resources
<xl>

* Sign up for [BruinALERT](https://oem.ucla.edu/bruinalert) from Office of Emergency Management for UCLA Emergency and Evacuation updates.  
* Mutual Aid LA [Google Doc resources](https://docs.google.com/spreadsheets/u/1/d/1KMk34XY5dsvVJjAoD2mQUVHYU_Ib6COz6jcGH5uJWDY/htmlview?usp=sharing&fbclid=PAZXh0bgNhZW0CMTEAAaYPJ-9_5yMHnw8jV-zoxTpablIDDM80At2DrBzEjHBljUZsh00Zg9fq81g_aem_Lb1Ux2Ml4lg8tavGSwEp9w)

* LAist: [Want to help fire victims? Here's what experts say does the most good and places seeking volunteers](https://laist.com/news/climate-environment/how-to-help-la-fire-victims)

* LAist: [A quick roundup of SoCal fire coverage and safety resources](https://laist.com/news/climate-environment/southern-california-fires-tips-resources)

* LAist: [Help for fire victims](https://laist.com/brief/news/climate-environment/resources-for-socal-fire-victims-evacuees-and-first-responders)



##

<xl> GIS resources
<xl>

* Watch Duty Live [Wildfire Maps and Evacuation Notifications](https://app.watchduty.org/)

* [Air Quality map](https://gispub.epa.gov/airnow/)


## Group formation for midterm and final projects

* Open and review the [midterm and final project guidelines](https://github.com/cgiamarino9/25W-UP221/tree/main/Midterm%20and%20Finals#midterms-20-of-your-final-grade). 

* Join breakout room with concentration/specialization you are interested in.

* Introduce yourself and your proposed project in 1-2 sentences. 

* Form groups of 2 - 4 students

* Fill out Google Form with group name, title, description, names and emails by next Sunday, January 19th at 11:59 pm.

* The form is not graded, but it will help you with your midterm proposal due after Week 3. You are welcome to submit the [group project proposal assignment](https://github.com/cgiamarino9/25W-UP221/discussions/5) when your group is ready. It is due January 26th at 11:59 pm. 


## Hands on Lab
* First, grab the course material, and "pull" it into your JupyterHub:

* [UP221 Git Puller](https://jupyter.idre.ucla.edu/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Fcgiamarino9%2F25W-UP221&urlpath=lab%2Ftree%2F25W-UP221%2F&branch=main) 
(This link will automatically launch JupyterHub and clone the course material into your directory)

<small>Note that you have to do this at the start of every lecture to get the latest material.
</small>


# Assignments (due 11:59 Sunday, January 19th the day before class)


## Individual assignment: Data Exploration

### Create a token

In order to pull and push content to GitHub, you must first create a token, which will serve as your password. Refer to this tutorial to create your token:

* [How to create a token](https://github.com/cgiamarino9/25W-UP221/blob/main/Git%20related/Create%20a%20token.md)

### Clone your repo

This is your first code assignment submission. Before you begin, create a clone of your repo in JupyterHub.

* [How to clone your repo into JupyterHub](https://github.com/cgiamarino9/25W-UP221/blob/main/Git%20related/Clone%20repo%20to%20hub.md)

### Submission guidelines:

- Find and download a dataset of your choice. This can be a shapefile, csv file, or json file. For many of you, you may have already done this as part of your week 1 assignments.
- Launch JupyterHub, go to your `up221` repo folder, and create a `week02` folder.
- Load the dataset to the `up221/week02` folder.

### 
Create a new python notebook 
**Do not** work on a copy of the lab notebook

<kbd><img src="images/notebook.png" width=75%></kbd>

###

Right click on the `Untitled.ipynb` tab and rename the notebook to `week2assignment.ipynb` or `assignment2.ipynb`. Just be consistent throughout the quarter. 

<kbd><img src="images/rename.png" height=75% ></kbd>

###

Add an introductory markdown cell with a title (header) and paragraph that describes what you are doing.

###

Import the data, and conduct data exploration, making sure to document your steps and your preliminary findings. At minimum, run the following commands:

* `.shape`
* `.info`
* `.head()`
* `.plot()`
* `.value_counts()`
* run a query on the data that filters it in some way

###

For each code cell, add a markdown cell that explains what you are doing.

Add markdown cells that describe the output of each operation.

Save your notebook.

### Commit your changes to your GitHub class repo.

Commit your changes to your GitHub repo by following these instructions:

* [How to commit and push to your repo](https://github.com/cgiamarino9/25W-UP221/blob/main/Git%20related/Commit%20and%20push.md)

### Submit your assignment 

The last step is to submit your assignment to the class repo discussion section [here](https://github.com/cgiamarino9/25W-UP221/discussions/4).
