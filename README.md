# NutriPath-app

NutriPath: A Health and Lifestyle Calorie-Tracking App
Project Outline
Nathan Huynh-Nguyen
COM 330 – Mobile App Development
Saint Leo University
Project Description
Overview
NutriPath is a mobile app for tracking your daily food intake and caloric intake. Users can log their meals and view a live caloric count and progress towards their goals.
Target Audience
This app is ideal for those who want a simple logging tool or those who don’t want the bloat of a traditional fitness tracker. Students, working professionals, or even casual gym-goers who want to track their progress without learning a complex system would be interested in something like this.
Value Proposition
Most calorie tracking apps have a bloated UI and/or require paying for a subscription. NutriPath will offer a more streamlined experience, removing unecessary elements and focusing on quick logging and easy progress vizualisation.
Problem Addressing
Statement of the Problem
Most people do not have a good understanding of what they eat and how much they eat. This leads to overweight/obesity issues and general lack of control over one’s health and wellbeing. The current solutions are too complicated and not focused enough.
Why This Matters
Having a good understanding of one’s diet is crucial to maintaining a healthy lifestyle. With the current state of affairs, it is difficult to determine whether someone is eating healthy or not. Having a tool that can help people keep track of their diet without requiring them to have any nutritional expertise will go a long way towards assisting them in developing better eating habits.
How This Project Solves It
NutriPath will be uncomplicated and focused on providing the essential functions needed to track one’s food intake and diet. It will log the information in an easily accessible manner and provide general insights and guidance, such as how many calories one consumed for the day and what their progress towards their goal is.
Platform
Operating System
The application will be an Android app created within the MIT App Inventor software, as this course focuses on this platform.
Device
It will be compatible with any Android device running Android 8.0 or higher. The application will not be resource intensive and will only use standard permissions (saving data).
Other Requirements/Considerations
The data storage solution will use a simple export/import system. This will allow for easy migration to another OS (such as iOS) should the need arise.
Front/Back End Support
Front End
The Front End will be created in App Inventor by using its visual design tools to create the desired UI and then writting code for the app functionality.
The application will have a few UI screens: a Home screen, an Add Meal screen, a Daily Log, and a Progress/History screen. All screens will be simplified to the point where the user does not have to put in more information than necessary to use the app. All screens will follow a consistent UI/UX pattern to avoid causing confusion.
Back End
The Back End will be a simple database to hold food entries and calorie totals. It will be implemented using the TinyDB block in App Inventor. 
Each log entry will be an object containing food name, calories, nutrients, meal type, and entry date/time. There is an option to implement a cloud database (such as Firebase) to provide synchronization functionality should the application be ported to iOS.
V. Functionality
Must Have Features
Logging of individual food entries with calories, name, and type.
Display of current day’s total calories and progress towards the daily goal.
Logging of individual food entries with calories, name, and type.
Meals can be categorized as breakfast, lunch, dinner, or others. Entries can be viewed per day or per week.
Stretch Features
Option to set/edit the daily goal. The goal will be displayed prominently on the Home Screen.
Nutrients (protein/fat/carbs) can be tracked alongside calories.
On-screen progress indicator (progress bar) that displays how much of the daily goal has been achieved.
Design (Wireframes)
Home/Dashboard Screen
The Home Screen will display the date, total daily calories, progress towards the daily goal (in a bar chart format), and an option to add a new entry.
Add Meal Screen
Add Meal Screen will have a form for logging a new entry. It will ask for food name, calories, type (dropdown menu), and nutrients. It will have a Save button that will save the entry and return to the Home Screen.
Daily Log Screen
Daily Log Screen will display all entries for the currently selected day, organized by type. Each entry will have the name and the calories.
Progress/History Screen
The Progress Screen will display a bar chart that shows the weekly total. It will allow the user to select a day and see how many calories they had on that day and what their progress towards their daily goal was at the end of that day.
Wireframe Files
The low-fidelity wireframes for each of the screens described above will be submitted as a part of this assignment along with this document. They will be placed in a /wireframes directory in this repository along with the README file described below.
GitHub Repository and Wiki
The outline will be committed to the project’s GitHub Wiki as the README.md file and uploaded to the main branch of the repository. As the project develops, the Readme and Wiki will be updated to reflect the current state of development. The Repository and Wiki links will be placed in the bottom of the README.md file so that the project can be found easily.
