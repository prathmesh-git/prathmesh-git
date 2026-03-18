# Prathmesh Pimpalshende

**Full-Stack Developer · MERN Stack · AI Integration**  
Nagpur, India · [LinkedIn](https://www.linkedin.com/in/prathmesh-pimpalshende/) · [Email](mailto:prathmpimpalshende@gmail.com)

---

## About

Final-year Computer Science student at GH Raisoni University (2022–2026), building full-stack web applications that go beyond CRUD. I work across the MERN stack, integrate AI APIs into production workflows, and ship projects with real deployments — not just local demos.

My recent work spans real-time collaborative apps with Socket.IO, AI-powered media analysis tools using LLMs and Whisper, and containerized deployments via Docker and Render. I care about architecture, clean code, and building things that actually solve problems.

---

## Technical Skills

**Frontend**  
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=flat-square&logo=bootstrap&logoColor=white)

**Backend**  
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socket.io&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-FF6C37?style=flat-square&logo=postman&logoColor=white)

**Databases**  
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=flat-square&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=flat-square&logo=mysql&logoColor=white)

**AI & Integrations**  
![OpenAI](https://img.shields.io/badge/OpenAI_Whisper-412991?style=flat-square&logo=openai&logoColor=white)
![Groq](https://img.shields.io/badge/Groq_LLaMA_3-F55036?style=flat-square&logoColor=white)
![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=flat-square&logo=cloudinary&logoColor=white)
![Leaflet](https://img.shields.io/badge/Leaflet-199900?style=flat-square&logo=leaflet&logoColor=white)

**DevOps & Tools**  
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=black)

**Other**  
![Java](https://img.shields.io/badge/Java_(DSA)-007396?style=flat-square&logo=java&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)

---

## Projects

### [Unreel](https://github.com/prathmesh-git/Unreel) — AI Fact-Checker for Viral Videos · [unreeled.in](https://www.unreeled.in/)
> Detects bias, verifies factual claims, and exposes misinformation in YouTube Shorts, Instagram Reels, and TikTok videos.

- Transcribes video audio using **OpenAI Whisper** and extracts on-screen text via **OCR** from key video frames
- Identifies and fact-checks claims using **Groq LLaMA 3** against live web sources via **Tavily Search**
- Measures bias on a 0–100 scale with detection indicators; persists results to MongoDB for retrieval
- Containerized with **Docker** and deployed on **Render**; frontend built with React 18 + Vite

`React` `Node.js` `Express` `MongoDB` `OpenAI Whisper` `Groq LLaMA 3` `Tavily` `Docker` `Render`

---

### [SyncFlow](https://github.com/prathmesh-git/SyncFlow) — Real-Time Collaborative Task Manager · [Live Demo](https://sync-flow-seven.vercel.app)
> Kanban-style task board with real-time sync, conflict detection, and smart workload assignment.

- Real-time multi-user collaboration via **Socket.IO** — live task updates across all connected clients
- **Conflict detection system** — prevents data overwrites when multiple users edit the same task simultaneously
- **Smart Assign** algorithm — automatically distributes tasks to the user with the fewest active items
- Full activity log tracking task creation, updates, deletions, and assignments in real time
- Deployed: frontend on **Vercel**, backend on **Render**

`React` `Node.js` `Express` `MongoDB` `Socket.IO` `JWT` `DnD Kit` `Vercel` `Render`

---

### [Cravio — From Craving to Cart](https://github.com/prathmesh-git/Cravio-From-craving-to-cart) *(In Progress)*
> AI-powered food discovery and delivery platform combining traditional ordering with short-form video and smart recommendations.

- **Khavo AI** — in-app AI assistant providing personalized food recommendations based on user cravings
- Reels-based food discovery feed with view tracking, engagement metrics, and reel-to-order conversion analytics
- Seller dashboard with menu management, reel uploads, and analytics via **Recharts/Chart.js**
- Location support via **OpenStreetMap + Leaflet** — address search, map-pin selection, saved addresses
- Modular REST API with **Cloudinary** media storage and **JWT** authentication

`React` `Node.js` `Express` `MongoDB` `Cloudinary` `OpenStreetMap` `Leaflet` `Recharts` `JWT`

---

### [Wanderlust](https://github.com/prathmesh-git/Wanderlust) — Property Listing Platform
> Airbnb-style web application for listing, discovering, and booking properties.

- Full CRUD for property listings with user authentication and session management
- MVC architecture using Express.js and EJS, with Cloudinary for image uploads

`Node.js` `Express.js` `MongoDB` `Bootstrap` `EJS` `Cloudinary`

---

### [Weatherly](https://github.com/prathmesh-git/Weatherly) · [Live](https://weatherly-six-sand.vercel.app)
> Real-time weather application built with React and Vite, deployed on Vercel.

`React` `Vite` `Weather API` `Vercel`

---

### [Open Media Flow](https://github.com/Sk-Mahammad-Irfan/intern_media_ai) *(Internship — Digital Guruji)*
> Collaborative media platform integrating AI APIs, built during internship.

- Contributed to frontend–backend integration, API handling, and team-based version-controlled development

`React` `Node.js` `MongoDB` `AI APIs`

---

## Experience

**Web Development Intern — Digital Guruji** *(Remote)*  
*April 2025 – July 2025*

- Built responsive web interfaces using HTML, CSS, JavaScript, and Bootstrap
- Assisted in debugging and implementing full-stack features on production projects
- Contributed to the Open Media Flow platform in a collaborative team environment

---

## Education

**B.Tech — Computer Science & Engineering**  
GH Raisoni University, Amravati · 2022 – 2026  
CGPA: **7.77 / 10**

---

## Certifications & Training

- **Full Stack Web Development & DSA in Java** — Apna College *(2025 – Present)*
- **AI/ML Hackathon Participant** — Deepfake Detection Project, University Level

---

## Currently Learning

- Advanced React patterns and state management
- System design and scalable backend architecture
- Data Structures & Algorithms in Java

---

## GitHub Stats

<p align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=prathmesh-git&show_icons=true&theme=github_dark&hide_border=true&count_private=true" height="160"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=prathmesh-git&layout=compact&theme=github_dark&hide_border=true" height="160"/>
</p>

---

## Let's Connect

I'm open to internships, full-stack roles, and interesting collaboration opportunities.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/prathmesh-pimpalshende/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:prathmpimpalshende@gmail.com)
[![Unreel](https://img.shields.io/badge/Unreel-Live_Project-black?style=flat-square)](https://www.unreeled.in/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/prathmesh-git)
