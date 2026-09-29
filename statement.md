# Project Statement: Campus Balance

## Problem Statement

College students must balance academic responsibilities with personal health, rest, social activities, finances, and technology use. Choices in one area can affect others: studying may improve academic performance but increase stress and use energy, while socializing may improve happiness but cost money and time.

Campus Balance provides an interactive way to explore these trade-offs. Players make daily decisions and see how those choices affect a student’s overall well-being throughout a simulated college week.

## Scope of the Project

Campus Balance is a single-player, text-based application written in Python. It simulates a student’s life over seven days, with 12 activity hours available each day.

The player can choose from seven activities: attending classes, studying, sleeping, exercising, socializing, using a phone, and working part-time. Activities and random events affect the student’s money, energy, health, stress, attendance, academic score, happiness, screen time, and sleep hours.

The application displays warnings when selected statistics reach concerning levels. At the end of the simulation, it produces a weekly report, identifies major problem areas, and saves the report to `reports/weekly_report.txt`.

This project is a simplified educational simulation. It does not use real student data or provide personalized health, financial, or academic advice.

## Target Users

- Students interested in how everyday choices can affect different aspects of college life.
- Beginner programmers learning Python programming concepts.
- Educators looking for a small example of an interactive, menu-driven project.

## High-Level Features

- **Daily activity selection:** Choose from seven student activities.
- **Time management:** Activities use different amounts of the 12 available hours per day.
- **Energy management:** Some activities require energy, while sleep restores it.
- **Student statistics:** Track money, energy, health, stress, attendance, academic score, happiness, screen time, and sleep.
- **Random events:** Respond to unexpected expenses, quizzes, invitations, club activities, and transport problems.
- **Warnings:** Receive alerts when selected statistics become concerning.
- **Weekly summary:** View final statistics and identified problem areas after seven days.
- **Report saving:** Save the weekly report as reports/weekly_report.txt.