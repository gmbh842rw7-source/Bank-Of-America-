bank-of-american/
├─ backend/             # Node.js + Express server
│  ├─ controllers/      # API controllers
│  ├─ models/           # MongoDB schemas
│  ├─ routes/           # API endpoints
│  ├─ sockets/          # Optional Socket.io notifications
│  ├─ seed.js           # Script to seed demo accounts
│  ├─ server.js         # Main backend server
│  └─ package.json      # Backend dependencies
├─ frontend/            # React + Tailwind dashboard
│  ├─ src/
│  │  ├─ components/    # React UI components
│  │  ├─ pages/         # Login, Dashboard, Admin, etc.
│  │  ├─ services/      # API service calls
│  │  └─ App.jsx        # Main app entry
│  ├─ package.json      # Frontend dependencies
│  └─ vite.config.js
├─ .gitignore
├─ README.md
└─ deploy.js            # Optional one-command local setup
