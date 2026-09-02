**NutriPath: A Health and Lifestyle Calorie-Tracking App**

*Project Outline*

Nathan Huynh-Nguyen

COM 330 – Mobile App Development

Saint Leo University

# I. Project Description

1. Overview

   NutriPath is a mobile health and lifestyle application designed to help users track their daily food intake, monitor caloric consumption, and build sustainable eating habits. The app allows users to log meals throughout the day, view a running total of calories and macronutrients, and track progress toward personal health goals over time.

2. Target Audience

   The primary audience includes individuals who want a simple, low-friction way to monitor their diet, including students, working professionals, and casual fitness enthusiasts who are not looking for the complexity of a full fitness-tracking ecosystem.

3. Value Proposition

   Unlike many existing calorie trackers that rely on cluttered interfaces and paid subscriptions, NutriPath focuses on a clean, minimal logging experience with clear visual feedback, making it easier for users to stay consistent with tracking their eating habits.

# II. Problem Addressing

1. Statement of the Problem

   Many people struggle to maintain awareness of their daily caloric and nutritional intake, which contributes to unhealthy eating patterns, difficulty managing weight, and a general lack of insight into personal health trends. Existing solutions are often overly complex, require manual barcode databases, or bury core tracking features behind paywalls.

2. Why This Matters

   Poor dietary awareness is linked to a range of long-term health issues, including obesity and related chronic conditions. Providing an accessible, easy-to-use tracking tool lowers the barrier to entry for users who want to make informed decisions about their eating habits without needing nutrition expertise.

3. How NutriPath Addresses It

   NutriPath simplifies the logging process, surfaces daily and weekly summaries in an easy-to-read format, and gives users immediate feedback on how their choices align with their personal calorie goals.

# III. Platform

1. Operating System

   NutriPath will be developed as an Android application using MIT App Inventor, consistent with the platform used throughout this course.

2. Device Requirements

   The app is designed for standard Android smartphones and tablets running Android 8.0 (Oreo) or later, requiring only basic device permissions such as storage access for saving logged data.

3. Future Platform Considerations

   While the initial release targets Android, the underlying data structure is designed to be portable, which would allow for a future iOS version if the project were to expand beyond this course.

# IV. Front/Back End Support

1. Front End

   1. Built using MIT App Inventor's designer and blocks editor for the user interface and app logic.

   2. Screens include a Home dashboard, Add Meal entry form, Daily Log view, and Progress/History view.

   3. Interface emphasizes minimal input steps to reduce friction when logging a meal.

2. Back End

   1. Local data storage using App Inventor's TinyDB component to persist food entries, calorie totals, and user goals between sessions.

   2. Structured data model for each food entry, including name, calorie count, macronutrients, meal type, and timestamp.

   3. Potential future integration with a cloud database (such as Firebase) to support account syncing across devices.

# V. Functionality

1. Core Features

   1. Log a food item manually with name, portion size, and calorie count.

   2. View a running daily total of calories consumed versus a user-defined daily goal.

   3. Categorize entries by meal type: breakfast, lunch, dinner, and snacks.

   4. View historical logs by day or week to track eating patterns over time.

2. Secondary Features

   1. Set and edit a personal daily calorie goal.

   2. Basic macronutrient breakdown (protein, carbohydrates, fat) per entry.

   3. Simple progress indicators (e.g., a progress bar) showing percentage of daily goal consumed.

3. Stretch Goals

   1. Reminder notifications to log meals at typical meal times.

   2. Exportable summary of weekly intake.

# VI. Design (Wireframes)

1. Home / Dashboard Screen

   Displays the current day's date, a summary of total calories consumed versus the daily goal, a progress bar, and a button to add a new food entry.

2. Add Meal Screen

   A simple form with fields for food name, calorie count, meal type (dropdown), and an optional macronutrient breakdown, followed by a Save button that returns the user to the dashboard.

3. Daily Log Screen

   A scrollable list of all food entries logged for the selected day, grouped by meal type, with each entry showing the food name and calorie count.

4. Progress / History Screen

   A weekly view showing total calories per day as a simple bar chart, allowing the user to identify trends and compare days against their goal.

5. Wireframe Files

   *Low-fidelity wireframes for each of the above screens have been created and are included in the GitHub repository under the /wireframes folder, and referenced in the project README.*

# GitHub Repository and Wiki

This outline has been published to the project's GitHub repository as both the README.md file and the project Wiki. The repository also documents ongoing development progress as the term continues.

**GitHub Repository:** \[insert repository link here\]

**GitHub Wiki (Outline):** \[insert wiki link here\]