# DriveReach Driving School Dashboard

A responsive React + Vite driving school management dashboard with interactive demo data.

## Features
- Overview dashboard with live demo KPIs
- Instructor management (add, edit status, search/filter)
- Learner management (register, search/filter, profile drawer, progress updates)
- Lesson bookings (create, search/filter, change booking status)
- Payments (mark outstanding payments as paid, export demo action)
- Reports and performance summaries
- Demo messaging interface
- School profile settings
- Responsive desktop, tablet and mobile layouts
- Local browser persistence with `localStorage`

## Run locally
Requires Node.js 18 or later.

```bash
npm install
npm run dev
```

Open the local URL printed by Vite (usually http://localhost:5173).

## Production build
```bash
npm run build
npm run preview
```

## Demo mode
No database, API, authentication service or backend is used. Changes are stored in the browser's localStorage. Use **Settings → Reset demo data** to restore the original sample records.

## Notes
- All people, payments and bookings are fictional demo records.
- Messaging is a local UI demonstration, not connected to WhatsApp or a messaging provider.
- Payment status updates are local demo actions and do not move money.
- The date and activity figures are sample data and can be edited in `src/App.jsx`.
