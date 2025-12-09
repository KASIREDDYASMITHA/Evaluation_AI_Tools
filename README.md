# AI-Powered Daily Time Tracking & Analytics Dashboard

A responsive web app that helps users log daily activities in minutes and analyze how their 24 hours are spent each day. Built with Firebase Auth + Firestore and Chart.js. Includes an “Analyse” dashboard, a friendly “No data available” state, and responsive UI with micro-interactions.



## Problem statement coverage
- Authentication (Google) restricts access to tracker/dashboard.
- Activity logging with name, category (optional), and minutes.
- Validation ensures total ≤ 1440 minutes and shows remaining time.
- Date-based analytics dashboard with a pie chart and summary stats.
- “No data available” state with a friendly illustration and CTA.
- Analyse button triggers dashboard update for the selected date.
- Responsive design for mobile, tablet, and desktop.

## Tech stack
- HTML, CSS, JavaScript
- Firebase Authentication (Google) and Firestore
- Chart.js (pie chart)

## Features
- Secure sign-in and sign-out (Google)
- Date picker to manage daily logs
- Add, edit, and delete activities
- Remaining minutes indicator (out of 1440)
- Dashboard: total hours, activity count, pie chart by category
- Beautiful “No data available” view
- Responsive UI & smooth micro-interactions

## Firestore data structure
