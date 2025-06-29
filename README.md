# 🧩 StickLift (Mobile-First Game Setup)

StickLift is a 3D multiplayer stick puzzle game built using a monorepo approach for web and mobile.

## 🗂 Folder Structure

```
sticklift/
├── packages/
│   ├── core/         # Shared logic (JS)
│   ├── api/          # Mock or real backend API
│   ├── mobile-app/   # React Native app (primary UI)
│   └── web-app/      # Optional Vite + Three.js (Web viewer)
├── .gitignore
├── .prettierrc
├── README.md
└── package.json      # Yarn Workspaces
```

## 🚀 Setup

```bash
yarn install
```

## ✅ Current Version: v0.1.0

- [x] Monorepo initialized with Yarn Workspaces
- [x] Base folders created for core logic, mobile app, web app, and mock API
- [x] Git initialized in `sticklift/` folder
- [x] Project structure pushed to GitHub

## ✅ Development Checklist

### Core

- [ ] Define stick movement detection in `/core`
- [ ] Add scoring logic based on picked stick value

### API

- [ ] Add `getGameState()` to mock game state
- [ ] Add `recordScore()` and `resetGame()`

### Mobile App (`mobile-app`)

- [ ] Set up base React Native project (v0.78)
- [ ] Use WebView to load local canvas (`http://localhost:3000`)
- [ ] Test WebView on emulator or device

### Web App (`web-app`)

- [ ] Initialize Vite + React + R3F + Three.js
- [ ] Render 3D canvas with tray + stick mock
- [ ] Add OrbitControls or touch support for rotate/pan

### Optional

- [ ] Set up `.editorconfig`, ESLint, and Husky
- [ ] Create GitHub project board or issues to track tasks
