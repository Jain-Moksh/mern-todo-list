# MERN Todo List (Basic)

A minimal Todo app using the MERN stack:

- Frontend: React (Vite) in `src/`
- Backend: Node/Express in `server/`
- Database: MongoDB

No external URLs/APIs are used.

## 📁 Project Structure

```plaintext
TodoList/
├── src/                  # React (Vite) frontend
│   ├── App.tsx
│   ├── main.tsx
│   ├── index.css
│   └── vite-env.d.ts
│
├── server/               # Node.js + Express backend
│   ├── config/           # Database configuration
│   ├── models/           # Mongoose schemas
│   ├── server.js         # Server entry point
│   ├── package.json
│   └── .env              # Environment variables (not committed)
│
├── package.json          # Root dependencies (if used for both client & server)
├── README.md
└── node_modules/
```

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
