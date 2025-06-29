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

## ✅ Next Steps

- [ ] Add mock API structure in `/api`
- [ ] Define shared functions in `/core`
- [ ] Set up mobile-app with WebView
- [ ] Create canvas scene in web-app using Vite + R3F
