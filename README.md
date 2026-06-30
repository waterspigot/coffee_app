# Espresso Tracker

A gamified espresso logging app for dialing in coffee shots and tracking progress over time. Log the details of each shot, get instant feedback on your brew ratio and a quality score, and level up as you pull more shots.

**Live demo:** https://connor-schuchmann.github.io/coffee_app/
## What it does

For each shot, you log:

- Bean name and roast date
- Grind size, dose, and yield
- Brew time
- Taste score (1–10) and tasting notes

From that input, the app calculates your **brew ratio** and **brew time**, and generates a **score** for the shot. Every shot is saved so you can review your history and spot what's working.

## Features

- **Shot logger** — capture all the variables that affect an espresso pull in one place
- **Brew ratio & time calculation** — automatic feedback on each shot's key metrics
- **Scoring** — each shot gets a score so you can compare pulls objectively
- **Feedback** — actionable advice basesd on your inputed stats 
- **Calendar view** — see your shots laid out by date
- **History view** — browse and review every shot you've logged
- **Leveling system** — your level climbs as you log more shots, turning practice into progress you can see

## Built with

- HTML / CSS / JavaScript
- Tailwind CSS for styling
- Browser `localStorage` for persistence — your shots are saved locally and remain after you close the tab

## Design decisions

The hardest and most interesting part of this project wasn't any single feature — it was the information architecture. Espresso has a lot of interacting variables, and the challenge was deciding how to structure them so the app stays simple to use shot-to-shot while still surfacing useful patterns over time. That meant choosing what to track, how to split it across the logging, calendar, history, and leveling tabs, and how the scoring and leveling logic should reward consistency. Getting that organization right is what makes the data actually useful rather than just stored.

## Notes

This was my first self-directed software project, built using an agentic coding workflow. Beyond the app itself, it was where I learned to scope a project, make product and data-model decisions, and direct an AI-assisted build from idea to a working, deployed application.
