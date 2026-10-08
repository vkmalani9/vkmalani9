<h1 align="center">Vikram Jangid Malani</h1>

<p align="center">
  <b>Full-Stack Engineer · React Native Expert · Systems that ship</b><br/>
  Ahmedabad, India &nbsp;·&nbsp;
  <a href="mailto:vikramjangid203@gmail.com">vikramjangid203@gmail.com</a> &nbsp;·&nbsp;
  <a href="https://linkedin.com/in/vikram-jangid-malani-35116023b">LinkedIn</a>
</p>

---

### About

I'm a full-stack engineer with 4+ years of building products from the first commit to production: mobile and web UIs, APIs, microservices, data, cloud, and the CI/CD pipeline that ships them.
React Native is my core. I go deep on native performance and architecture, and I'm just as comfortable designing the backend, database and infrastructure the app runs on.
I've shipped consumer and enterprise platforms used by hundreds of thousands of people. Some started on a blank page; others had to scale overnight.

### What I go deep on

**Mobile and frontend**
- **React Native**: RN 0.8x on the New Architecture (Fabric, TurboModules, JSI), Hermes, strictly typed navigation
- **Performance**: 60fps lists and gestures, Reanimated, render-cost profiling, startup and bundle tuning
- **Server-Driven UI**: screens composed from a backend schema, so layouts change without an app-store release
- **Web**: React, Next.js and TailwindCSS dashboards and admin portals

**Backend and systems**
- **APIs and services**: Node.js / Express 5, FastAPI, PHP, REST, gRPC microservices, OpenAPI / Swagger
- **Data**: MongoDB, PostgreSQL, MySQL, Redis caching and queues, vector databases
- **Security**: OTP auth, JWT/JWKS verification, role-based permissions, Zod-validated contracts end to end
- **Architecture**: pnpm monorepos (28+ TypeScript packages) with enforced boundaries, so teams ship in parallel without collisions

**Cloud and AI**
- **DevOps**: AWS, Docker, Kubernetes, GitHub Actions CI/CD
- **AI**: LLM features, AI agents, MCP servers and tool calling, LangGraph, n8n automations

### Open source

**[react-native-phone-number-hint](https://github.com/vkmalani9/react-native-phone-number-hint)** · *[npm](https://www.npmjs.com/package/react-native-phone-number-hint)*
- Problem: login screens still ask for a phone number the device already knows, and older RN helpers wrap Google's deprecated `HintRequest` API.
- A permission-free TurboModule on the current Phone Number Hint API (`GetPhoneNumberHintIntentRequest`). No contacts, phone, or SMS permissions. Concurrent calls share one chooser; cancel and missing Play services resolve `null`.
- Kotlin + New Architecture, iOS autofill `TextInput` props, CI, and MIT. `npm install react-native-phone-number-hint`

### Selected engineering work

**Enterprise B2C + B2B service platform** · *React Native, Node.js, gRPC, MongoDB, Redis*
- Problem: consumers, staff and business owners each needed their own app, all running on the same live operational data.
- Customer and partner apps built from one monorepo with shared domain, design-system and API packages.
- Core business and auth microservices talk over gRPC, with JWKS-verified REST at the edge. A Server-Driven UI pipeline drives context-aware screens, and queue and booking state update in real time.

**Real-time ride-hailing platform** · *React Native, Node.js*
- Separate rider and driver apps for auto, bike and cab, with live location tracking and dynamic matching on the backend.

**High-concurrency fantasy sports and prediction app** · *React Native, Node.js*
- Grew to **140K+ active users in its first month**. The backend was scaled to absorb contest-time traffic spikes.

**Fintech recharge and payments app** · *React Native, Node.js*
- Multiple payment gateways integrated for high availability, reliable transaction processing and strong data security.

**Finance dashboard and assessment platform** · *React, Node.js / PHP, MySQL, Razorpay / Stripe*
- A high-volume finance dashboard with role-based access, plus a test engine with real-time auto-save, payments and LLM-generated performance summaries.

### Stack

**Mobile & Web** &nbsp;
![React Native](https://img.shields.io/badge/React_Native-20232A?logo=react&logoColor=61DAFB)
![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind-06B6D4?logo=tailwindcss&logoColor=white)

**Backend** &nbsp;
![Node.js](https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?logo=express&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?logo=php&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-244c5a?logo=google&logoColor=white)

**Data** &nbsp;
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white)

**Cloud & AI** &nbsp;
![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?logo=langchain&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?logo=n8n&logoColor=white)

### How I build

- **Own it end to end.** UI, API, data and deploy are one problem, not four tickets.
- **Performance is a feature.** If it drops frames or adds latency, it isn't done.
- **Contracts before code.** Typed schemas shared between client and server.
- **AI-native workflow.** Agents, MCP tooling and LLM-assisted review help me ship faster without lowering the bar.

---

<p align="center"><i>Open to senior full-stack and React Native roles. Reach me at <a href="mailto:vikramjangid203@gmail.com">vikramjangid203@gmail.com</a></i></p>
