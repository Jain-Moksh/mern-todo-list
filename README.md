# MERN Todo List (Basic)

A minimal Todo app using the MERN stack:

- Frontend: React (Vite) in `src/`
- Backend: Node/Express in `server/`
- Database: MongoDB

No external URLs/APIs are used.

## Folder Structure

\`\`\`
.
├─ src/ # React (Vite) app
│ ├─ App.tsx
│ ├─ main.tsx
│ ├─ index.css
│ └─ vite-env.d.ts
├─ server/ # Node/Express API + MongoDB
│ ├─ config/
│ ├─ models/
│ ├─ server.js
│ ├─ package.json
│ └─ .env # local only (not committed)
└─ node_modules/
\`\`\`

## Quick Start

1. Backend (API)

- cd server
- npm install
- Create `server/.env`:
  - MONGODB_URI=your-mongodb-connection-string
  - PORT=5000
- Start the server:
  - npm run dev (if available) OR node server.js
  - API runs at http://localhost:5000

2. Frontend (React)

- From project root:
  - npm install
  - npm run dev
- Open the app at the URL printed by Vite (usually http://localhost:5173)

## Notes

- Keep your `.env` file private and out of version control.
- Adjust ports in `.env` or scripts if you change defaults.
