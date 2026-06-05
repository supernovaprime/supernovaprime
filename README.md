<!-- Animated Background & Header Illustration -->
<div align="center">

<svg width="860" height="280" viewBox="0 0 860 280" xmlns="http://www.w3.org/2000/svg" style="overflow:visible">
  <defs>
    <!-- Neon gradient palette -->
    <linearGradient id="neonBlue" x1="0%" y1="0%" x2="100%" y2="0%"><stop offset="0%" style="stop-color:#00d4ff"/><stop offset="100%" style="stop-color:#00a8ff"/></linearGradient>
    <linearGradient id="neonGreen" x1="0%" y1="0%" x2="100%" y2="0%"><stop offset="0%" style="stop-color:#39ff14"/><stop offset="100%" style="stop-color:#00ff88"/></linearGradient>
    <linearGradient id="neonViolet" x1="0%" y1="0%" x2="100%" y2="0%"><stop offset="0%" style="stop-color:#bc13fe"/><stop offset="100%" style="stop-color:#d900ff"/></linearGradient>
    <linearGradient id="neonGradient" x1="0%" y1="0%" x2="100%" y2="0%"><stop offset="0%" style="stop-color:#00d4ff"/><stop offset="33%" style="stop-color:#39ff14"/><stop offset="66%" style="stop-color:#bc13fe"/><stop offset="100%" style="stop-color:#00d4ff"/></linearGradient>
    
    <!-- Background star field -->
    <pattern id="stars" x="0" y="0" width="100" height="100" patternUnits="userSpaceOnUse">
      <circle cx="10" cy="15" r="1" fill="#ffffff" opacity="0.3"/>
      <circle cx="50" cy="5" r="1.5" fill="#39ff14" opacity="0.5"/>
      <circle cx="80" cy="40" r="1" fill="#00d4ff" opacity="0.4"/>
      <circle cx="30" cy="70" r="1" fill="#bc13fe" opacity="0.3"/>
      <circle cx="90" cy="90" r="0.5" fill="#ffffff" opacity="0.6"/>
    </pattern>
  </defs>
  
  <!-- Animated starry background -->
  <rect width="860" height="280" fill="#0a0a12">
    <animate attributeName="opacity" values="0.8;1;0.8" dur="3s" repeatCount="indefinite"/>
  </rect>
  
  <!-- Star field -->
  <rect width="860" height="280" fill="url(#stars)" opacity="0.3"/>
  
  <!-- Twinkling stars (animated) -->
  <g id="twinkling-stars">
    <circle cx="50" cy="50" r="2" fill="#00d4ff"><animate attributeName="opacity" values="0;1;0" dur="2s" repeatCount="indefinite"/></circle>
    <circle cx="150" cy="80" r="1" fill="#39ff14"><animate attributeName="opacity" values="0;1;0" dur="1.5s" repeatCount="indefinite" begin="0.5s"/></circle>
    <circle cx="250" cy="30" r="1.5" fill="#bc13fe"><animate attributeName="opacity" values="0;1;0" dur="2.5s" repeatCount="indefinite" begin="1s"/></circle>
    <circle cx="350" cy="100" r="1" fill="#39ff14"><animate attributeName="opacity" values="0;1;0" dur="1.8s" repeatCount="indefinite" begin="0.3s"/></circle>
    <circle cx="450" cy="60" r="2" fill="#00d4ff"><animate attributeName="opacity" values="0;1;0" dur="2.2s" repeatCount="indefinite" begin="0.7s"/></circle>
    <circle cx="550" cy="120" r="1" fill="#bc13fe"><animate attributeName="opacity" values="0;1;0" dur="1.6s" repeatCount="indefinite" begin="1.2s"/></circle>
    <circle cx="650" cy="40" r="1.5" fill="#39ff14"><animate attributeName="opacity" values="0;1;0" dur="2s" repeatCount="indefinite" begin="0.1s"/></circle>
    <circle cx="750" cy="90" r="1" fill="#00d4ff"><animate attributeName="opacity" values="0;1;0" dur="1.7s" repeatCount="indefinite" begin="0.9s"/></circle>
    <circle cx="820" cy="150" r="2" fill="#bc13fe"><animate attributeName="opacity" values="0;1;0" dur="2.3s" repeatCount="indefinite" begin="0.4s"/></circle>
  </g>
  
  <!-- Matrix code rain effect -->
  <g id="matrix-rain" opacity="0.2">
    <text x="40" y="70" font-family="JetBrains Mono" font-size="10" fill="#39ff14">0</text>
    <text x="60" y="90" font-family="JetBrains Mono" font-size="10" fill="#00d4ff">1</text>
    <text x="85" y="60" font-family="JetBrains Mono" font-size="10" fill="#39ff14">0</text>
    <text x="110" y="110" font-family="JetBrains Mono" font-size="10" fill="#bc13fe">1</text>
    <text x="135" y="50" font-family="JetBrains Mono" font-size="10" fill="#39ff14">0</text>
    <text x="480" y="80" font-family="JetBrains Mono" font-size="10" fill="#00d4ff">1</text>
    <text x="510" y="100" font-family="JetBrains Mono" font-size="10" fill="#39ff14">0</text>
    <text x="540" y="60" font-family="JetBrains Mono" font-size="10" fill="#bc13fe">1</text>
    <text x="560" y="120" font-family="JetBrains Mono" font-size="10" fill="#39ff14">0</text>
    <text x="680" y="90" font-family="JetBrains Mono" font-size="10" fill="#00d4ff">1</text>
    <text x="710" y="130" font-family="JetBrains Mono" font-size="10" fill="#39ff14">0</text>
    <text x="740" y="50" font-family="JetBrains Mono" font-size="10" fill="#bc13fe">1</text>
  </g>
  
  <!-- Neural network nodes -->
  <g id="neural-network" opacity="0.4">
    <!-- Connections -->
    <line x1="700" y1="180" x2="720" y2="200" stroke="#00d4ff" stroke-width="1"><animate attributeName="opacity" values="0.2;0.8;0.2" dur="2s" repeatCount="indefinite"/></line>
    <line x1="720" y1="200" x2="750" y2="190" stroke="#39ff14" stroke-width="1"><animate attributeName="opacity" values="0.2;0.8;0.2" dur="2.5s" repeatCount="indefinite" begin="0.3s"/></line>
    <line x1="750" y1="190" x2="780" y2="210" stroke="#bc13fe" stroke-width="1"><animate attributeName="opacity" values="0.2;0.8;0.2" dur="2.2s" repeatCount="indefinite" begin="0.6s"/></line>
    
    <!-- Nodes -->
    <circle cx="700" cy="180" r="4" fill="#00d4ff"><animate attributeName="r" values="4;6;4" dur="2s" repeatCount="indefinite"/></circle>
    <circle cx="720" cy="200" r="4" fill="#39ff14"><animate attributeName="r" values="4;6;4" dur="2.5s" repeatCount="indefinite" begin="0.3s"/></circle>
    <circle cx="750" cy="190" r="4" fill="#bc13fe"><animate attributeName="r" values="4;6;4" dur="2.2s" repeatCount="indefinite" begin="0.6s"/></circle>
    <circle cx="780" cy="210" r="4" fill="#00d4ff"><animate attributeName="r" values="4;6;4" dur="2.4s" repeatCount="indefinite" begin="0.9s"/></circle>
  </g>
  
  <!-- Coding Illustration (terminal) -->
  <g id="coding-illustration" transform="translate(400, 120)">
    <!-- Terminal screen -->
    <rect x="-120" y="-40" width="240" height="80" rx="6" fill="#0d0d0f" stroke="url(#neonGradient)" stroke-width="1"/>
    <rect x="-115" y="-35" width="230" height="70" fill="#0a0a12"/>
    
    <!-- Terminal prompt -->
    <text x="-110" y="-15" font-family="JetBrains Mono" font-size="8" fill="#39ff14">supernovaprime@dev:</text>
    <text x="-110" y="0" font-family="JetBrains Mono" font-size="8" fill="#00d4ff">~</text>
    <text x="-105" y="0" font-family="JetBrains Mono" font-size="8" fill="#39ff14">$</text>
    
    <!-- Animated typing text -->
    <text x="-100" y="15" font-family="JetBrains Mono" font-size="8" fill="#bc13fe">Building the future..</text>
    
    <!-- Terminal cursor -->
    <line x="50" y1="15" x2="52" y2="15" stroke="#39ff14" stroke-width="1">
      <animate attributeName="opacity" values="1;0;1" dur="0.8s" repeatCount="indefinite"/>
    </line>
  </g>
  
  <!-- Profile info overlay -->
  <text x="430" y="250" text-anchor="middle" font-family="JetBrains Mono" font-size="24" font-weight="bold" fill="url(#neonGradient)">supernovaprime</text>
  <text x="430" y="270" text-anchor="middle" font-family="JetBrains Mono" font-size="12" fill="#888899">Software Engineer · Velvron Labs · Accra, Ghana 🇬🇭</text>
  
  <!-- Live status indicator -->
  <circle cx="780" cy="30" r="5" fill="#39ff14">
    <animate attributeName="opacity" values="1;0.4;1" dur="1.5s" repeatCount="indefinite"/>
  </circle>
  <text x="790" y="34" font-family="JetBrains Mono" font-size="10" fill="#39ff14">ONLINE</text>
</svg>

</div>

---

## 👾 About Me

```typescript
const supernovaprime = {
  location:   "Accra, Ghana 🇬🇭",
  role:       "Software Engineer · Velvron Labs",
  focus:      ["Full-Stack Development", "TypeScript", "React/Next.js", "System Architecture"],
  email:      "ebenezerayimful@gmail.com",
  portfolio:  "supernovaprimeportfolio.vercel.app",
  available:  true,
};
```

---

## 🛠 Tech Stack

**Core Languages & Frameworks**

![TypeScript](https://img.shields.io/badge/TypeScript-0a0a12?style=for-the-badge&logo=typescript&logoColor=00d4ff)
![React](https://img.shields.io/badge/React-0a0a12?style=for-the-badge&logo=react&logoColor=00d4ff)
![Next.js](https://img.shields.io/badge/Next.js-0a0a12?style=for-the-badge&logo=nextdotjs&logoColor=39ff14)
![Node.js](https://img.shields.io/badge/Node.js-0a0a12?style=for-the-badge&logo=nodedotjs&logoColor=39ff14)
![Python](https://img.shields.io/badge/Python-0a0a12?style=for-the-badge&logo=python&logoColor=bc13fe)

**Tools & Platforms**

![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-0a0a12?style=for-the-badge&logo=tailwindcss&logoColor=00d4ff)
![Prisma](https://img.shields.io/badge/Prisma-0a0a12?style=for-the-badge&logo=prisma&logoColor=39ff14)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0a0a12?style=for-the-badge&logo=postgresql&logoColor=bc13fe)
![GraphQL](https://img.shields.io/badge/GraphQL-0a0a12?style=for-the-badge&logo=graphql&logoColor=00d4ff)
![tRPC](https://img.shields.io/badge/tRPC-0a0a12?style=for-the-badge&logo=trpc&logoColor=39ff14)

**Infrastructure & DevOps**

![Docker](https://img.shields.io/badge/Docker-0a0a12?style=for-the-badge&logo=docker&logoColor=00d4ff)
![Vercel](https://img.shields.io/badge/Vercel-0a0a12?style=for-the-badge&logo=vercel&logoColor=39ff14)
![AWS](https://img.shields.io/badge/AWS-0a0a12?style=for-the-badge&logo=amazonwebservices&logoColor=bc13fe)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-0a0a12?style=for-the-badge&logo=githubactions&logoColor=00d4ff)

**Skills Proficiency (Animated)**

<div align="center">

<svg width="860" height="240" viewBox="0 0 860 240" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="neonSkill" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#00d4ff"/>
      <stop offset="33%" style="stop-color:#39ff14"/>
      <stop offset="66%" style="stop-color:#bc13fe"/>
      <stop offset="100%" style="stop-color:#00d4ff"/>
    </linearGradient>
  </defs>
  
  <!-- Background -->
  <rect width="860" height="240" rx="14" fill="#0a0a12" stroke="#2a2a3a" stroke-width="1"/>
  
  <!-- Header -->
  <text x="430" y="35" text-anchor="middle" font-family="JetBrains Mono" font-size="14" fill="#00d4ff">🔧 SKILL PROFICIENCY MATRIX</text>
  <line x1="30" y1="45" x2="830" y2="45" stroke="#2a2a3a" stroke-width="1"/>
  
  <!-- Skill bars -->
  <text x="40" y="75" font-family="JetBrains Mono" font-size="12" fill="#888899">React / Next.js 95%</text>
  <rect x="180" y="67" width="240" height="14" rx="7" fill="#1a1a2e"/>
  <rect x="180" y="67" width="0" height="14" rx="7" fill="url(#neonSkill)">
    <animate attributeName="width" from="0" to="228" dur="1.5s" fill="freeze" calcMode="spline" keySplines="0.4 0 0.2 1"/>
  </rect>
  
  <text x="40" y="105" font-family="JetBrains Mono" font-size="12" fill="#888899">TypeScript 90%</text>
  <rect x="180" y="97" width="240" height="14" rx="7" fill="#1a1a2e"/>
  <rect x="180" y="97" width="0" height="14" rx="7" fill="url(#neonSkill)">
    <animate attributeName="width" from="0" to="216" dur="1.5s" fill="freeze" begin="0.1s" calcMode="spline" keySplines="0.4 0 0.2 1"/>
  </rect>
  
  <text x="40" y="135" font-family="JetBrains Mono" font-size="12" fill="#888899">Node.js 95%</text>
  <rect x="180" y="127" width="240" height="14" rx="7" fill="#1a1a2e"/>
  <rect x="180" y="127" width="0" height="14" rx="7" fill="url(#neonSkill)">
    <animate attributeName="width" from="0" to="228" dur="1.5s" fill="freeze" begin="0.2s" calcMode="spline" keySplines="0.4 0 0.2 1"/>
  </rect>
  
  <text x="40" y="165" font-family="JetBrains Mono" font-size="12" fill="#888899">PostgreSQL 90%</text>
  <rect x="180" y="157" width="240" height="14" rx="7" fill="#1a1a2e"/>
  <rect x="180" y="157" width="0" height="14" rx="7" fill="url(#neonSkill)">
    <animate attributeName="width" from="0" to="216" dur="1.5s" fill="freeze" begin="0.3s" calcMode="spline" keySplines="0.4 0 0.2 1"/>
  </rect>
  
  <text x="40" y="195" font-family="JetBrains Mono" font-size="12" fill="#888899">Tailwind CSS 90%</text>
  <rect x="180" y="187" width="240" height="14" rx="7" fill="#1a1a2e"/>
  <rect x="180" y="187" width="0" height="14" rx="7" fill="url(#neonSkill)">
    <animate attributeName="width" from="0" to="216" dur="1.5s" fill="freeze" begin="0.4s" calcMode="spline" keySplines="0.4 0 0.2 1"/>
  </rect>
  
  <text x="400" y="75" font-family="JetBrains Mono" font-size="12" fill="#888899">Python 85%</text>
  <rect x="540" y="67" width="240" height="14" rx="7" fill="#1a1a2e"/>
  <rect x="540" y="67" width="0" height="14" rx="7" fill="url(#neonSkill)">
    <animate attributeName="width" from="0" to="204" dur="1.5s" fill="freeze" begin="0.5s" calcMode="spline" keySplines="0.4 0 0.2 1"/>
  </rect>
  
  <text x="400" y="105" font-family="JetBrains Mono" font-size="12" fill="#888899">GraphQL 80%</text>
  <rect x="540" y="97" width="240" height="14" rx="7" fill="#1a1a2e"/>
  <rect x="540" y="97" width="0" height="14" rx="7" fill="url(#neonSkill)">
    <animate attributeName="width" from="0" to="192" dur="1.5s" fill="freeze" begin="0.6s" calcMode="spline" keySplines="0.4 0 0.2 1"/>
  </rect>
  
  <text x="400" y="135" font-family="JetBrains Mono" font-size="12" fill="#888899">AWS 85%</text>
  <rect x="540" y="127" width="240" height="14" rx="7" fill="#1a1a2e"/>
  <rect x="540" y="127" width="0" height="14" rx="7" fill="url(#neonSkill)">
    <animate attributeName="width" from="0" to="204" dur="1.5s" fill="freeze" begin="0.7s" calcMode="spline" keySplines="0.4 0 0.2 1"/>
  </rect>
  
  <text x="400" y="165" font-family="JetBrains Mono" font-size="12" fill="#888899">Docker 85%</text>
  <rect x="540" y="157" width="240" height="14" rx="7" fill="#1a1a2e"/>
  <rect x="540" y="157" width="0" height="14" rx="7" fill="url(#neonSkill)">
    <animate attributeName="width" from="0" to="204" dur="1.5s" fill="freeze" begin="0.8s" calcMode="spline" keySplines="0.4 0 0.2 1"/>
  </rect>
</svg>

</div>

---

## 📊 GitHub Analytics

<div align="center">

<svg width="860" height="300" viewBox="0 0 860 300" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="neonGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#00d4ff"/>
      <stop offset="33%" style="stop-color:#39ff14"/>
      <stop offset="66%" style="stop-color:#bc13fe"/>
      <stop offset="100%" style="stop-color:#00d4ff"/>
    </linearGradient>
  </defs>
  
  <!-- Background -->
  <rect width="860" height="300" rx="14" fill="#0a0a12" stroke="#2a2a3a" stroke-width="1"/>
  
  <!-- Header -->
  <text x="430" y="35" text-anchor="middle" font-family="JetBrains Mono" font-size="14" fill="#00d4ff">⚡ LIVE SYSTEM TELEMETRY</text>
  
  <!-- Stat cards -->
  <rect x="30" y="50" width="0" height="80" rx="8" fill="#1a1a2e">
    <animate attributeName="width" from="0" to="160" dur="1.5s" fill="freeze" calcMode="spline" keySplines="0.4 0 0.2 1"/>
  </rect>
  <text x="110" y="95" text-anchor="middle" font-family="JetBrains Mono" font-size="28" font-weight="bold" fill="#00d4ff">9</text>
  <text x="110" y="118" text-anchor="middle" font-family="JetBrains Mono" font-size="11" fill="#888899">REPOS</text>
  
  <rect x="210" y="50" width="0" height="80" rx="8" fill="#1a1a2e">
    <animate attributeName="width" from="0" to="120" dur="1.5s" fill="freeze" begin="0.1s" calcMode="spline" keySplines="0.4 0 0.2 1"/>
  </rect>
  <text x="270" y="95" text-anchor="middle" font-family="JetBrains Mono" font-size="28" font-weight="bold" fill="#39ff14">0</text>
  <text x="270" y="118" text-anchor="middle" font-family="JetBrains Mono" font-size="11" fill="#888899">STARS</text>
  
  <rect x="390" y="50" width="0" height="80" rx="8" fill="#1a1a2e">
    <animate attributeName="width" from="0" to="140" dur="1.5s" fill="freeze" begin="0.2s" calcMode="spline" keySplines="0.4 0 0.2 1"/>
  </rect>
  <text x="460" y="95" text-anchor="middle" font-family="JetBrains Mono" font-size="28" font-weight="bold" fill="#bc13fe">0</text>
  <text x="460" y="118" text-anchor="middle" font-family="JetBrains Mono" font-size="11" fill="#888899">COMMITS</text>
  
  <rect x="570" y="50" width="0" height="80" rx="8" fill="#1a1a2e">
    <animate attributeName="width" from="0" to="140" dur="1.5s" fill="freeze" begin="0.3s" calcMode="spline" keySplines="0.4 0 0.2 1"/>
  </rect>
  <text x="640" y="95" text-anchor="middle" font-family="JetBrains Mono" font-size="28" font-weight="bold" fill="#00d4ff">1</text>
  <text x="640" y="118" text-anchor="middle" font-family="JetBrains Mono" font-size="11" fill="#888899">FOLLOWERS</text>
  
  <rect x="750" y="50" width="0" height="80" rx="8" fill="#1a1a2e">
    <animate attributeName="width" from="0" to="60" dur="1.5s" fill="freeze" begin="0.4s" calcMode="spline" keySplines="0.4 0 0.2 1"/>
  </rect>
  <text x="780" y="95" text-anchor="middle" font-family="JetBrains Mono" font-size="28" font-weight="bold" fill="#ff6b35">0</text>
  <text x="780" y="118" text-anchor="middle" font-family="JetBrains Mono" font-size="11" fill="#888899">STREAK</text>
  
  <!-- Language bars -->
  <text x="40" y="165" font-family="JetBrains Mono" font-size="11" fill="#888899">TYPESCRIPT</text>
  <rect x="120" y="157" width="0" height="16" rx="4" fill="url(#neonGrad)">
    <animate attributeName="width" from="0" to="200" dur="1.5s" fill="freeze" begin="0.5s" calcMode="spline" keySplines="0.4 0 0.2 1"/>
  </rect>
  
  <text x="40" y="195" font-family="JetBrains Mono" font-size="11" fill="#888899">JAVASCRIPT</text>
  <rect x="120" y="187" width="0" height="16" rx="4" fill="url(#neonGrad)">
    <animate attributeName="width" from="0" to="160" dur="1.5s" fill="freeze" begin="0.6s" calcMode="spline" keySplines="0.4 0 0.2 1"/>
  </rect>
  
  <text x="40" y="225" font-family="JetBrains Mono" font-size="11" fill="#888899">PYTHON</text>
  <rect x="120" y="217" width="0" height="16" rx="4" fill="url(#neonGrad)">
    <animate attributeName="width" from="0" to="100" dur="1.5s" fill="freeze" begin="0.7s" calcMode="spline" keySplines="0.4 0 0.2 1"/>
  </rect>
  
  <!-- Activity heatmap -->
  <text x="40" y="265" font-family="JetBrains Mono" font-size="11" fill="#888899">ACTIVITY — 12 WEEKS</text>
  
  <!-- Animated heatmap cells -->
  <g id="heatmap">
    <rect x="140" y="252" width="12" height="12" rx="2" fill="#0a0a12"><animate attributeName="fill" values="#0a0a12;#0e4429;#006d32;#26a641;#39d353" dur="0.3s" fill="freeze" begin="0.8s"/></rect>
    <rect x="156" y="252" width="12" height="12" rx="2" fill="#0a0a12"><animate attributeName="fill" values="#0a0a12;#006d32;#26a641" dur="0.3s" fill="freeze" begin="0.82s"/></rect>
    <rect x="172" y="252" width="12" height="12" rx="2" fill="#0a0a12"><animate attributeName="fill" values="#0a0a12;#0e4429;#006d32;#26a641" dur="0.3s" fill="freeze" begin="0.84s"/></rect>
    <rect x="188" y="252" width="12" height="12" rx="2" fill="#0a0a12"><animate attributeName="fill" values="#0a0a12;#0e4429" dur="0.3s" fill="freeze" begin="0.86s"/></rect>
    <rect x="204" y="252" width="12" height="12" rx="2" fill="#0a0a12"><animate attributeName="fill" values="#0a0a12;#006d32;#26a641;#39d353" dur="0.3s" fill="freeze" begin="0.88s"/></rect>
    <rect x="220" y="252" width="12" height="12" rx="2" fill="#0a0a12"><animate attributeName="fill" values="#0a0a12;#0e4429" dur="0.3s" fill="freeze" begin="0.9s"/></rect>
    <rect x="236" y="252" width="12" height="12" rx="2" fill="#0a0a12"><animate attributeName="fill" values="#0a0a12;#0e4429;#006d32;#26a641" dur="0.3s" fill="freeze" begin="0.92s"/></rect>
    <rect x="140" y="268" width="12" height="12" rx="2" fill="#0a0a12"><animate attributeName="fill" values="#0a0a12;#006d32;#26a641" dur="0.3s" fill="freeze" begin="0.94s"/></rect>
    <rect x="156" y="268" width="12" height="12" rx="2" fill="#0a0a12"><animate attributeName="fill" values="#0a0a12;#0e4429;#006d32;#26a641;#39d353" dur="0.3s" fill="freeze" begin="0.96s"/></rect>
    <rect x="172" y="268" width="12" height="12" rx="2" fill="#0a0a12"><animate attributeName="fill" values="#0a0a12;#0e4429" dur="0.3s" fill="freeze" begin="0.98s"/></rect>
    <rect x="188" y="268" width="12" height="12" rx="2" fill="#0a0a12"><animate attributeName="fill" values="#0a0a12;#0e4429;#006d32;#26a641" dur="0.3s" fill="freeze" begin="1.0s"/></rect>
    <rect x="204" y="268" width="12" height="12" rx="2" fill="#0a0a12"><animate attributeName="fill" values="#0a0a12;#006d32" dur="0.3s" fill="freeze" begin="1.02s"/></rect>
    <rect x="220" y="268" width="12" height="12" rx="2" fill="#0a0a12"><animate attributeName="fill" values="#0a0a12;#0e4429;#006d32;#26a641;#39d353" dur="0.3s" fill="freeze" begin="1.04s"/></rect>
    <rect x="236" y="268" width="12" height="12" rx="2" fill="#0a0a12"><animate attributeName="fill" values="#0a0a12;#0e4429;#006d32" dur="0.3s" fill="freeze" begin="1.06s"/></rect>
  </g>
</svg>

</div>

---

## 🧱 Projects

**Public repositories showcasing full-stack development:**

| Repository | Description | Stack |
|---|---|---|
| [velvron-labs](https://github.com/supernovaprime/velvron-labs) | Company website/portfolio | TypeScript, React, Tailwind |
| [portfolio](https://github.com/supernovaprime/portfolio) | Personal portfolio | Next.js, TypeScript, Tailwind |
| [Backend](https://github.com/supernovaprime/Backend) | Backend API services | JavaScript, Node.js, Express |
| [Examination](https://github.com/supernovaprime/Examination) | 3D WebGL scene | JavaScript, Three.js, WebGL |

<details>
<summary>📦 More Projects (click to expand)</summary>

| Repository | Description | Updated |
|---|---|---|
| [hostelbookingmanagementsystem](https://github.com/supernovaprime/hostelbookingmanagementsystem) | Hostel booking system | Feb 2026 |
| [inventorytrackingsystem](https://github.com/supernovaprime/inventorytrackingsystem) | Inventory tracking | Jan 2026 |
| [premiumeventproject](https://github.com/supernovaprime/premiumeventproject) | Event management | Dec 2025 |

</details>

---

## 🤝 Connect

<p align="center">
  <a href="https://github.com/supernovaprime"><img src="https://img.shields.io/badge/GitHub-supernovaprime-0a0a12?style=for-the-badge&logo=github&logoColor=00d4ff" /></a>
  <a href="https://supernovaprimeportfolio.vercel.app"><img src="https://img.shields.io/badge/Portfolio-supernovaprimeportfolio.vercel.app-0a0a12?style=for-the-badge&logo=vercel&logoColor=39ff14" /></a>
  <a href="mailto:ebenezerayimful@gmail.com"><img src="https://img.shields.io/badge/Email-ebenezerayimful@gmail.com-0a0a12?style=for-the-badge&logo=gmail&logoColor=ff6b35" /></a>
</p>

---

<sub>🚀 Built with <a href="https://github.com/supernovaprime">supernovaprime</a> · <a href="https://velvronlabs.vercel.app">Velvron Labs</a> · Last updated: 2026-06-05</sub>