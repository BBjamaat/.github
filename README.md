# Available BB Rooms

Find available rooms in the BernoulliBorg building at the University of Groningen.

## Description

A simple app that checks the lecture and lab schedules and shows which rooms in BB are currently free. Originally made so we could find a spot to pray between classes.

## Data

Room and schedule data is in [`public/`](public/) — `LECTURE_ROOMS.json`, `LAB_ROOMS.json`, `LECTURE_ACTIVITY.json`, `LAB_ACTIVITY.json`, and `META.json`. The JSON files need to be downloaded manually from the university's Rooster (timetable) system. Ideally this would be fetched server-side or automated via GitHub Actions on deploy, but that's too try-hard for a personal tool.

## Setup

```bash
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.
