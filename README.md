<div align="center">

# Francis Rey

### Engineering Lead — Full-Stack Platform Architecture

[![Portfolio](https://img.shields.io/badge/Portfolio-Live-00D9FF?style=for-the-badge&logo=cloudflare&logoColor=white)](https://frncsryddlbg.pages.dev)
[![React](https://img.shields.io/badge/React-19.2-61DAFB?style=for-the-badge&logo=react&logoColor=white)](https://react.dev)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.x-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org)
[![Node.js](https://img.shields.io/badge/Node-20+-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org)

</div>

---

## System Brief

I design and operate a **multi-domain web platform** that blends portfolio, AI, scientific tooling, and premium product surfaces under a shared architecture.

### Primary Objectives
- Deliver a high-density, route-rich frontend without sacrificing responsiveness.
- Keep third-party credentials server-side through dedicated proxy layers.
- Enforce security controls across auth, premium features, and sensitive routes.
- Maintain modular boundaries so independent feature hubs can evolve safely.

---

## Architecture

### Frontend Runtime
- **React 19 + TypeScript + Vite 7** for the main application shell (`/main/*`).
- Layered provider model for auth, payments, chat, notifications, and security controls.
- Mixed rendering ecosystem with integrated **Vue** and **SolidJS** entry flows.
- Route-level lazy loading plus predictive preloading for high-frequency navigation paths.
- PWA support via Workbox runtime caching strategies.

### Backend Boundary
- **Secure Auth Proxy (`oauth-proxy-server-secure.js`, :8081)**
  - OAuth token exchanges
  - WebAuthn / passkey registration and verification
  - JWT issuance and auth-oriented rate limiting
  - Security headers and hardened middleware
  - Twitch + time service proxy endpoints
- **API Proxy (`api-proxy/server.js`, :3001)**
  - Spoonacular and RapidAPI-backed integrations
  - Request mediation and secret isolation
  - Security telemetry ingestion endpoint with rate controls

### Data and Integration Layer
- Supabase-backed authentication/data paths
- PostgreSQL support in backend services
- External APIs integrated behind controlled proxy routes

---

## Platform Modules

### Core Product Surfaces
- Portfolio lifecycle: projects, skills, experience, certifications, contact.
- AI surfaces: agents, adaptive/personalized UX, neuroadaptive interfaces.
- Science Hub: astronomy, ISS/space telemetry, earth systems, biomedical datasets.
- Tools Hub: diagnostics, recommendation engines, time/data utilities.
- Premium commerce: subscription/paywall gates and entitlement-aware navigation.

### Specialized Capabilities
- Real-time interactive components (chat, typing, live dashboards).
- Browser ML pipelines (TensorFlow.js + MediaPipe) for perception-oriented UX.
- 3D and geospatial rendering stack for data-rich visual exploration.

---

## Security Posture

- Defense-in-depth middleware: Helmet, CORS policy, validation pipelines, rate limiting.
- Credential and token handling constrained to backend proxy servers.
- WebAuthn/passkeys and OAuth provider support (GitHub, Google).
- Protected and view-only route controls for sensitive/premium capabilities.
- Telemetry ingestion for security event visibility.

---

## Operational Model

### Local Environment
```bash
npm install
npm run dev
npm run server
node api-proxy/server.js
```

### Combined Frontend + Secure Auth Proxy
```bash
npm run dev:full
```

### Quality Gates
```bash
npm run lint
npm run test
npm run test:e2e
```

---

## Technology Profile

- **Frontend**: React, TypeScript, Vite, MUI, Tailwind, Framer Motion
- **Backend**: Node.js, Express
- **Auth/Data**: Supabase, PostgreSQL
- **ML**: TensorFlow.js, MediaPipe, Gemini API integration
- **Visualization**: Three.js, React Three Fiber, Cesium, MapLibre, Leaflet, Chart.js
- **Testing**: Vitest, Playwright, Jest
- **Deployment Targets**: Cloudflare Pages, Vercel, Netlify, Azure-ready workflows

---

## Engineering Focus

- Architecture evolution for large-route SPA systems
- Security hardening for auth and API mediation
- Performance tuning for high-interaction UI and visualization workloads
- Productizing advanced feature hubs with clear operational boundaries

---

## Contact

- Portfolio: https://frncsryddlbg.pages.dev
- Google Dev: https://g.dev/sngttncs
- Email: secretparakoranemailc@tutamail.com
