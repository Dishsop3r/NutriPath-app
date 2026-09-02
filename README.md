# NutriPath: A Health and Lifestyle Calorie-Tracking App

**Author:** Nathan Huynh-Nguyen
**Course:** COM 330 – Mobile App Development
**Institution:** Saint Leo University

## I. Project Description

**Overview**
NutriPath is a mobile health and lifestyle application designed to help users track their daily food intake, monitor caloric consumption, and build sustainable eating habits. The app allows users to log meals throughout the day, view a running total of calories and macronutrients, and track progress toward personal health goals over time.

**Target Audience**
The primary audience includes individuals who want a simple, low-friction way to monitor their diet, including students, working professionals, and casual fitness enthusiasts who are not looking for the complexity of a full fitness-tracking ecosystem.

**Value Proposition**
Unlike many existing calorie trackers that rely on cluttered interfaces and paid subscriptions, NutriPath focuses on a clean, minimal logging experience with clear visual feedback, making it easier for users to stay consistent with tracking their eating habits.

## II. Problem Addressing

**Statement of the Problem**
Many people struggle to maintain awareness of their daily caloric and nutritional intake, which contributes to unhealthy eating patterns, difficulty managing weight, and a general lack of insight into personal health trends. Existing solutions are often overly complex, require manual barcode databases, or bury core tracking features behind paywalls.

**Why This Matters**
Poor dietary awareness is linked to a range of long-term health issues, including obesity and related chronic conditions. Providing an accessible, easy-to-use tracking tool lowers the barrier to entry for users who want to make informed decisions about their eating habits without needing nutrition expertise.

**How NutriPath Addresses It**
NutriPath simplifies the logging process, surfaces daily and weekly summaries in an easy-to-read format, and gives users immediate feedback on how their choices align with their personal calorie goals.

## III. Platform

- **Operating System:** Android, built with MIT App Inventor, consistent with the platform used throughout this course.
- **Device Requirements:** Standard Android smartphones and tablets running Android 8.0 (Oreo) or later, requiring only basic device permissions such as storage access.
- **Future Platform Considerations:** The data structure is designed to be portable, which would allow for a future iOS version if the project expanded beyond this course.

## IV. Front/Back End Support

**Front End**
- Built using MIT App Inventor's designer and blocks editor for the user interface and app logic.
- Screens include a Home dashboard, Add Meal entry form, Daily Log view, and Progress/History view.
- Interface emphasizes minimal input steps to reduce friction when logging a meal.

**Back End**
- Local data storage using App Inventor's TinyDB component to persist food entries, calorie totals, and user goals between sessions.
- Structured data model for each food entry, including name, calorie count, macronutrients, meal type, and timestamp.
- Potential future integration with a cloud database (such as Firebase) to support account syncing across devices.

## V. Functionality

**Core Features**
- Log a food item manually with name, portion size, and calorie count.
- View a running daily total of calories consumed versus a user-defined daily goal.
- Categorize entries by meal type: breakfast, lunch, dinner, and snacks.
- View historical logs by day or week to track eating patterns over time.

**Secondary Features**
- Set and edit a personal daily calorie goal.
- Basic macronutrient breakdown (protein, carbohydrates, fat) per entry.
- Simple progress indicators (e.g., a progress bar) showing percentage of daily goal consumed.

**Stretch Goals**
- Reminder notifications to log meals at typical meal times.
- Exportable summary of weekly intake.

## VI. Design (Wireframes)

- **Home / Dashboard Screen:** Displays the current day's date, a summary of total calories consumed versus the daily goal, a progress bar, and a button to add a new food entry.
- **Add Meal Screen:** A simple form with fields for food name, calorie count, meal type (dropdown), and an optional macronutrient breakdown, followed by a Save button that returns the user to the dashboard.
- **Daily Log Screen:** A scrollable list of all food entries logged for the selected day, grouped by meal type, with each entry showing the food name and calorie count.
- **Progress / History Screen:** A weekly view showing total calories per day as a simple bar chart, allowing the user to identify trends and compare days against their goal.

Wireframe files: *(place your wireframe images in a `/wireframes` folder in this repo and link them here once created)*
