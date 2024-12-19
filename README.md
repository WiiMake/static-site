# WiiMix Static Site

Landing page and Objective Data Store for WiiMix

## Objective JSON Files

Objectives are stored in `src/v1/objectives` in a consistent format. To add a new objective, create a new JSON file with the achievement ID. Savestates will be linked in an external server. Once the file is created, add the objective ID to `src/games/json` in the corresponding game. 

## Updating Landing Page

Ensure Tailwind is installed with `npm install -D tailwindcss`

Update stylesheet with `npx tailwindcss -i ./src/tw.css -o ./src/main.css --watch`