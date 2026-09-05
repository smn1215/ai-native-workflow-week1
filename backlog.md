# Backlog: Household Chores App

## Task 1: Initialize Django Project & Setup Models
- Set up Django project and create the core app.
- Define models for `Chore` (title, description, points), `User` (extend default user to track total points), and `ChoreCompletion` (linking a user, a chore, completion status, and peer review status).
- Register models in Django Admin.

## Task 2: Build the Leaderboard View
- Create a view that calculates and ranks all users based on their total points for the current month.
- Create a template to display the leaderboard.

## Task 3: Task Assignment and Submission
- Create views and templates for users to see available chores.
- Build a form for users to submit a chore as "completed", pending review.

## Task 4: Peer Review System
- Build a view for roommates to see pending chores and approve them.
- Once approved, update the `ChoreCompletion` status and add points to the user's profile.
