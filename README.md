<div align="center">

# Marquis Pierre

**Full-stack developer building real-time web apps and browser extensions**

New York, NY · B.S. Computer Science, Lehman College (CUNY) · Open to junior software engineer and full-stack roles

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/marquis-pierre-263367183)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:marquispierre27@gmail.com)

</div>

---

## 🚀 Projects

### 📚 [YomiPop](https://github.com/MarquisPierre/YomiPop)
**A Japanese pop-up dictionary for Chrome, published on the Chrome Web Store, plus a flashcard web app: hover any word on any site, save it as a card with an AI sentence, picture and voice, then review it with spaced repetition.**

[![Chrome Web Store](https://img.shields.io/badge/Chrome_Web_Store-Add_to_Chrome-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white)](https://chromewebstore.google.com/detail/yomipop/ijooliheidehdicjpmnhhaiioajlmgmj)
[![Live Demo](https://img.shields.io/badge/Live_Demo-yomipop.vercel.app-C8352A?style=for-the-badge)](https://yomipop.vercel.app)
[![Try the Demo](https://img.shields.io/badge/Try_the_Demo-Sign_in-C8352A?style=for-the-badge&logo=keycdn&logoColor=white)](https://yomipop.vercel.app/sign-in)
[![Source Code](https://img.shields.io/badge/Source_Code-GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MarquisPierre/YomiPop)
[![CI](https://github.com/MarquisPierre/YomiPop/actions/workflows/ci.yml/badge.svg)](https://github.com/MarquisPierre/YomiPop/actions/workflows/ci.yml)

> 🔑 **Demo login:** `marquispierre27+demo@gmail.com` · `demoguy123`
> Sample decks are ready to review on the website. Install the extension to save your own words.

<img src="https://raw.githubusercontent.com/MarquisPierre/YomiPop/main/docs/demo.gif" alt="Hovering a Japanese word on NHK News, then building a card with an AI sentence and a picture" width="700">

**Tech:** ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Chrome Extension](https://img.shields.io/badge/Chrome_Extension_(MV3)-4285F4?style=flat-square&logo=googlechrome&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white) ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![Fastify](https://img.shields.io/badge/Fastify-000000?style=flat-square&logo=fastify&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white) ![Gemini](https://img.shields.io/badge/Gemini_API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white) ![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat-square&logo=tailwind-css&logoColor=white) ![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

- **Instant, offline dictionary:** 200,000+ entries stored in the browser (IndexedDB), with my own conjugation engine so 食べた finds 食べる
- **One-key card builder** right on the page: pick meanings, keep the page's sentence or have **Gemini** write one, add an **Unsplash** picture or your own, and hear it in a natural AI voice
- **Spaced-repetition review app** using the FSRS scheduler, with decks, undo and daily new-card limits
- **Secure by default:** email verification and Google sign-in, ownership checks on every API route, and API keys that never leave the server
- **Tested on every push:** 50+ unit and API tests against a real PostgreSQL database, plus Playwright end-to-end and accessibility (axe) tests, all in GitHub Actions
- **Documented decisions:** 15 architecture trade-offs in a [decision log](https://github.com/MarquisPierre/YomiPop/blob/main/docs/decisions.md)

### 💬 [NodeSync](https://github.com/MarquisPierre/NodeSync)
**A full-stack, real-time chat app: text channels, direct messages, voice, video, and screen sharing in one place.**

[![Live Demo](https://img.shields.io/badge/Live_Demo-nodesync.onrender.com-5865F2?style=for-the-badge)](https://nodesync.onrender.com)
[![Source Code](https://img.shields.io/badge/Source_Code-GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MarquisPierre/NodeSync)

**Tech:** ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white) ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white) ![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=flat-square&logo=socket.io&logoColor=white) ![LiveKit](https://img.shields.io/badge/LiveKit-FF4D4D?style=flat-square) ![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat-square&logo=tailwind-css&logoColor=white)

- **Redesigned the DM system** from server-based to user-based and migrated existing data to the new schema with no history lost
- **Real-time messaging** over WebSockets, with every event delivered only to users who belong to that chat
- **Voice, video, and screen sharing** in channels and 1-on-1 DMs, powered by LiveKit (WebRTC), with server-issued access tokens
- **Friends and direct messages** that work across servers, with live unread badges and friend requests
- **Server-side authorization** on every route, plus role-based permissions

### 🗂️ Earlier projects
- **[Web Scraper](https://github.com/MarquisPierre/Web-Scraper):** an Amazon price tracker with scheduled scraping and email alerts (Next.js, MongoDB, Nodemailer)

---

## 💻 Skills
**Languages:** ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Frontend:** ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white) ![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat-square&logo=tailwind-css&logoColor=white) ![Chrome Extensions](https://img.shields.io/badge/Chrome_Extensions-4285F4?style=flat-square&logo=googlechrome&logoColor=white)

**Backend:** ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white) ![Fastify](https://img.shields.io/badge/Fastify-000000?style=flat-square&logo=fastify&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white) ![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=flat-square&logo=socket.io&logoColor=white) ![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)

**Databases:** ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

**Testing & DevOps:** ![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white) ![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white) ![Render](https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=black)
