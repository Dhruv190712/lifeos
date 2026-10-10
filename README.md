# LifeOS

A calm, single-page personal tracker I vibe coded to keep my college life, family and friends in one place.

I built it to organise my academics and other commitments at college, and to get **one unified view of everything I have in a day across college, family and friends**, so I can be aware of what's coming and plan my day accordingly.

**Live demo:** https://Dhruv190712.github.io/lifeos/

## Features

- **Today view**: one screen with College, Family and Friends side by side, showing what's due today. Overdue items sit at the top of each area.
- **Four item types**: tasks, events, deadlines and reminders, each with its own colour.
- **Calendar**: month, week and day views.
- **Upcoming**: Overdue, Today, Tomorrow, This week, Next week, Later.
- **Everything**: search across all items, with filters for area, type, status, priority and date.
- **People**: names, relationship, birthday and notes, plus every item linked to each person.
- **Recurring items**: events repeat without creating duplicates, and recurring tasks and reminders roll to their next date when completed.
- **Quick add**: add an item from the Today page by typing and pressing Enter, or use **+ Add**.
- **Backups**: export and import all your data as a JSON file.
- **Alerts**: optional browser notifications while the tab is open.
- **Shortcuts**: `n` to add, `/` to search, `Esc` to close.

## Design decisions

The hardest part was deciding which areas to cover, which features to prioritise and how to reduce redundancy. Early versions had many tabs that showed the same content, such as separate lists for tasks, events, deadlines, reminders and overdue items. I merged them into five tabs (Today, Calendar, Upcoming, Everything, People) and used filters instead of duplicate pages.

## Privacy

- No account, no server, no tracking.
- No AI, no paid services, no external APIs.
- Your data is stored only in your own browser (`localStorage`) and never leaves your device.
- Clearing your browser data erases it, so use **Export data** now and then.

## Run it

It's a single file with no build step. Open `index.html` in any modern browser, or host it with GitHub Pages (Settings, then Pages, then deploy from the `main` branch).

## Tech

Plain HTML, CSS and JavaScript in one file. No frameworks and no dependencies.
