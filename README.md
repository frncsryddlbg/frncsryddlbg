<div align="center">

# Francis Rey

### Full-Stack Software Architect • Hokkaido, Japan 🇯🇵

[![Portfolio](https://img.shields.io/badge/Portfolio-Live-00D9FF?style=for-the-badge&logo=cloudflare&logoColor=white)](https://frncsryddlbg.pages.dev)
[![React](https://img.shields.io/badge/React-19.2-61DAFB?style=for-the-badge&logo=react&logoColor=white)](https://react.dev)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.x-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org)
[![Vite](https://img.shields.io/badge/Vite-7.x-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev)

</div>

---

## 🚀 What I’m Building

I build a **large, production-style portfolio platform** that combines:

- A route-rich React app (`/main/*`) with specialized feature hubs
- A multi-framework shell (React + Vue + Solid widgets)
- AI/ML experiences running in-browser
- Secure auth flows (OAuth + passkeys/WebAuthn)
- Backend proxy services that keep API secrets server-side

---

## 🧭 Platform Scope (Based on the Actual Site)

### Core Areas
- **Portfolio & Personal Hub**: Projects, skills, experience, certifications, contact
- **AI & Adaptive UX**: AI features, agents, personalization, neuroadaptive interfaces
- **Science Hub**: NASA, ISS tracking, solar activity, astronomy, Earth/geo datasets, bio/medical explorers
- **Developer Tools**: Resolution inspector, palette studio, itinerary planner, movie recommender, time tools
- **Interactive Entertainment**: Arcade games, brain games, real-time typing/chat experiences
- **Premium/Commerce**: Store, subscriptions, gated feature access, account profile/notifications

### Security-Centered Features
- Passkey diagnostics and WebAuthn support
- Protected/gated routes for secure modules
- Security wrappers and route monitoring across the app
- Telemetry ingestion and rate-limited backend endpoints

---

## 🏗️ Architecture Snapshot

### Frontend
- **React 19 + TypeScript + Vite 7**
- **MUI + Tailwind + Framer Motion**
- Code-split routes with aggressive preloading and predictive loading
- PWA configuration with Workbox runtime caching

### Multi-Framework Integration
- **Vue 3** components
- **SolidJS** pre-landing flow
- Additional specialized modules integrated into the same workspace

### Backend Services
- **`oauth-proxy-server-secure.js` (port 8081)**
  - OAuth token exchange
  - WebAuthn/passkey flows
  - JWT issuance, auth rate limiting, security headers
  - Twitch and time-related proxy endpoints
- **`api-proxy/server.js` (port 3001)**
  - Spoonacular proxy
  - RapidAPI integrations (including movie/covid data paths)
  - Security telemetry ingest endpoint

---

## 🧠 AI/ML + Data Capabilities

- TensorFlow.js model integrations (vision/object/pose pipelines)
- MediaPipe-based real-time perception components
- Google Gemini integration in AI features
- Data-heavy visual modules (charts, maps, geospatial views, 3D scenes)

---

## 🔐 Security & Auth Stack

- Helmet, CORS controls, input validation, and endpoint rate limiting
- JWT + Argon2/Bcrypt support in auth-related server paths
- OAuth providers (GitHub/Google) and passkeys/WebAuthn
- Client-side security controls with centralized enforcement wrappers

---

## 🛠️ Tech Stack (Primary)

- **Frontend**: React, TypeScript, Vite, MUI, Tailwind, Framer Motion
- **Backend**: Node.js, Express
- **Data/Auth**: Supabase, PostgreSQL
- **3D/Maps**: Three.js, React Three Fiber, Cesium, MapLibre, Leaflet
- **Testing**: Vitest, Playwright, Jest
- **Deployment Targets**: Cloudflare Pages, Vercel, Netlify, Azure-compatible workflows

---

## ⚡ Local Dev

```bash
npm install
npm run dev          # Frontend (Vite)
npm run server       # Secure OAuth/auth proxy (8081)
node api-proxy/server.js  # API proxy (3001)
```

Or run frontend + secure proxy together:

```bash
npm run dev:full
```

---

## 📊 GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=frncsryddlbg&show_icons=true&theme=radical&hide_border=true" height="165"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=frncsryddlbg&theme=radical&hide_border=true" height="165"/>

</div>

---

## 🤝 Connect

- 🌐 Portfolio: https://frncsryddlbg.pages.dev
- 🧪 Google Dev: https://g.dev/sngttncs
- 📬 Email: secretparakoranemailc@tutamail.com
