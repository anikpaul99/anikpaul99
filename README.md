<!--
╔══════════════════════════════════════════════════════════════╗
║           ANIK PAUL — GitHub Profile README                  ║
║           Theme: Deep Space / Cosmic Developer               ║
╚══════════════════════════════════════════════════════════════╝
-->

<div align="center">

<!-- ═══════════════════════════════════════════════════════ -->
<!--                  COSMIC HEADER SVG                      -->
<!-- ═══════════════════════════════════════════════════════ -->

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 280" width="100%">
  <defs>
    <!-- Deep space background gradient -->
    <radialGradient id="spaceGrad" cx="50%" cy="50%" r="75%">
      <stop offset="0%"   stop-color="#0a0e1a"/>
      <stop offset="60%"  stop-color="#050810"/>
      <stop offset="100%" stop-color="#000005"/>
    </radialGradient>

    <!-- Nebula glow — teal/blue -->
    <radialGradient id="nebula1" cx="20%" cy="40%" r="40%">
      <stop offset="0%"  stop-color="#0ff4c6" stop-opacity="0.08"/>
      <stop offset="100%" stop-color="#0ff4c6" stop-opacity="0"/>
    </radialGradient>

    <!-- Nebula glow — violet -->
    <radialGradient id="nebula2" cx="80%" cy="60%" r="45%">
      <stop offset="0%"  stop-color="#9b59ff" stop-opacity="0.1"/>
      <stop offset="100%" stop-color="#9b59ff" stop-opacity="0"/>
    </radialGradient>

    <!-- Blackhole gradient -->
    <radialGradient id="blackhole" cx="50%" cy="50%" r="50%">
      <stop offset="0%"   stop-color="#000000"/>
      <stop offset="55%"  stop-color="#0a0010"/>
      <stop offset="75%"  stop-color="#9b59ff" stop-opacity="0.25"/>
      <stop offset="90%"  stop-color="#0ff4c6" stop-opacity="0.12"/>
      <stop offset="100%" stop-color="transparent"/>
    </radialGradient>

    <!-- Glow filter for stars -->
    <filter id="starGlow" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="1.2" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>

    <!-- Strong glow for constellation nodes -->
    <filter id="nodeGlow">
      <feGaussianBlur stdDeviation="2.5" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>

    <!-- Text glow -->
    <filter id="textGlow">
      <feGaussianBlur stdDeviation="4" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>

    <!-- Accretion disk gradient -->
    <linearGradient id="accretion" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"   stop-color="#0ff4c6" stop-opacity="0"/>
      <stop offset="30%"  stop-color="#0ff4c6" stop-opacity="0.6"/>
      <stop offset="50%"  stop-color="#ffffff" stop-opacity="0.9"/>
      <stop offset="70%"  stop-color="#9b59ff" stop-opacity="0.6"/>
      <stop offset="100%" stop-color="#9b59ff" stop-opacity="0"/>
    </linearGradient>

    <linearGradient id="accretion2" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"   stop-color="#9b59ff" stop-opacity="0"/>
      <stop offset="35%"  stop-color="#9b59ff" stop-opacity="0.4"/>
      <stop offset="50%"  stop-color="#0ff4c6" stop-opacity="0.7"/>
      <stop offset="65%"  stop-color="#9b59ff" stop-opacity="0.4"/>
      <stop offset="100%" stop-color="#9b59ff" stop-opacity="0"/>
    </linearGradient>

  </defs>

  <!-- === BACKGROUND === -->
  <rect width="900" height="280" fill="url(#spaceGrad)"/>
  <rect width="900" height="280" fill="url(#nebula1)"/>
  <rect width="900" height="280" fill="url(#nebula2)"/>

  <!-- === STAR FIELD === -->
  <!-- Tiny distant stars -->
  <g fill="white" filter="url(#starGlow)">
    <circle cx="45"  cy="18"  r="0.7" opacity="0.5"/>
    <circle cx="120" cy="42"  r="0.5" opacity="0.4"/>
    <circle cx="200" cy="12"  r="0.8" opacity="0.6"/>
    <circle cx="310" cy="55"  r="0.5" opacity="0.5"/>
    <circle cx="430" cy="22"  r="0.6" opacity="0.7"/>
    <circle cx="560" cy="38"  r="0.5" opacity="0.4"/>
    <circle cx="650" cy="15"  r="0.8" opacity="0.6"/>
    <circle cx="780" cy="48"  r="0.6" opacity="0.5"/>
    <circle cx="860" cy="20"  r="0.5" opacity="0.7"/>
    <circle cx="75"  cy="80"  r="0.6" opacity="0.5"/>
    <circle cx="160" cy="95"  r="0.5" opacity="0.3"/>
    <circle cx="250" cy="72"  r="0.8" opacity="0.6"/>
    <circle cx="370" cy="88"  r="0.5" opacity="0.4"/>
    <circle cx="480" cy="65"  r="0.7" opacity="0.5"/>
    <circle cx="590" cy="90"  r="0.5" opacity="0.6"/>
    <circle cx="700" cy="70"  r="0.8" opacity="0.5"/>
    <circle cx="820" cy="85"  r="0.6" opacity="0.4"/>
    <circle cx="880" cy="75"  r="0.5" opacity="0.6"/>
    <circle cx="30"  cy="140" r="0.6" opacity="0.4"/>
    <circle cx="140" cy="155" r="0.5" opacity="0.5"/>
    <circle cx="220" cy="175" r="0.7" opacity="0.6"/>
    <circle cx="340" cy="160" r="0.5" opacity="0.4"/>
    <circle cx="840" cy="145" r="0.6" opacity="0.5"/>
    <circle cx="870" cy="170" r="0.5" opacity="0.4"/>
    <circle cx="50"  cy="220" r="0.6" opacity="0.5"/>
    <circle cx="160" cy="235" r="0.5" opacity="0.6"/>
    <circle cx="280" cy="245" r="0.7" opacity="0.4"/>
    <circle cx="400" cy="258" r="0.5" opacity="0.5"/>
    <circle cx="680" cy="248" r="0.6" opacity="0.6"/>
    <circle cx="800" cy="230" r="0.5" opacity="0.5"/>
    <circle cx="880" cy="255" r="0.6" opacity="0.4"/>
    <!-- brighter accent stars -->
    <circle cx="90"  cy="32"  r="1.2" opacity="0.8"/>
    <circle cx="490" cy="50"  r="1.0" opacity="0.7"/>
    <circle cx="730" cy="28"  r="1.3" opacity="0.9"/>
    <circle cx="170" cy="200" r="1.1" opacity="0.7"/>
    <circle cx="810" cy="195" r="1.2" opacity="0.8"/>
  </g>

  <!-- === CONSTELLATION — Orion-like (left cluster) === -->
  <!-- Lines first (below dots) -->
  <g stroke="#0ff4c6" stroke-width="0.6" opacity="0.35">
    <line x1="78"  y1="118" x2="95"  y2="140"/>
    <line x1="95"  y1="140" x2="115" y2="130"/>
    <line x1="115" y1="130" x2="130" y2="155"/>
    <line x1="95"  y1="140" x2="80"  y2="162"/>
    <line x1="78"  y1="118" x2="62"  y2="105"/>
    <line x1="115" y1="130" x2="125" y2="110"/>
  </g>
  <!-- Nodes -->
  <g fill="#0ff4c6" filter="url(#nodeGlow)">
    <circle cx="78"  cy="118" r="1.8" opacity="0.9"/>
    <circle cx="95"  cy="140" r="2.2" opacity="1.0"/>
    <circle cx="115" cy="130" r="1.6" opacity="0.8"/>
    <circle cx="130" cy="155" r="1.4" opacity="0.7"/>
    <circle cx="80"  cy="162" r="1.4" opacity="0.7"/>
    <circle cx="62"  cy="105" r="1.6" opacity="0.8"/>
    <circle cx="125" cy="110" r="1.8" opacity="0.9"/>
  </g>

  <!-- === CONSTELLATION — Cassiopeia-like (top right) === -->
  <g stroke="#9b59ff" stroke-width="0.6" opacity="0.30">
    <line x1="720" y1="40"  x2="745" y2="58"/>
    <line x1="745" y1="58"  x2="768" y2="44"/>
    <line x1="768" y1="44"  x2="792" y2="62"/>
    <line x1="792" y1="62"  x2="815" y2="46"/>
  </g>
  <g fill="#9b59ff" filter="url(#nodeGlow)">
    <circle cx="720" cy="40"  r="1.6" opacity="0.9"/>
    <circle cx="745" cy="58"  r="2.0" opacity="1.0"/>
    <circle cx="768" cy="44"  r="1.8" opacity="0.9"/>
    <circle cx="792" cy="62"  r="2.0" opacity="1.0"/>
    <circle cx="815" cy="46"  r="1.6" opacity="0.9"/>
  </g>

  <!-- === CONSTELLATION — small triangle (bottom right) === -->
  <g stroke="#0ff4c6" stroke-width="0.5" opacity="0.25">
    <line x1="780" y1="210" x2="810" y2="235"/>
    <line x1="810" y1="235" x2="755" y2="240"/>
    <line x1="755" y1="240" x2="780" y2="210"/>
  </g>
  <g fill="#0ff4c6" filter="url(#nodeGlow)" opacity="0.7">
    <circle cx="780" cy="210" r="1.5"/>
    <circle cx="810" cy="235" r="1.5"/>
    <circle cx="755" cy="240" r="1.5"/>
  </g>

  <!-- === BLACK HOLE (right-center) === -->
  <!-- Outer accretion glow rings -->
  <ellipse cx="760" cy="162" rx="68" ry="14" fill="none" stroke="url(#accretion)"  stroke-width="3" opacity="0.6"/>
  <ellipse cx="760" cy="162" rx="55" ry="10" fill="none" stroke="url(#accretion2)" stroke-width="2" opacity="0.5"/>
  <ellipse cx="760" cy="162" rx="44" ry="7"  fill="none" stroke="url(#accretion)"  stroke-width="1.5" opacity="0.4"/>
  <!-- Black hole core shadow -->
  <ellipse cx="760" cy="162" rx="36" ry="36" fill="url(#blackhole)"/>
  <!-- True event horizon -->
  <circle  cx="760" cy="162" r="22" fill="#000000"/>
  <!-- Subtle inner rim -->
  <circle  cx="760" cy="162" r="22" fill="none" stroke="#9b59ff" stroke-width="1" opacity="0.3"/>

  <!-- === MAIN TEXT === -->
  <!-- Name — large, elegant -->

<text
x="450" y="118"
text-anchor="middle"
font-family="'Palatino Linotype', Palatino, Georgia, serif"
font-size="52"
font-weight="400"
letter-spacing="6"
fill="white"
filter="url(#textGlow)"
opacity="0.95"

> ANIK PAUL</text>

  <!-- Thin divider line -->
  <line x1="260" y1="132" x2="640" y2="132" stroke="white" stroke-width="0.4" opacity="0.25"/>

  <!-- Subtitle — spaced, lighter -->

<text
x="450" y="157"
text-anchor="middle"
font-family="'Courier New', Courier, monospace"
font-size="12"
letter-spacing="4"
fill="#0ff4c6"
opacity="0.85"

> FRONT-END DEVELOPER · REACT · NEXT.JS</text>

  <!-- Tagline / philosophy -->

<text
x="450" y="195"
text-anchor="middle"
font-family="'Palatino Linotype', Palatino, Georgia, serif"
font-size="14"
font-style="italic"
letter-spacing="1"
fill="white"
opacity="0.45"

> crafting interfaces that feel like they belong to the future</text>

  <!-- Bottom micro-text -->

<text
x="450" y="255"
text-anchor="middle"
font-family="'Courier New', Courier, monospace"
font-size="10"
letter-spacing="3"
fill="#9b59ff"
opacity="0.5"

> // exploring the universe, one component at a time</text>

</svg>

<!-- ═══════════════════════════════════════════════════════ -->
<!--              PROFILE VIEWS COUNTER                     -->
<!-- ═══════════════════════════════════════════════════════ -->

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=anikpaul99&style=flat-square&color=9b59ff&label=EXPLORERS+WHO+VISITED)

</div>

---

<!-- ═══════════════════════════════════════════════════════ -->
<!--                   ABOUT ME SECTION                     -->
<!-- ═══════════════════════════════════════════════════════ -->

<br/>

```
  ┌─────────────────────────────────────────────────────────────┐
  │  > whoami                                                    │
  │                                                             │
  │    A front-end developer who believes that great UI is       │
  │    not decoration — it's communication. I build with         │
  │    React & Next.js, write to teach, and stay curious.        │
  │                                                             │
  │  > current_mission                                           │
  │    Building The Wild Oasis (Customer)                        │
  │    Mastering Next.js · Exploring Node.js                     │
  │                                                             │
  │  > location                                                  │
  │    Somewhere between a blank <div> and a finished product    │
  └─────────────────────────────────────────────────────────────┘
```

<br/>

<!-- ═══════════════════════════════════════════════════════ -->
<!--              THE WEEKLY COMMIT — NEWSLETTER            -->
<!-- ═══════════════════════════════════════════════════════ -->

<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 860 58" width="95%">
  <defs>
    <linearGradient id="headerLine" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"   stop-color="#0ff4c6" stop-opacity="0"/>
      <stop offset="20%"  stop-color="#0ff4c6" stop-opacity="0.8"/>
      <stop offset="80%"  stop-color="#9b59ff" stop-opacity="0.8"/>
      <stop offset="100%" stop-color="#9b59ff" stop-opacity="0"/>
    </linearGradient>
  </defs>
  <rect width="860" height="58" fill="#050810" rx="8"/>
  <rect x="0" y="0"   width="860" height="1"  fill="url(#headerLine)"/>
  <rect x="0" y="57"  width="860" height="1"  fill="url(#headerLine)"/>
  <text x="430" y="24" text-anchor="middle" font-family="'Courier New', monospace" font-size="10" letter-spacing="5" fill="#0ff4c6" opacity="0.7">NEWSLETTER</text>
  <text x="430" y="45" text-anchor="middle" font-family="'Palatino Linotype', Palatino, Georgia, serif" font-size="19" letter-spacing="3" fill="white" opacity="0.95">The Weekly Commit</text>
</svg>

<br/><br/>

**Every week, I break down JavaScript, React, and web development — distilled, practical, no noise.**
<br/>
_Deep dives that actually move your skills forward._

<br/>

[![Subscribe to The Weekly Commit](https://img.shields.io/badge/Subscribe_on_LinkedIn-%230A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/build-relation/newsletter-follow?entityUrn=7353997486119620608)

</div>

<br/>

<!-- Latest Articles -->

### 📡 &nbsp;Latest Transmissions from The Weekly Commit

| #     | Article                                                                                                                                                   | Topic              |
| ----- | --------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------ |
| `#30` | [**MVC Architecture — A Complete Guide**](https://www.linkedin.com/pulse/weekly-commit-30-js28-mvc-architecture-complete-guide-anik-paul-klljc)           | JS Design Patterns |
| `#29` | [**JavaScript Script Loading — defer & async**](https://www.linkedin.com/pulse/weekly-commit-29-js27-javascript-script-loading-defer-anik-paul-tedac)     | Core JavaScript    |
| `#28` | [**JavaScript Modules — Complete Modern Guide**](https://www.linkedin.com/pulse/weekly-commit-28-js26-javascript-modules-complete-modern-anik-paul-u5svc) | ES Modules         |

<br/>

---

<!-- ═══════════════════════════════════════════════════════ -->
<!--                  GITHUB STATS                          -->
<!-- ═══════════════════════════════════════════════════════ -->

<div align="center">

### 🌌 &nbsp;Activity in the Cosmos

<img height="170" src="https://github-readme-stats.vercel.app/api?username=anikpaul99&show_icons=true&theme=midnight-purple&hide_border=true&bg_color=050810&title_color=0ff4c6&icon_color=9b59ff&text_color=c0c8e8&ring_color=9b59ff" />
&nbsp;&nbsp;
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=anikpaul99&layout=compact&theme=midnight-purple&hide_border=true&bg_color=050810&title_color=0ff4c6&text_color=c0c8e8" />

<br/><br/>

<img width="70%" src="https://streak-stats.demolab.com?user=anikpaul99&theme=midnight-purple&hide_border=true&background=050810&ring=9b59ff&fire=0ff4c6&currStreakLabel=0ff4c6&sideLabels=9b59ff&dates=5a6480"/>

</div>

<br/>

---

<!-- ═══════════════════════════════════════════════════════ -->
<!--              TECH STACK                                -->
<!-- ═══════════════════════════════════════════════════════ -->

### ⚡ &nbsp;Technologies in my orbit

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000?style=flat-square&logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Redux](https://img.shields.io/badge/Redux-593D88?style=flat-square&logo=redux&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)
![React Query](https://img.shields.io/badge/React_Query-FF4154?style=flat-square&logo=react-query&logoColor=white)
![Styled Components](https://img.shields.io/badge/Styled_Components-DB7093?style=flat-square&logo=styled-components&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Webpack](https://img.shields.io/badge/Webpack-8DD6F9?style=flat-square&logo=webpack&logoColor=black)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![Sass](https://img.shields.io/badge/Sass-CC6699?style=flat-square&logo=sass&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)

</div>

<br/>

---

<!-- ═══════════════════════════════════════════════════════ -->
<!--              CODEWARS                                  -->
<!-- ═══════════════════════════════════════════════════════ -->

### 🏅 &nbsp;Codewars

<a href="https://www.codewars.com/users/anikpaul99" target="_blank">
  <img src="https://www.codewars.com/users/anikpaul99/badges/large" alt="Codewars badge"/>
</a>

<br/><br/>

---

<!-- ═══════════════════════════════════════════════════════ -->
<!--              CONNECT                                   -->
<!-- ═══════════════════════════════════════════════════════ -->

<div align="center">

### 🛸 &nbsp;Find me across the universe

[![Portfolio](https://img.shields.io/badge/Portfolio-paulanik.com-0ff4c6?style=for-the-badge&logoColor=white)](https://paulanik.com)
&nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/anik-paul-dev)
&nbsp;
[![Dev.to](https://img.shields.io/badge/Dev.to-0A0A0A?style=for-the-badge&logo=dev.to&logoColor=white)](https://dev.to/anikpaul)
&nbsp;
[![Twitter/X](https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/anikpauldev)
&nbsp;
[![Email](https://img.shields.io/badge/Email-hello@paulanik.com-9b59ff?style=for-the-badge&logoColor=white)](mailto:hello@paulanik.com)

<br/><br/>

<!-- CLOSING SVG — thin cosmic divider with quote -->
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 860 50" width="95%">
  <defs>
    <linearGradient id="divLine" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"   stop-color="#0ff4c6" stop-opacity="0"/>
      <stop offset="50%"  stop-color="#9b59ff" stop-opacity="0.5"/>
      <stop offset="100%" stop-color="#0ff4c6" stop-opacity="0"/>
    </linearGradient>
  </defs>
  <rect width="860" height="50" fill="transparent"/>
  <line x1="0" y1="1" x2="860" y2="1" stroke="url(#divLine)" stroke-width="1"/>
  <text x="430" y="33" text-anchor="middle"
    font-family="'Palatino Linotype', Palatino, Georgia, serif"
    font-size="13" font-style="italic"
    fill="white" opacity="0.35" letter-spacing="1">
    "The cosmos is within us. We are made of star-stuff." — Carl Sagan
  </text>
</svg>

</div>
