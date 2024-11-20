# PYTHON-MINI-PROJECT
Personalized Fitness Tracker
Welcome to the Personalized Fitness Tracker! This project allows users to track various physical activities, calculate calories burned based on MET (Metabolic Equivalent of Task) values, and view summaries of their recent workout history.

Table of Contents
Introduction
Features
Installation
Usage
MET Values
Example Workflow
Contributing
License
Introduction
The Personalized Fitness Tracker is a beginner-friendly Python program designed to help users track their fitness activities. The program supports logging workouts, calculating calories burned, and viewing a summary of recent workouts in a visually appealing bar graph. The calories burned are estimated using MET values for different physical activities.

Features
Add workout sessions with activity type, duration, weight, and date.
Calculate calories burned based on MET values for different activities.
View a summary of workouts from the last 7 days, including total workout time and calories burned.
Visualize recent workout data using bar charts.
Clear workout history if desired.
Installation
Clone this repository:
git clone https://github.com/your-username/personalized-fitness-tracker.git
cd personalized-fitness-tracker
Install dependencies:
Make sure you have Python installed, along with the required packages:
pip install matplotlib
Usage
To run the fitness tracker, execute:
python fitness_tracker.py
Available Options:
Add a workout: Enter the type of activity, duration (in minutes), weight (in kg), and date (optional).
View summary for the last 7 days: Displays total workout time, calories burned, and a bar chart of daily calories.
Clear workout history: Removes all saved data (requires confirmation).
Exit: Ends the program.
MET Values
The program calculates calories burned based on the following MET (Metabolic Equivalent of Task) values:

Running: 9.8
Cycling: 7.5
Walking: 3.8
Yoga: 2.5
Swimming: 8.0
Weight Training: 6.0
The formula used to calculate calories burned is:
Calories = (MET value * 3.5 * weight in kg / 200) * duration in minutes
Example Workflow
Start the program and choose "Add a workout."
Enter activity type (e.g., "running"), duration, weight, and date.
View a summary of recent workouts to track progress visually.
Clear workout history when desired.
Contributing
Contributions are welcome! Feel free to fork this repository, make enhancements, and submit a pull request.
License
This project is licensed under the MIT License. Feel free to use, modify, and distribute as per the license terms.

