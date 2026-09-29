# Campus Balance

Campus Balance is a command-line student life management simulator written in Python. Play through a seven-day college week by balancing studies, attendance, health, happiness, money, energy, stress, and screen time.

Each day, you have 12 hours to spend on activities. Random events add unexpected choices, and a weekly report summarizes your results and highlights potential problem areas.

## Features

- Simulate a student’s college life over seven days.
- Choose from seven activities:
  - Attend classes
  - Study
  - Sleep
  - Exercise
  - Socialize
  - Use a phone
  - Work part-time
- Manage daily time and energy.
- Track money, health, stress, attendance, academic score, happiness, screen time, and sleep.
- Receive warnings when statistics reach concerning levels.
- Encounter a random event at the end of each day.
- View a weekly summary and identified problem areas.
- Save the final report to `reports/weekly_report.txt`.

## Technologies and Tools

- Python 3
- Python standard library:
  - `random` for random events
  - `os` for creating the report directory and saving the report

No third-party packages are required.

## Installation and Run

1. Install Python 3 if it is not already installed.
2. Place the project files in the same directory:

   ```text
   main.py
   activities.py
   data.py
   events.py
   report.py
   student.py

## Testing
The project does not currently include an automated test suite. You can test it manually:

Run the program and confirm the opening status is displayed.
Enter valid activity choices and check that time and statistics change.
Try invalid input, such as a letter or a number outside the menu, and confirm the program prompts you again.
Try selecting an activity when there is not enough time or energy.
Complete all seven days and confirm that the weekly report appears in the terminal.
Check that reports/weekly_report.txt exists and contains the final statistics and problem areas.
