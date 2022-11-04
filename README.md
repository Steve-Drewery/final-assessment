# **Fitalytics**

# Description

## Purpose
The application is designed to help users keep a record of their workouts, as well as achieve their fitness goals. It does this by allowing users to create records with details of each workout they undertake, view the details of historical workout records, set and meet weekly goals, earn trophies based on milestones, and compete to climb the overall monthly ladders (based on number of workouts). 

## FEATURES/FUNCTIONALITY
- User Management
    > The ability to create a user account, as well as sign in, and sign out will be implemented using functionality made available by the Ruby Gem Devise. 
- Authorisation
    > Devise also allows us to segment functionality based on user authentication (e.g only members can access portal, create workouts, etc)
- Workouts
    >Add workout records to your account (including type, duration, distance, date, etc)

    >View a history of your previous workout records 
- Weekly goals
    >Add a weekly workout goal (i.e 4 workouts per week)

    >Your total number of weekly workouts will be displayed in your user portal (i.e "2/4 workouts completed this week")  
- Ladder
    >View a table ordered by how many workouts app users have completed in a given month. 

    Your position on this ladder will be displayed in your user portal (i.e You are 23/100 in the monthly ladder!) 
- Trophies
    >Earn trophies by completing milestones (i.e Reach #1 on overall ladder)

    >Trophies will be displayed in the Trophies page of the user portal. 

## Target Audience
At a high level, this application is for users who want to leverage digital tools to achieve their fitness goals. This could apply to: 
- Active individuals undertaking physical programs who would like to use an app to track their progress 
- People who struggle to work out consistently and want to leverage tracking and goal setting to help them maintain a regular routine. 
- People with health conditions that require they be mindful of their physical activity, and monitor their level of physical fitness. 
- Competitive People who would like to compete with others for higher workout activity (via their position in the ladder system) 

## Tech Stack

**Version control** 
- Git & Github

| Front End                 |                  | 
| :------------------------:|:-----------------:
| Programming Language      | Javascript 
| Front End Framework       | React      
| Deployment                | Netlify   
| Styling                   | Styled-components 
| Testing                   | Jest     
| HTTP Requests             | Axios   

| Back End                  |                  | 
| :------------------------:|:-----------------:
| Programming Language      | Ruby 2.7.5 
| Server Side Framework     | Rails 6.1.6   
| Testing                   | Rspec
| Gems                      | Devise 4.8 
| DBMS                      | Postgresql   
| Deployment                | Heroku 

# Dataflow Diagram
![Dataflowdiagram](docs\dataflow-diagram.png)

# Application Architecture Diagram
![Architecturediagram](docs\architecture-diagram.png)

# User Stories
- As a casual runner, I would like to be able to keep track of my previous run times so I can try to beat my time on my next run.
- As a competitive person, I would like to be able to share my workout with friends so we can compete against each other.
- As a gym junkie, I would like to be able to log complete workouts with reps/sets so I can improve next session.
- As a bodybuilder, I would like to be able to post photos to a live feed so I can promote my physique.
- As a world class athlete, I would like to be able to compete against people around the world from my hometown so I can show everyone I am the best.
- As a local runner, I would like to be able to track my location so I can keep track of how far I have run.
- As someone who struggles with motivation, I would like to have a reward system for reaching  my goals so I can motivate myself through positive reinforcement.
- As a busy business man, I would like a reminder or notification system to show when my friends workout and when my previous workout was so I can keep in touch with friends and keep track of my fitness.
- As a dietitian, I would like to be able to keep track of how many calories I am burning throughout a workout so I can program my diet more efficiently.

# Wireframes
![Addworkoutdesktop](docs\add-workout-desktop.png)
![Addworkouttablet](docs\addworkout-tablet-phone.png)
![Homepagedesktop](docs\homepage-desktop.png)
![Homepagetablet](docs\homepage-tablet-phone.png)
![Ladderdesktop](docs\monthly-ladder-desktop.png)
![Laddertablet](docs\monthly-ladder-tablet-phone.png)
![Homeportaldesktop](docs\portal-home-desktop.png)
![Homeportaltablet](docs\portal-home-tablet-phone.png)
![Signindesktop](docs\signin-desktop.png)
![Signintablet](docs\signin-tablet-phone.png)
![Signupdesktop](docs\signup-desktop.png)
![Signupdesktop](docs\signup-tablet-phone.png)
![Trophiesdesktop](docs\trophies-desktop.png)
![Trophiestablet](docs\trophies-tablet-phone.png)

# Trello Board

![Trello1](docs\trello-board.png)
![Trello2](docs\trello-board-2.png)