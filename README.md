<div align="center">

<svg width="100%" height="250" viewBox="0 0 900 250" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <!-- Dark gradient background -->
    <linearGradient id="bgGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0d1117;stop-opacity:1" />
      <stop offset="50%" style="stop-color:#0f2a4a;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#001d3d;stop-opacity:1" />
    </linearGradient>
    <!-- Cyan glow gradient for text -->
    <linearGradient id="textGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#90e0ef;stop-opacity:1" />
      <stop offset="50%" style="stop-color:#00b4d8;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#0077b6;stop-opacity:1" />
    </linearGradient>
    <!-- Glow filter -->
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <!-- Wave clip path -->
    <clipPath id="waveClip">
      <path d="M0,0 L900,0 L900,220 Q675,250 450,230 Q225,210 0,240 Z"/>
    </clipPath>
  </defs>

  <!-- Background -->
  <rect width="900" height="250" fill="url(#bgGrad)" rx="0"/>

  <!-- Animated wave shape at bottom -->
  <path d="M0,200 Q225,170 450,190 Q675,210 900,180 L900,250 L0,250 Z" fill="#00b4d8" opacity="0.12">
    <animate attributeName="d"
      values="M0,200 Q225,170 450,190 Q675,210 900,180 L900,250 L0,250 Z;
              M0,210 Q225,185 450,200 Q675,215 900,190 L900,250 L0,250 Z;
              M0,200 Q225,170 450,190 Q675,210 900,180 L900,250 L0,250 Z"
      dur="4s" repeatCount="indefinite"/>
  </path>
  <path d="M0,215 Q225,190 450,205 Q675,220 900,195 L900,250 L0,250 Z" fill="#0077b6" opacity="0.15">
    <animate attributeName="d"
      values="M0,215 Q225,190 450,205 Q675,220 900,195 L900,250 L0,250 Z;
              M0,225 Q225,200 450,215 Q675,230 900,205 L900,250 L0,250 Z;
              M0,215 Q225,190 450,205 Q675,220 900,195 L900,250 L0,250 Z"
      dur="5s" repeatCount="indefinite"/>
  </path>

  <!-- Glowing dot particles -->
  <circle cx="80" cy="60" r="2" fill="#00b4d8" opacity="0.6">
    <animate attributeName="opacity" values="0.2;0.9;0.2" dur="3s" repeatCount="indefinite"/>
  </circle>
  <circle cx="820" cy="50" r="3" fill="#90e0ef" opacity="0.5">
    <animate attributeName="opacity" values="0.1;0.8;0.1" dur="2.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="150" cy="180" r="1.5" fill="#00b4d8" opacity="0.4">
    <animate attributeName="opacity" values="0.3;1;0.3" dur="4s" repeatCount="indefinite"/>
  </circle>
  <circle cx="750" cy="170" r="2.5" fill="#90e0ef" opacity="0.5">
    <animate attributeName="opacity" values="0.2;0.7;0.2" dur="3.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="450" cy="30" r="2" fill="#00b4d8" opacity="0.4">
    <animate attributeName="opacity" values="0.1;0.6;0.1" dur="2s" repeatCount="indefinite"/>
  </circle>

  <!-- Horizontal accent line -->
  <line x1="280" y1="155" x2="620" y2="155" stroke="#00b4d8" stroke-width="1" opacity="0.4">
    <animate attributeName="opacity" values="0.2;0.6;0.2" dur="3s" repeatCount="indefinite"/>
  </line>

  <!-- Main Name: Abu Rayhan -->
  <text
    x="450" y="115"
    font-family="'Segoe UI', Arial, sans-serif"
    font-size="64"
    font-weight="900"
    text-anchor="middle"
    fill="url(#textGrad)"
    filter="url(#glow)"
    letter-spacing="4">
    Abu Rayhan
    <animate attributeName="opacity" values="0;1" dur="1.5s" fill="freeze"/>
  </text>

  <!-- Subtitle -->
  <text
    x="450" y="170"
    font-family="'Segoe UI', Arial, sans-serif"
    font-size="17"
    font-weight="400"
    text-anchor="middle"
    fill="#90e0ef"
    letter-spacing="2"
    opacity="0">
    Full-Stack Web Developer  &amp;  AI Automation Creator
    <animate attributeName="opacity" values="0;0.85" dur="2s" begin="0.8s" fill="freeze"/>
  </text>
</svg>

<!-- ═══════════════ TYPING HEADLINE ═══════════════ -->
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=00B4D8&center=true&vCenter=true&width=700&lines=Full-Stack+Web+Developer;React+%26+Next.js+Specialist;Backend+%26+API+Architect;AI+Automation+Creator;Building+Digital+Products+that+Matter)](https://git.io/typing-svg)

<br/>

[![About](https://img.shields.io/badge/About%20Me-%230d1117.svg?style=for-the-badge&logo=About.me&logoColor=00b4d8)](https://rayhanwebdev.vercel.app/#about)
[![Skills](https://img.shields.io/badge/Skills-%230d1117.svg?style=for-the-badge&logo=stackshare&logoColor=00b4d8)](#-technical-skills)
[![Projects](https://img.shields.io/badge/Projects-%230d1117.svg?style=for-the-badge&logo=github&logoColor=00b4d8)](#-featured-projects)
[![Contact](https://img.shields.io/badge/Contact-%230d1117.svg?style=for-the-badge&logo=gmail&logoColor=00b4d8)](#-contact)
[![Portfolio](https://img.shields.io/badge/Portfolio-%2300b4d8.svg?style=for-the-badge&logo=vercel&logoColor=white)](https://rayhanwebdev.vercel.app/)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=rayhan309&label=Profile%20Views&color=00b4d8&style=flat-square)
[![GitHub followers](https://img.shields.io/github/followers/rayhan309?label=Followers&style=social)](https://github.com/rayhan309)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abu-rayhan-dev-2514b5390/)
[![Twitter/X](https://img.shields.io/badge/X%20%2F%20Twitter-Follow-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/AbuRayhan1818)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-Chat-25D366?style=flat-square&logo=whatsapp&logoColor=white)](https://wa.me/8801323399685)

</div>

---

## 👋 About Me

```typescript
const rayhan: Developer = {
  name:       "Abu Rayhan",
  title:      "Full-Stack Web Developer & AI Automation Creator",
  location:   "Gopalganj Sadar, Dhaka Division, Bangladesh 🇧🇩",
  portfolio:  "https://rayhanwebdev.vercel.app/",
  focus:      [
    "Full-Stack Web Application Development",
    "React & Next.js Frontend Architecture",
    "Backend API Design & Development",
    "Database Design & Optimization",
    "AI Automation & Intelligent Workflows",
  ],
  currentlyLearning: ["Advanced AI integrations", "Distributed systems"],
  openToWork: true,
};
```

I am a full-stack web developer passionate about crafting high-performance, production-ready web applications. I work across the entire stack — designing intuitive React & Next.js frontends, building robust Node.js and Go backends, and engineering reliable database layers with MongoDB, PostgreSQL, and Redis.

Beyond conventional development, I build **AI automation solutions** that help businesses streamline workflows, reduce manual overhead, and unlock new capabilities. I care deeply about clean architecture, developer experience, and shipping software that genuinely holds up in production.

---

## 🛠 Technical Skills

### 🌐 Languages & Web Fundamentals

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

---

### ⚛️ Frontend Development

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![TanStack Query](https://img.shields.io/badge/TanStack%20Query-FF4154?style=for-the-badge&logo=reactquery&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Gatsby](https://img.shields.io/badge/Gatsby-663399?style=for-the-badge&logo=gatsby&logoColor=white)
![Redux Toolkit](https://img.shields.io/badge/Redux%20Toolkit-764ABC?style=for-the-badge&logo=redux&logoColor=white)

---

### 🔧 Backend & Database

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![Gin](https://img.shields.io/badge/Gin-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)

---

### ⚙️ Tools & Infrastructure

![Linux VPS](https://img.shields.io/badge/Linux%20VPS-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=for-the-badge&logo=socketdotio&logoColor=white)

---

### 📈 Growth & Performance Marketing

![Meta Ads](https://img.shields.io/badge/Meta%20Ads-0866FF?style=for-the-badge&logo=meta&logoColor=white)
![Instagram Ads](https://img.shields.io/badge/Instagram%20Ads-E4405F?style=for-the-badge&logo=instagram&logoColor=white)
![TikTok Ads](https://img.shields.io/badge/TikTok%20Ads-010101?style=for-the-badge&logo=tiktok&logoColor=white)

---

## 🚀 Featured Projects

<div align="center">

| Project | Description | Tech Stack | Link |
|:-------:|:-----------:|:----------:|:----:|
| **🛒 Hidden Urban** | A modern lifestyle & urban fashion platform delivering a refined online retail experience with curated product collections, category navigation, and seamless checkout. | Next.js · Node.js · MongoDB · Tailwind CSS | [![Live](https://img.shields.io/badge/Live%20Site-00b4d8?style=flat-square&logo=vercel&logoColor=white)](https://hiddenurban.com/) |
| **🛍️ NextBuy BD** | A high-performance e-commerce platform for the Bangladesh market, featuring product discovery, category-based browsing, fast delivery support, and a customer-first shopping experience. | Next.js · Express.js · MongoDB · Redis | [![Live](https://img.shields.io/badge/Live%20Site-00b4d8?style=flat-square&logo=vercel&logoColor=white)](https://nextbuybd.com/) |
| **🌿 Eco Fashion BD** | A sustainable fashion e-commerce store focused on eco-conscious clothing, clean UI design, and a streamlined path from product discovery to purchase. | Next.js · Node.js · PostgreSQL · Tailwind CSS | [![Live](https://img.shields.io/badge/Live%20Site-00b4d8?style=flat-square&logo=vercel&logoColor=white)](https://ecofashionbd.store/) |

</div>

<div align="center">

[![View All Projects](https://img.shields.io/badge/%F0%9F%94%97%20View%20All%20Projects-%230d1117?style=for-the-badge)](https://rayhanwebdev.vercel.app/projects)

</div>

---

## 📊 GitHub Statistics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=rayhan309&show_icons=true&theme=github_dark&bg_color=0d1117&border_color=00b4d8&icon_color=00b4d8&title_color=00b4d8&text_color=c9d1d9&hide_border=false&rank_icon=github" height="165" alt="GitHub Stats"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=rayhan309&layout=compact&theme=github_dark&bg_color=0d1117&border_color=00b4d8&title_color=00b4d8&text_color=c9d1d9&langs_count=8&hide_border=false" height="165" alt="Top Languages"/>

</div>

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=rayhan309&theme=dark&background=0d1117&border=00b4d8&stroke=00b4d8&ring=00b4d8&fire=ff6b6b&currStreakNum=ffffff&sideNums=c9d1d9&currStreakLabel=00b4d8&sideLabels=c9d1d9&dates=6e7681" alt="GitHub Streak Stats"/>

</div>

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=rayhan309&bg_color=0d1117&color=00b4d8&line=00b4d8&point=ffffff&area=true&area_color=00b4d820&hide_border=false&border_color=00b4d8&radius=8" alt="GitHub Activity Graph" width="100%"/>

</div>

---

## 💡 What I Build

<table>
<tr>
<td width="50%" valign="top">

### 🏗 Full-Stack Web Applications
End-to-end web platforms built with React or Next.js on the frontend and Node.js, Express, or Go (Gin) on the backend. I design scalable APIs, integrate databases thoughtfully, and ship products that perform in real-world conditions.

</td>
<td width="50%" valign="top">

### 🤖 AI Automation Solutions
Intelligent workflow tools that connect APIs, language models, and business logic to automate repetitive tasks, extract insights from data, and build smarter software pipelines.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🛒 E-Commerce Platforms
Full-featured online stores with product discovery, cart management, secure checkout, order tracking, and admin dashboards — optimized for conversion and designed for real users.

</td>
<td width="50%" valign="top">

### ⚡ Performance & Infrastructure
Real-time systems using Socket.IO, optimized database queries, Redis caching, Nginx reverse proxies, Docker containerization, and Linux VPS deployments for production-grade reliability.

</td>
</tr>
</table>

---

## 📬 Contact

<div align="center">

I am open to **freelance projects**, **collaborations**, and **technical conversations**.
The fastest way to reach me is via WhatsApp or my portfolio.

<br/>

[![Portfolio](https://img.shields.io/badge/%F0%9F%8C%90%20Portfolio-rayhanwebdev.vercel.app-00b4d8?style=for-the-badge&logo=vercel&logoColor=white)](https://rayhanwebdev.vercel.app/)
[![WhatsApp](https://img.shields.io/badge/%F0%9F%92%AC%20WhatsApp-%2B8801323399685-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/8801323399685)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abu-rayhan-dev-2514b5390/)
[![GitHub](https://img.shields.io/badge/GitHub-rayhan309-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/rayhan309)

<br/>

📍 **Location:** Gopalganj Sadar, Dhaka Division, Bangladesh
📱 **WhatsApp / Phone:** +8801323399685

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00b4d8,50:0f2a4a,100:0d1117&height=120&section=footer&text=Thanks%20for%20visiting!&fontSize=20&fontColor=90e0ef&fontAlignY=65&animation=fadeIn" width="100%"/>

*"Great software starts with the human on the other side of the screen."*

</div>
