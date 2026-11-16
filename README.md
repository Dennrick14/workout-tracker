# FORM — Workout & Protein Tracker

A personal fitness dashboard for tracking strength training, activities, and daily protein intake.

## Features

- **Overview:** today's and yesterday's protein totals, monthly calendar with previous/next month navigation, and daily activity details.
- **Workout:** editable Monday–Sunday plan, exercise sets/reps, weights, plate configuration, tutorial links, completion checkboxes, and week duplication.
- **Other activities:** track badminton, pickleball, trail hikes, running, cycling, and custom activity types.
- **Protein:** reusable food groups, editable food protein values, meal/snack categories, daily food checklists, and manual protein entries.
- **Daily goal:** starts at 140g and can be changed in the Protein tab.
- **Persistence:** data is saved in the browser using localStorage.

## Run locally

Open `index.html` in a modern browser, or serve the folder with any static web server.

## Deploy

This is a static site and can be deployed with GitHub Pages or Vercel. For Vercel, import this repository and use the default static site settings.

## Data note

The current version stores data in the browser where it is used. Browser data is not automatically synchronized between devices or browsers. A future Supabase integration can provide account-based cloud sync and backups.
