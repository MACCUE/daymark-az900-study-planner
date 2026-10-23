# Daymark

Daymark is a browser-based AZ-900 study planner. Choose an exam date, study pace, focus areas, and confidence ratings to create a personal revision schedule.

## Run locally

Open `index.html` in a modern browser. Your study plan and completion progress are stored locally in that browser. Use **Export CSV** to save a copy of the plan.

## Pitch deck

Open `pitch-deck.html` for the seven-slide presentation. Use the arrow keys or on-screen controls to navigate. Use the browser's print dialog to print or save the slides as a PDF.

## Deploy to Render

This repository includes a `render.yaml` Blueprint for the static site. In Render, choose **New + → Blueprint**, connect this GitHub repository, and deploy the detected `daymark-az900-study-planner` service. Render will publish the root directory; future pushes to `main` will trigger deployments.

## Current scope

The planner is a front-end prototype for AZ-900 exam preparation. Plans are generated in the browser; no account or server is required.
