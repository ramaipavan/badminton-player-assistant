# Rally — Badminton Player Assistant

Rally is a responsive season planner for competitive junior badminton players. It includes tournament discovery, registration tracking, a personal schedule and calendar, and a travel planning checklist.

## Run locally

Install dependencies, then start the development server:

```sh
npm install
npm run dev
```

Create a production build with `npm run build`, or preview it with `npm run preview`.

## Features

- Filter 13 illustrative tournaments by age category and major/open challenge type, or search by club and location.
- Track registration status and see deadline countdowns.
- Add and remove personal schedule entries; review tournament dates and potential same-day schedule overlaps.
- Browse a month calendar combining tournaments and personal plans.
- Compare illustrative travel estimates for away events and use an interactive packing/travel checklist.
- Edit player name, category, home area, and season goal.
- Save profile, schedule, and registration changes in browser local storage.
- Installable PWA shell with a service worker for previously cached app assets.

## Sample data and limitations

Tournament dates, fees, venues, eligibility, travel costs, and availability are sample planning data, not verified event listings or live offers. Confirm details with tournament organizers and current travel providers. The service worker caches the app shell; it does not sync data across devices or provide live push notifications. Browser notification permission and push delivery are not configured.
