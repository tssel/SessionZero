# SessionZero

SessionZero is a simple, mobile-friendly session timer for setting a goal, working until it is complete, and recording the next task.

## Run locally

Open `index.html` directly in a browser, or serve the folder with:

```sh
python3 -m http.server 4173
```

Then visit `http://localhost:4173`.

## Features

- Set a goal before starting a session
- Start, pause, resume, and end a timer
- Record what you did, your next task, and whether something was finished
- View past tasks on the Start screen
- Browse sessions in a monthly calendar
- See total minutes and session details by day
- Export sessions as JSON

## Data storage

SessionZero has no backend or account system. It stores:

- Completed sessions in `sessionZero.sessions`
- The active timer in `sessionZero.timer`
- The latest next task in `sessionZero.nextTask`

Data remains in the browser's localStorage and is not sent anywhere.

## Export and backup

Use **Export to JSON** on the History screen to download all saved sessions.
