# Code Institute January 2022 Hackathon with SODA Social: Mindfulness and Wellbeing

# Project: Mindful Timer

![](static/images/jan-2022-hackathon-image.png)

# Team: The Mind O'Holics

# Table of Contents

<details>
<summary>
Table of Contents
</summary>

* [Introduction](#introduction)
* [User Experience](#user-experience)
    * [User Stories](#user-stories)
        * [Site Owner Goals](#site-owner-goals)
        * [All Visitor Goals](#all-visitor-goals)
        * [First Time Visitor Goals](#first-time-visitor-goals)
        * [Returning Visitor Goals](#returning-visitor-goals)
* [Design](#design)
    * [Surface](#surface)
        * [Colour Scheme](#colour-scheme)
* [Wireframes](#wireframes)
* [Technologies](#technologies)
* [Testing](#testing)
    * [Manual testing](#manual-testing)
    * [Testing Site Owner Goals](#testing-site-owner-goals)
    * [Testing All Visitor Goals](#testing-all-visitor-goals)
    * [Testing First Timer Visitor Goals](#testing-first-time-visitor-goals)
    * [Testing Returning Visitor Goals](#testing-returning-visitor-goals)
    * [Validation Testing](#validation-testing)
    * [Bugs](#bugs)
* [Features](#features)
* [Future Plans](#future-plans)
* [Deployment](#deployment)
    * [Local Deployment](#local-deployment)
        * [Clone the Github Repository](#clone-the-github-repository)
        * [Install Project Dependencies](#install-project-dependencies)
        * [Create a database on MongoDB](#create-a-database-on-mongodb)
        * [Local deployment](#local-deployment)
        * [Deploy to Heroku](#deploy-to-heroku)
* [Credits]()
    * [Images](#images)
    * [Resources](#resources)
    * [Acknowledgements](#acknowledgements)
</details>

## Introduction

This website is a project for Code Institute's January 2022 Hackathon, hosted in collaboration with digital recruitment firm SODA and their networking event SODA Social. The theme of the Hackathon was mindfulness and wellbeing in the workplace. 

The website was created by Naoise Gaffney, Marina Pavlovic, Goran Kuzma, Eva Kuk and Adam Boley, with the project facilitated by Aisha Bushell. The team collectively decided on the team name "The Mind O'Holics". 

The aim of the project is to help digital workers - those working in offices and those working from home - maintain their wellbeing and mindfulness whilst working. When working in an office, workers are often sitting down for long periods, and may not have particularly ergonomic workstations. Those working from home face these issues as well, and more besides - when working from home, it is all too easy for work time to spill over into personal time, with workers constantly in "work-mode", and unable to switch off from work. 

Thus, the website's main feature is an adjustable timer with options of for 2 minutes, 5 minutes, 10 minutes and 20 minutes that can be activated by a user. The timer allows users to take some time away from work to focus on their own wellbeing by drinking some water, doing some breathing exercises, or taking a short walk. The idea is to break up the user's day and try to prevent burnout by giving their brain a break. The timer has a selectable background and an audio file of softy music that plays as the timer counts down. 

The website also includes a resources page that functions as a signpost to other resources on mindfulness and wellbeing. 

## Deployed Project

The project is deployed at [Mindful Timer](https://mindtimer.herokuapp.com/)
<br>
The mockup is below:<br>
![](/static/images/mindtimer.png)

# User Experience

## User Stories

### Site Owner goals
- As site owners, we want to promote mindfulness and wellbeing
- As site owners, we want our site to be easy to use and navigate

### All Visitor Goals
- Visitors should be able to easily navigate the site's pages
- Visitors should be able to easily operate the timer and select from the pre-set timer options

### First Time Visitor Goals
- Visitors should be able to easily determine that the site's purpose is to provide tools to help them focus on their mindfulness and wellbeing at work
- Visitors should be able to easily register an account and log in to that account

### Returning Visitor Goals
- Returning visitors should be able to log in to their account
- Returning visitors should be able to reset their account password if they forget it
- Returning visitors should be able to delete their account if they desire
- Returning visitors should be able to update their profile

# Design
## Surface

### Colour Scheme

The website's chosen colour palette consists of blue, turquoise and green. These were chosen as they are pleasant to look at and may be associated with **peacefulness**, **stress relief**, **balance** and **emotional stability**.

Referring to the colour psychology websites [Very Well Mind](https://www.verywellmind.com/color-psychology-green-2795817) and [Graf1x](https://graf1x.com/color-psychology-emotion-meaning-poster/):

**Blue** is associated with **calmness**, **serenity** and **peace**. It is calm, stress-relieving colour. Blue is often used to decorate offices because research has shown that people are more productive in blue rooms. 

**Green** is associated with **growth** and **health**. It is a **refreshing** and **peaceful** colour. Green is typically the colour of nature. It has a calming effect and is often considered a refreshing, relaxing colour. Green has been found to positively influence not only our emotions but our memories as well. Therefore, green has been employed to help users remember information.

**Turquoise** is a bright blue-green colour. Hence, it takes on the associations of both blue and green - the **calmness** of blue and the **growth** of green. Turquoise is also a bright, energetic colour much like **yellow**. Turquoise is associated with **freshness**,**mental clarity**, **femininity**, **calmness**, **energy**, **serenity**, **creativity**, **balance** and **friendship**.

Our colour scheme, with hex codes:

![proposed-colour-scheme-3](/static/images/proposed-colour-scheme-3.png)


# Wireframes

The Balsamiq Wireframes app was used to create the initial wireframes and update them through the creation of the project. Wireframes were created for each page, with full-size versions for desktops and reduced-size versions for tablets and smartphones. The project evolved in scope over time, and so these wireframes show the initial concept, not the final product.<br> 
Home page:
![home-page-pc](/static/wireframes/home-page-pc.png)

[Smartphone and tablet version](/static/wireframes/home-page-tablet-and-phone.png)

Timer page:
![timers-pc](/static/wireframes/timers-pc.png)

[Smartphone and tablet version](/static/wireframes/timers-tablet-and-phone.png)

Register page:
![register-pc](/static/wireframes/register-pc.png)

[Smartphone and tablet version](/static/wireframes/register-tablet-and-phone.png)

Login page:
![login-pc](/static/wireframes/login-pc.png)

[Smartphone and tablet version](/static/wireframes/login-tablet-and-phone.png)

Resources page:
![resources-pc](/static/wireframes/resources-pc.png)

[Smartphone and tablet version](/static/wireframes/resources-tablet-and-phone.png)

# Technologies

[Github](https://github.com/): Adam Boley's Github was used to host the main project files and folders. Other team members then forked to their repositories. 

[Gitpod](https://gitpod.com/): Most team members used the Gitpod IDE to create and edit the project files. Other team members preferred Visual Studio Code.

[Flask](https://palletsprojects.com/p/flask/): Flask was used to create a framework for the project.

[Flask User](https://flask-user.readthedocs.io/en/latest/): Flask User was used to create the registration and login functionality.

[Bootstrap](https://getbootstrap.com/docs/5.1/getting-started/introduction/): Bootstrap was used to provide a framework for the project

[Heroku](https://www.heroku.com/): Heroku was used to deploy the application

[MongoDB](https://www.mongodb.com/): MongoDB was used to provide the database instance for the project, and to store user profiles

[Slack](https://slack.com/intl/en-gb/): Slack was used to communicate and coordinate the actions of team members, share screenshots, and join video calls to discuss the project

[Google Docs](https://www.google.com/docs/about/): Google Docs was used to create and edit a shared document to note down ideas. 


# Testing

## Testing Site Owner Goals
- The site itself serves to promote mindfulness and wellbeing
- The resources page allows users to access other mindfulness and well-being resources
- The site's navigation is built on modern User Design principles that allow for easy navigation

## Testing All Visitor Goals
- The navigation bar in the header allows for easy and intuitive navigation
- The timer's operation is simple and intuitive

## Testing First Time Visitor Goals
- The purpose of the site is easily discernable
- Account creation is simple and intuitive

## Testing Returning Visitor Goals
- Account login is simple and intuitive
- Password reset is easily accomplished
- Account deletion is easily accomplished
- Users can easily update their profile

## Validation Testing

### JavaScript
- The [JShint](https://jshint.com/) JavaScript Validator was used to validate the JavaScript files of the project
- A number of warnings were detected for each file, but these were for code that was added in the ES6 version of JavaScript 

### HTML
- The [W3C HTML validator](https://validator.w3.org/) was used to check the HTML by URL input from the Heroku-deployed site 

### CSS
- The [W3C Jigsaw CSS validator](https://jigsaw.w3.org/css-validator/) was used to check the CSS rules by direct input
- The validator shows no errors and 6 warnings. One warning is for imported Google Font which cannot be checked and the other 5 are browser compatibility warnings

### Python
- The [ExtendsClass Python Validator](https://extendsclass.com/python-tester.html) was used to check the Python files of the project by direct input
- No syntax errors were detected for either app.py or config.py 

### Lighthouse
- The Lighthouse function of the Browser Dev Tools was used to check the performance of MindTimer. The site rates as good, but not excellent. 
![Lighthouse](/static/images/lighthouse.png)

## Bugs 

During on-going testing, one team member accessed the website on their iPhone and found that the sound for the timer function does not work. Other team members access the website on their Android phones and reported that the sound did work. The cause of this discrepancy is unknown. 

# Features

The website has three main features:
- A timer that times down from 4 pre-set times - 2 minutes, 5 minutes, 10 minutes and 20 minutes. The timer plays an audio track when it times down, and video file plays as the background image. 
- A blog page that displays posts. Authenticated users (i.e. those who have registered an account) can add blog posts. 
- A resources page that acts as a signpost to other mindfulness, wellbeing and related resources. 

# Future Plans 
- Over time, the team plans to add further content and functionality
- One idea explored during the project planning phase was a timer function that counts down from 8 hours. At various intervals, the timer would flash up a message reminding the user to take breaks from work to do various things, like drinking water, stretching and doing breathing exercises. The 8 hour value measures a normal workday, and would be aimed at users who work from home, where it could be difficult to switch off and stop work after they have done their hours.
- To accompany this function, the site could be expanded to provide guides on these stretching and breathing exercises. 
- Users using this feature would then use the existing timer function to time discrete periods for these activities.
- A possible feature would an option for the user to change the audio file that plays when the timer is activated, just as the video backgrounds can be changed. 

# Deployment

## Local Deployment

To run this project locally make sure you have installed the following:
- an IDE of your choice (such as Gitpod, VS Code, etc.)
- have the following installed:
    - [Git](https://git-scm.com/)
    - [Python3](https://www.python.org/downloads/)
    - [PIP](https://pypi.org/project/pip/)

### Clone the GitHub Repository

To clone this project and run locally please follow the below steps:
1. Login into GitHub with your account
2. Go to the [project repository](https://github.com/AdamBoley/January-2022-Hackathon)
3. If using Gitpod click on the "Code" button (located next to the green "Gitpod" button)
4. From the dropdown menu copy the HTTPS URL
5. In your local IDE open the terminal
6. Change your working directory to the location where you want the cloned project saved
7. Type `git clone` and paste copied URL from Step 4
8. Press enter to create your local clone

### Install project dependencies
- Install project requirements by typing `pip install -r requirements.txt` in the terminal and pressing Enter

### Create a database on MongoDB

Register for a free account with [MongoDB](https://account.mongodb.com/account/register)

- Create a new Project and call it 'mindful timer'
- Create a Cluster, choose the free tier option and select your region
- Create a new database and call it 'mindfultimer_db'
- Create Collections named "user" and "session"

### Local deployment
- To run the project locally, in the terminal type `python3 app.py` and press Enter
- This will open a localhost address, which is provided in the terminal output
- Either copy and paste the URL into a new browser tab, or hover over it and click the link

### Deploy to Heroku

The website of this project requires back-end technologies such as a server, an application, and a database, so the website is deployed on [Heroku](https://www.heroku.com/), which is a cloud platform with a service supporting several programming languages, because GitHub Page can only host a static websites.

Before deploying the website to Heroku, there are three important steps to follow to make the application work in Heroku correctly.

1. Create `requirements.txt` file that contains the names of packages being used in Python. It is important to update the file if other packages or modules are required for installation during the project.
2. Create `Procfile` that contains the name of the application file so that Heroku knows what to run. Ensure it is formatted properly or deployment will fail.
3. Push them into GitHub.

Once above steps have been followed the website can be deployed. Please find the steps of the deployment in Heroku:

1. Create an account in [Heroku](https://signup.heroku.com/login)
2. Click **New** & **Create new app** to create a new app
3. Put an app name, which must be unique, choose a region and click create app
4. Go to **Deploy** section and click **Connect to GitHub**
5. Search for the repository by the repository name and connect it
6. Before clicking Enable Automatic Deploys, hidden variables such as IP address, PORT, SECRET_KEY, MONGO_URI and MONGO_DATABASE need to be recorded in Heroku. Go to **Settings**, click **Reveal Config Vars** and fill out necessary keys and values. 
7. Once all the hidden variables are recorded, then click **Enable Automatic Deploys** and click **Deploy Branch** (Main should be selected unless you want other branches to be deployed).
8. When the app is deployed by Heroku correctly, there is a confirmation message and you can access the app.

**Note**<br>
*It is important NOT to set `debug=True` when deploying the website.*


# Credits

## Media

- The audio file for the timer was obtained from [Pixabay](https://pixabay.com/music/search/genre/beats/?duration=480-)
- The video backgrounds for the timer page were obtained from [Pexels](https://www.pexels.com/): [Ocean background](https://www.pexels.com/video/sea-water-blue-ocean-7513671/), [Rain background](https://www.pexels.com/video/splatters-of-water-in-the-ground-2491284/), [Fire Background](https://www.pexels.com/video/fire-burning-3718525/), [Underwater background](https://www.pexels.com/video/school-of-fish-in-the-deep-blue-sea-5358755/), [Buddha background](https://www.pexels.com/video/a-buddha-statue-peacefully-meditating-6448150/) 

## Images

- Blog images from [Pexels](https://www.pexels.com/)
- Resource hero image from [Unsplash](https://unsplash.com/)
- Illustration from [Undraw by IRA Design](https://undraw.co/illustrations)

## Resources

The following resources were used in the Resources page of the Mindful Timer website

[NHS mental health advice](https://www.nhs.uk/mental-health/self-help/tips-and-support/mindfulness/)

[The Human Condition](https://thehumancondition.com/)

[Active Wellness](https://www.activewellness.com/blog)

[Mindful](https://www.mindful.org/)

[Additude](https://www.additudemag.com/)

[Oxford Mindfullness](https://www.oxfordmindfulness.org/)

[Free Mindfulness](https://www.freemindfulness.org/welcome)

[The Wellness Society](https://thewellnesssociety.org/)

[Mindfulness for Teens](http://mindfulnessforteens.com/)

[Smiling Mind](https://www.healthdirect.gov.au/smiling-mind)

[Peak](https://www.peak.net/)

[Happify](https://www.happify.com/)

[Insight Timer](https://insighttimer.com/)

[Ten Percent](https://www.tenpercent.com/podcast)

[Daily Meditation Podcast](https://player.fm/series/daily-meditation-podcast)

[Meditation Minis](https://meditationminis.com/)

## Acknowledgements

The team: 
- [Naoise Gaffney](https://github.com/NaoiseGaffney)

- [Marina Pavlovic](https://github.com/FruitbatM)

- [Goran Kuzma](https://github.com/kuzGo)

- [Ewa Kuk](https://github.com/Eva-Kuk)

- [Adam Boley](https://github.com/AdamBoley) (and his cat)

Our Facilitator, [Aisha Bushell](https://www.linkedin.com/in/aishabushell/)
