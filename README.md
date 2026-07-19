<div align="center">

<!-- ═══════════════════════════════════════════════════════════════════════════
     PREETHAM.SYS — A profile that behaves like a distributed system
     Custom animated SVG · Zero template · Built for GitHub rendering
     ═══════════════════════════════════════════════════════════════════════════ -->

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 920 480" width="920" role="img" aria-label="Preetham - Backend Engineer at SAP">
  <defs>
    <linearGradient id="sky" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#030712"/>
      <stop offset="40%" stop-color="#0a1628"/>
      <stop offset="100%" stop-color="#0c1929"/>
    </linearGradient>
    <linearGradient id="neon" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#0066ff"/>
      <stop offset="50%" stop-color="#00d4ff"/>
      <stop offset="100%" stop-color="#6366f1"/>
    </linearGradient>
    <linearGradient id="neonV" x1="0%" y1="100%" x2="0%" y2="0%">
      <stop offset="0%" stop-color="#00d4ff" stop-opacity="0"/>
      <stop offset="50%" stop-color="#00d4ff" stop-opacity="0.6"/>
      <stop offset="100%" stop-color="#00d4ff" stop-opacity="0"/>
    </linearGradient>
    <radialGradient id="orb" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#00d4ff" stop-opacity="0.35"/>
      <stop offset="100%" stop-color="#0066ff" stop-opacity="0"/>
    </radialGradient>
    <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="4" result="b"/>
      <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <filter id="softglow" x="-30%" y="-30%" width="160%" height="160%">
      <feGaussianBlur stdDeviation="8" result="b"/>
      <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <pattern id="grid" width="40" height="40" patternUnits="userSpaceOnUse">
      <path d="M 40 0 L 0 0 0 40" fill="none" stroke="#00d4ff" stroke-width="0.3" opacity="0.12"/>
    </pattern>
    <clipPath id="scanClip"><rect x="0" y="0" width="920" height="480"/></clipPath>
  </defs>

  <style>
    @keyframes pulse { 0%,100%{opacity:.35;r:5} 50%{opacity:1;r:7} }
    @keyframes pulse2 { 0%,100%{opacity:.25} 50%{opacity:.9} }
    @keyframes spin { to{transform:rotate(360deg)} }
    @keyframes scan { 0%{transform:translateY(-480px)} 100%{transform:translateY(480px)} }
    @keyframes float { 0%,100%{transform:translateY(0)} 50%{transform:translateY(-6px)} }
    @keyframes dash { to{stroke-dashoffset:0} }
    @keyframes blink { 0%,100%{opacity:1} 50%{opacity:0} }
    @keyframes shimmer { 0%{opacity:.4} 50%{opacity:1} 100%{opacity:.4} }
    .n1{animation:pulse 2.4s ease-in-out infinite}
    .n2{animation:pulse 2.4s ease-in-out .4s infinite}
    .n3{animation:pulse 2.4s ease-in-out .8s infinite}
    .n4{animation:pulse 2.4s ease-in-out 1.2s infinite}
    .n5{animation:pulse 2.4s ease-in-out 1.6s infinite}
    .n6{animation:pulse 2.4s ease-in-out 2s infinite}
    .ln{animation:pulse2 3s ease-in-out infinite}
    .ring{animation:spin 28s linear infinite;transform-origin:460px 200px}
    .scan{animation:scan 4s linear infinite}
    .float{animation:float 5s ease-in-out infinite}
    .blink{animation:blink 1.1s step-end infinite}
    .shim{animation:shimmer 2.5s ease-in-out infinite}
    .path1{stroke-dasharray:120;stroke-dashoffset:120;animation:dash 2s ease forwards}
    .path2{stroke-dasharray:100;stroke-dashoffset:100;animation:dash 2s .3s ease forwards}
    .path3{stroke-dasharray:90;stroke-dashoffset:90;animation:dash 2s .6s ease forwards}
    .path4{stroke-dasharray:110;stroke-dashoffset:110;animation:dash 2s .9s ease forwards}
    .path5{stroke-dasharray:80;stroke-dashoffset:80;animation:dash 2s 1.2s ease forwards}
  </style>

  <!-- Background -->
  <rect width="920" height="480" fill="url(#sky)"/>
  <rect width="920" height="480" fill="url(#grid)"/>
  <ellipse cx="460" cy="240" rx="320" ry="180" fill="url(#orb)"/>

  <!-- Orbit ring -->
  <g class="ring" opacity="0.25">
    <ellipse cx="460" cy="200" rx="280" ry="100" fill="none" stroke="url(#neon)" stroke-width="0.8" stroke-dasharray="8 12"/>
  </g>

  <!-- Distributed system topology -->
  <g filter="url(#softglow)">
    <line class="ln path1" x1="460" y1="200" x2="200" y2="120" stroke="#00d4ff" stroke-width="1.2" opacity="0.5"/>
    <line class="ln path2" x1="460" y1="200" x2="720" y2="100" stroke="#00d4ff" stroke-width="1.2" opacity="0.5"/>
    <line class="ln path3" x1="460" y1="200" x2="780" y2="260" stroke="#6366f1" stroke-width="1.2" opacity="0.5"/>
    <line class="ln path4" x1="460" y1="200" x2="140" y2="280" stroke="#6366f1" stroke-width="1.2" opacity="0.5"/>
    <line class="ln path5" x1="460" y1="200" x2="460" y2="360" stroke="#0066ff" stroke-width="1.2" opacity="0.5"/>
    <line class="ln" x1="200" y1="120" x2="720" y2="100" stroke="#00d4ff" stroke-width="0.6" opacity="0.2"/>
    <line class="ln" x1="140" y1="280" x2="780" y2="260" stroke="#6366f1" stroke-width="0.6" opacity="0.2"/>
  </g>

  <!-- Nodes -->
  <g filter="url(#glow)">
    <circle class="n1" cx="460" cy="200" r="6" fill="#00d4ff"/>
    <circle class="n2" cx="200" cy="120" r="5" fill="#00d4ff"/>
    <circle class="n3" cx="720" cy="100" r="5" fill="#6366f1"/>
    <circle class="n4" cx="780" cy="260" r="5" fill="#6366f1"/>
    <circle class="n5" cx="140" cy="280" r="5" fill="#0066ff"/>
    <circle class="n6" cx="460" cy="360" r="5" fill="#0066ff"/>
  </g>

  <!-- Node labels -->
  <text x="200" y="108" fill="#64748b" font-family="monospace" font-size="9" text-anchor="middle">JAVA</text>
  <text x="720" y="88" fill="#64748b" font-family="monospace" font-size="9" text-anchor="middle">GO</text>
  <text x="790" y="278" fill="#64748b" font-family="monospace" font-size="9" text-anchor="middle">K8S</text>
  <text x="130" y="298" fill="#64748b" font-family="monospace" font-size="9" text-anchor="middle">KAFKA</text>
  <text x="460" y="382" fill="#64748b" font-family="monospace" font-size="9" text-anchor="middle">SPRING</text>
  <text x="460" y="188" fill="#00d4ff" font-family="monospace" font-size="9" text-anchor="middle" opacity="0.8">CORE</text>

  <!-- Scanline -->
  <g clip-path="url(#scanClip)" opacity="0.06">
    <rect class="scan" x="0" y="0" width="920" height="60" fill="url(#neonV)"/>
  </g>

  <!-- Top bar -->
  <rect x="30" y="24" width="860" height="32" rx="8" fill="#0f172a" stroke="#1e293b" stroke-width="1"/>
  <circle cx="52" cy="40" r="5" fill="#ef4444" opacity="0.8"/>
  <circle cx="70" cy="40" r="5" fill="#eab308" opacity="0.8"/>
  <circle cx="88" cy="40" r="5" fill="#22c55e" opacity="0.8"/>
  <text x="460" y="44" fill="#64748b" font-family="monospace" font-size="11" text-anchor="middle">preetham.sys — distributed backend engineer</text>
  <circle class="blink" cx="848" cy="40" r="4" fill="#22c55e"/>

  <!-- Main title -->
  <g class="float">
    <text x="460" y="175" fill="url(#neon)" font-family="Georgia, serif" font-size="72" font-weight="700" text-anchor="middle" filter="url(#glow)">Preetham</text>
  </g>
  <text x="460" y="218" fill="#94a3b8" font-family="monospace" font-size="14" text-anchor="middle" letter-spacing="4">ASSOCIATE SOFTWARE DEVELOPER</text>
  <text x="460" y="242" fill="#00d4ff" font-family="monospace" font-size="13" text-anchor="middle" class="shim">@ SAP  ·  Bengaluru  ·  Backend · Cloud Native · Distributed Systems</text>

  <!-- Status bar -->
  <rect x="120" y="400" width="680" height="52" rx="12" fill="#0f172a" stroke="#1e3a5f" stroke-width="1" opacity="0.95"/>
  <text x="150" y="422" fill="#22c55e" font-family="monospace" font-size="11">● ONLINE</text>
  <text x="240" y="422" fill="#64748b" font-family="monospace" font-size="11">uptime</text>
  <text x="240" y="440" fill="#e2e8f0" font-family="monospace" font-size="11">building enterprise systems</text>
  <text x="430" y="422" fill="#64748b" font-family="monospace" font-size="11">focus</text>
  <text x="430" y="440" fill="#00d4ff" font-family="monospace" font-size="11">microservices · k8s · system design</text>
  <text x="680" y="422" fill="#64748b" font-family="monospace" font-size="11">status</text>
  <text x="680" y="440" fill="#a78bfa" font-family="monospace" font-size="11">open to collaborate</text>
</svg>

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=16&duration=3000&pause=1200&color=00D4FF&center=true&vCenter=true&width=900&lines=Architecting+resilient+backend+systems;Java+%E2%86%92+Go+%E2%86%92+Kubernetes+at+scale;Where+microservices+meet+machine+intelligence;I+design+systems+that+survive+traffic+spikes"/>

<br/><br/>

<a href="https://github.com/Preethamn15?tab=repositories"><img src="https://img.shields.io/badge/▸_Repositories-0a1628?style=for-the-badge&labelColor=00d4ff&color=0a1628"/></a>
&nbsp;
<a href="https://www.linkedin.com/in/preetham-n-672951284/"><img src="https://img.shields.io/badge/▸_LinkedIn-0a1628?style=for-the-badge&labelColor=0077B5&color=0a1628"/></a>
&nbsp;
<a href="mailto:preethamn2004@gmail.com"><img src="https://img.shields.io/badge/▸_Email-0a1628?style=for-the-badge&labelColor=EA4335&color=0a1628"/></a>
&nbsp;
<a href="#deployments"><img src="https://img.shields.io/badge/▸_Projects-0a1628?style=for-the-badge&labelColor=6366f1&color=0a1628"/></a>

</div>

<br/>

<!-- ═══ BOOT SEQUENCE — animated terminal SVG ═══ -->

<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 860 200" width="860">
  <defs>
    <linearGradient id="termBg" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%" stop-color="#0c1220"/>
      <stop offset="100%" stop-color="#070b14"/>
    </linearGradient>
  </defs>
  <style>
    @keyframes type1 { from{width:0} to{width:520px} }
    @keyframes type2 { from{width:0} to{width:380px} }
    @keyframes type3 { from{width:0} to{width:440px} }
    @keyframes type4 { from{width:0} to{width:400px} }
    @keyframes type5 { from{width:0} to{width:360px} }
    @keyframes cur { 0%,100%{opacity:1} 50%{opacity:0} }
    @keyframes fadeIn { from{opacity:0} to{opacity:1} }
    .t1{animation:type1 1.2s steps(40) forwards, fadeIn .1s}
    .t2{animation:type2 1s steps(30) 1.3s forwards, fadeIn .1s 1.3s both}
    .t3{animation:type3 1.1s steps(35) 2.4s forwards, fadeIn .1s 2.4s both}
    .t4{animation:type4 1s steps(32) 3.6s forwards, fadeIn .1s 3.6s both}
    .t5{animation:type5 .9s steps(28) 4.7s forwards, fadeIn .1s 4.7s both}
    .cur{animation:cur 1s step-end infinite}
  </style>
  <rect width="860" height="200" rx="14" fill="url(#termBg)" stroke="#1e3a5f" stroke-width="1.5"/>
  <rect x="0" y="0" width="860" height="36" rx="14" fill="#111827"/>
  <rect x="0" y="22" width="860" height="14" fill="#111827"/>
  <circle cx="24" cy="18" r="6" fill="#ef4444" opacity=".85"/>
  <circle cx="44" cy="18" r="6" fill="#eab308" opacity=".85"/>
  <circle cx="64" cy="18" r="6" fill="#22c55e" opacity=".85"/>
  <text x="430" y="22" fill="#475569" font-family="monospace" font-size="11" text-anchor="middle">boot — preetham.sys</text>
  <clipPath id="c1"><rect class="t1" x="32" y="52" height="16" width="0"/></clipPath>
  <clipPath id="c2"><rect class="t2" x="32" y="76" height="16" width="0"/></clipPath>
  <clipPath id="c3"><rect class="t3" x="32" y="100" height="16" width="0"/></clipPath>
  <clipPath id="c4"><rect class="t4" x="32" y="124" height="16" width="0"/></clipPath>
  <clipPath id="c5"><rect class="t5" x="32" y="148" height="16" width="0"/></clipPath>
  <text clip-path="url(#c1)" x="32" y="64" fill="#22c55e" font-family="monospace" font-size="12">$ kernel.load — Preetham v1.0 initialized</text>
  <text clip-path="url(#c2)" x="32" y="88" fill="#00d4ff" font-family="monospace" font-size="12">$ role.mount — Associate Software Developer @ SAP</text>
  <text clip-path="url(#c3)" x="32" y="112" fill="#a78bfa" font-family="monospace" font-size="12">$ stack.link — Java · Go · Kubernetes · Spring Boot</text>
  <text clip-path="url(#c4)" x="32" y="136" fill="#fbbf24" font-family="monospace" font-size="12">$ mission.set — Ship reliable distributed systems</text>
  <text clip-path="url(#c5)" x="32" y="160" fill="#94a3b8" font-family="monospace" font-size="12">$ status — READY · awaiting collaboration requests</text>
  <rect class="cur" x="400" y="148" width="8" height="14" fill="#00d4ff"/>
</svg>

</div>

<br/>

<!-- ═══ BENTO DESKTOP — OS-style windows ═══ -->

<table width="100%">
<tr valign="top">
<td width="33%">

<table width="100%">
<tr><td bgcolor="#111827">

&nbsp; 🟢 &nbsp; **`currently.sys`**

</td></tr>
<tr><td bgcolor="#0a1628">

<br/>

**Building enterprise software at SAP**

Designing cloud-native backends, REST microservices, and production-grade APIs on SAP BTP.

<br/>

<img src="https://img.shields.io/badge/SAP-Active_Deployment-0092D1?style=flat-square&logo=sap&logoColor=white&labelColor=0f172a"/>

<br/><br/>

</td></tr>
</table>

</td>
<td width="33%">

<table width="100%">
<tr><td bgcolor="#111827">

&nbsp; 🔵 &nbsp; **`learning.sys`**

</td></tr>
<tr><td bgcolor="#0a1628">

<br/>

```
Go             ████████░░  80%
K8s            ██████░░░░  60%
Sys Design     ███████░░░  70%
Distributed    ████████░░  75%
```

<br/>

</td></tr>
</table>

</td>
<td width="33%">

<table width="100%">
<tr><td bgcolor="#111827">

&nbsp; 🟣 &nbsp; **`interests.sys`**

</td></tr>
<tr><td bgcolor="#0a1628">

<br/>

Cloud Native Architecture

Event-Driven Systems

Performance Engineering

AI × Backend Integration

Open Source

<br/>

</td></tr>
</table>

</td>
</tr>
</table>

<br/>

<!-- ═══ Animated skill constellation SVG ═══ -->

<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 920 280" width="920">
  <defs>
    <linearGradient id="bar" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#0066ff"/>
      <stop offset="100%" stop-color="#00d4ff"/>
    </linearGradient>
  </defs>
  <style>
    @keyframes grow1{from{width:0}to{width:340px}}
    @keyframes grow2{from{width:0}to{width:300px}}
    @keyframes grow3{from{width:0}to{width:280px}}
    @keyframes grow4{from{width:0}to{width:260px}}
    @keyframes grow5{from{width:0}to{width:240px}}
    @keyframes grow6{from{width:0}to{width:220px}}
    .b1{animation:grow1 1.8s ease-out forwards}
    .b2{animation:grow2 1.8s .15s ease-out forwards}
    .b3{animation:grow3 1.8s .3s ease-out forwards}
    .b4{animation:grow4 1.8s .45s ease-out forwards}
    .b5{animation:grow5 1.8s .6s ease-out forwards}
    .b6{animation:grow6 1.8s .75s ease-out forwards}
  </style>
  <rect width="920" height="280" rx="16" fill="#070b14" stroke="#1e3a5f" stroke-width="1"/>
  <text x="460" y="36" fill="#00d4ff" font-family="monospace" font-size="13" text-anchor="middle" letter-spacing="6">TECH STACK · LIVE METRICS</text>
  <!-- Java -->
  <text x="80" y="78" fill="#94a3b8" font-family="monospace" font-size="11">JAVA</text>
  <rect x="160" y="66" width="400" height="16" rx="4" fill="#1e293b"/>
  <rect class="b1" x="160" y="66" height="16" rx="4" fill="url(#bar)" width="0"/>
  <text x="520" y="78" fill="#64748b" font-family="monospace" font-size="10">PRIMARY</text>
  <!-- Go -->
  <text x="80" y="108" fill="#94a3b8" font-family="monospace" font-size="11">GO</text>
  <rect x="160" y="96" width="400" height="16" rx="4" fill="#1e293b"/>
  <rect class="b2" x="160" y="96" height="16" rx="4" fill="url(#bar)" width="0"/>
  <text x="520" y="108" fill="#64748b" font-family="monospace" font-size="10">GROWING</text>
  <!-- Spring -->
  <text x="80" y="138" fill="#94a3b8" font-family="monospace" font-size="11">SPRING</text>
  <rect x="160" y="126" width="400" height="16" rx="4" fill="#1e293b"/>
  <rect class="b3" x="160" y="126" height="16" rx="4" fill="url(#bar)" width="0"/>
  <!-- K8s -->
  <text x="80" y="168" fill="#94a3b8" font-family="monospace" font-size="11">K8S</text>
  <rect x="160" y="156" width="400" height="16" rx="4" fill="#1e293b"/>
  <rect class="b4" x="160" y="156" height="16" rx="4" fill="url(#bar)" width="0"/>
  <!-- Kafka -->
  <text x="80" y="198" fill="#94a3b8" font-family="monospace" font-size="11">KAFKA</text>
  <rect x="160" y="186" width="400" height="16" rx="4" fill="#1e293b"/>
  <rect class="b5" x="160" y="186" height="16" rx="4" fill="url(#bar)" width="0"/>
  <!-- AI/ML -->
  <text x="80" y="228" fill="#94a3b8" font-family="monospace" font-size="11">AI/ML</text>
  <rect x="160" y="216" width="400" height="16" rx="4" fill="#1e293b"/>
  <rect class="b6" x="160" y="216" height="16" rx="4" fill="url(#bar)" width="0"/>
  <!-- Icons area -->
  <text x="620" y="78" fill="#475569" font-family="monospace" font-size="10">LANGUAGES</text>
  <text x="620" y="130" fill="#475569" font-family="monospace" font-size="10">INFRA</text>
  <text x="620" y="182" fill="#475569" font-family="monospace" font-size="10">DATA</text>
  <text x="620" y="234" fill="#475569" font-family="monospace" font-size="10">TOOLS</text>
</svg>

<br/>

<img src="https://skillicons.dev/icons?i=java,go,python,c,php,spring,maven,nodejs,docker,kubernetes,postgres,mysql,redis,linux,bash,git,github,vscode,idea,postman&theme=dark&perline=10"/>

</div>

<br/>

<!-- ═══ EXPERIENCE — deployed service card ═══ -->

<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 920 8" width="920">
  <line x1="0" y1="4" x2="920" y2="4" stroke="#1e3a5f" stroke-width="1"/>
  <circle cx="460" cy="4" r="3" fill="#00d4ff"/>
</svg>

**`EXPERIENCE · DEPLOYMENT LOG`**

</div>

<br/>

<table width="100%">
<tr>
<td width="8%" align="center" valign="top">

```
▲
┃
┃
●
┃
┃
○
```

</td>
<td width="92%">

<table width="100%">
<tr><td bgcolor="#111827">&nbsp; 🟢 &nbsp; **SAP** · Associate Software Developer &nbsp;·&nbsp; `PRODUCTION` &nbsp;·&nbsp; uptime: active</td></tr>
<tr><td bgcolor="#0a1628">

<br/>

| Achievement | Detail |
|:---|:---|
| **Scaled** | Backend microservices handling enterprise workloads via Spring Boot |
| **Architected** | REST APIs & cloud-native services on SAP BTP |
| **Containerized** | Docker → Kubernetes deployment pipelines |
| **Engineered** | Event-driven patterns with Kafka integration |
| **Collaborated** | Cross-team system design, code reviews, production reliability |

<br/>

<img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white&labelColor=0f172a"/>
<img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white&labelColor=0f172a"/>
<img src="https://img.shields.io/badge/SAP_BTP-0FAAFF?style=flat-square&logo=sap&logoColor=white&labelColor=0f172a"/>

<br/><br/>

</td></tr>
</table>

<br/>

<table width="100%">
<tr><td bgcolor="#111827">&nbsp; ⚪ &nbsp; **RV College of Engineering** · B.E. AI & Machine Learning</td></tr>
<tr><td bgcolor="#0a1628">

<br/>

Foundation in machine learning, computer vision, and intelligent systems — now channeled into production backend engineering and AI-integrated services.

<br/><br/>

</td></tr>
</table>

</td>
</tr>
</table>

<br/>

<!-- ═══ TECH RADAR — unique hex grid ═══ -->

<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 920 220" width="920">
  <style>
    @keyframes hexPulse { 0%,100%{opacity:.5} 50%{opacity:1} }
    .hp{animation:hexPulse 3s ease-in-out infinite}
    .hp2{animation:hexPulse 3s .5s ease-in-out infinite}
    .hp3{animation:hexPulse 3s 1s ease-in-out infinite}
  </style>
  <rect width="920" height="220" rx="16" fill="#070b14" stroke="#1e3a5f" stroke-width="1"/>
  <text x="460" y="32" fill="#00d4ff" font-family="monospace" font-size="13" text-anchor="middle" letter-spacing="5">TECH RADAR 2025</text>
  <!-- ADOPT -->
  <rect x="40" y="55" width="190" height="150" rx="10" fill="#0f172a" stroke="#22c55e" stroke-width="1" opacity="0.9"/>
  <text x="135" y="78" fill="#22c55e" font-family="monospace" font-size="11" text-anchor="middle">ADOPT</text>
  <text x="135" y="105" fill="#e2e8f0" font-family="monospace" font-size="10" text-anchor="middle">Java</text>
  <text x="135" y="122" fill="#e2e8f0" font-family="monospace" font-size="10" text-anchor="middle">Spring Boot</text>
  <text x="135" y="139" fill="#e2e8f0" font-family="monospace" font-size="10" text-anchor="middle">Docker</text>
  <text x="135" y="156" fill="#e2e8f0" font-family="monospace" font-size="10" text-anchor="middle">PostgreSQL</text>
  <circle class="hp" cx="135" cy="180" r="4" fill="#22c55e"/>
  <!-- TRIAL -->
  <rect x="250" y="55" width="190" height="150" rx="10" fill="#0f172a" stroke="#00d4ff" stroke-width="1" opacity="0.9"/>
  <text x="345" y="78" fill="#00d4ff" font-family="monospace" font-size="11" text-anchor="middle">TRIAL</text>
  <text x="345" y="105" fill="#e2e8f0" font-family="monospace" font-size="10" text-anchor="middle">Go</text>
  <text x="345" y="122" fill="#e2e8f0" font-family="monospace" font-size="10" text-anchor="middle">Kubernetes</text>
  <text x="345" y="139" fill="#e2e8f0" font-family="monospace" font-size="10" text-anchor="middle">Kafka</text>
  <text x="345" y="156" fill="#e2e8f0" font-family="monospace" font-size="10" text-anchor="middle">Redis</text>
  <circle class="hp2" cx="345" cy="180" r="4" fill="#00d4ff"/>
  <!-- ASSESS -->
  <rect x="460" y="55" width="190" height="150" rx="10" fill="#0f172a" stroke="#a78bfa" stroke-width="1" opacity="0.9"/>
  <text x="555" y="78" fill="#a78bfa" font-family="monospace" font-size="11" text-anchor="middle">ASSESS</text>
  <text x="555" y="105" fill="#e2e8f0" font-family="monospace" font-size="10" text-anchor="middle">gRPC</text>
  <text x="555" y="122" fill="#e2e8f0" font-family="monospace" font-size="10" text-anchor="middle">Service Mesh</text>
  <text x="555" y="139" fill="#e2e8f0" font-family="monospace" font-size="10" text-anchor="middle">Observability</text>
  <text x="555" y="156" fill="#e2e8f0" font-family="monospace" font-size="10" text-anchor="middle">eBPF</text>
  <circle class="hp3" cx="555" cy="180" r="4" fill="#a78bfa"/>
  <!-- HOLD -->
  <rect x="670" y="55" width="210" height="150" rx="10" fill="#0f172a" stroke="#475569" stroke-width="1" opacity="0.9"/>
  <text x="775" y="78" fill="#64748b" font-family="monospace" font-size="11" text-anchor="middle">HOLD</text>
  <text x="775" y="110" fill="#64748b" font-family="monospace" font-size="10" text-anchor="middle">Monoliths</text>
  <text x="775" y="130" fill="#64748b" font-family="monospace" font-size="10" text-anchor="middle">Manual deploys</text>
  <text x="775" y="150" fill="#64748b" font-family="monospace" font-size="10" text-anchor="middle">Untested paths</text>
</svg>

</div>

<br/>

<!-- ═══ PROJECTS — product deployment cards ═══ -->

<div align="center" id="deployments">

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 920 40" width="920">
  <text x="460" y="28" fill="#00d4ff" font-family="monospace" font-size="14" text-anchor="middle" letter-spacing="8">DEPLOYMENTS</text>
</svg>

</div>

<br/>

<table width="100%">
<tr valign="top">
<td width="50%">

<table width="96%">
<tr><td bgcolor="#111827">&nbsp; ⬡ &nbsp; **Smart AI Gym Trainer** &nbsp; `v1.0` &nbsp; <img src="https://img.shields.io/badge/live-22c55e?style=flat-square&labelColor=0f172a" height="16"/></td></tr>
<tr><td bgcolor="#0c1220">

<br/>

AI fitness platform — real-time pose tracking, posture correction, YOLO nutrition analysis.

<br/>

<img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white&labelColor=161b22"/>
<img src="https://img.shields.io/badge/YOLO-CV-00C853?style=flat-square&labelColor=161b22"/>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white&labelColor=161b22"/>

<br/><br/>

<a href="https://github.com/Preethamn15/Smart-AI-Gym-Trainer-With-RealTime-Exercise-Tracking-and-Nutrition-Assistant"><img src="https://img.shields.io/badge/▸_Launch_Repo-00d4ff?style=for-the-badge&labelColor=0a1628"/></a>

<br/><br/>

</td></tr>
</table>

</td>
<td width="50%">

<table width="96%">
<tr><td bgcolor="#111827">&nbsp; ⬡ &nbsp; **Autonomous Trading System** &nbsp; `v2.1` &nbsp; <img src="https://img.shields.io/badge/live-22c55e?style=flat-square&labelColor=0f172a" height="16"/></td></tr>
<tr><td bgcolor="#0c1220">

<br/>

Kafka-streamed trading engine with Random Forest models & SHAP explainability.

<br/>

<img src="https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white&labelColor=161b22"/>
<img src="https://img.shields.io/badge/SHAP-XAI-8B5CF6?style=flat-square&labelColor=161b22"/>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white&labelColor=161b22"/>

<br/><br/>

<a href="https://github.com/Preethamn15/Autonomous-Streaming-Trading-System-with-Explainable-AI"><img src="https://img.shields.io/badge/▸_Launch_Repo-00d4ff?style=for-the-badge&labelColor=0a1628"/></a>

<br/><br/>

</td></tr>
</table>

</td>
</tr>
<tr valign="top">
<td width="50%">

<table width="96%">
<tr><td bgcolor="#111827">&nbsp; ⬡ &nbsp; **EduFused AI Platform** &nbsp; `v1.2`</td></tr>
<tr><td bgcolor="#0c1220">

<br/>

Adaptive learning with NLP chatbot, personalized paths, and interactive quizzes.

<br/>

<img src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white&labelColor=161b22"/>
<img src="https://img.shields.io/badge/NLP-AI-F97316?style=flat-square&labelColor=161b22"/>

<br/><br/>

<a href="https://github.com/Preethamn15/EduFused-AI-Powered-Adaptive-Learning-Platform"><img src="https://img.shields.io/badge/▸_Launch_Repo-00d4ff?style=for-the-badge&labelColor=0a1628"/></a>

<br/><br/>

</td></tr>
</table>

</td>
<td width="50%">

<table width="96%">
<tr><td bgcolor="#111827">&nbsp; ⬡ &nbsp; **AI Hydroponic System** &nbsp; `v1.0` &nbsp; <img src="https://img.shields.io/badge/IoT-0066ff?style=flat-square&labelColor=0f172a" height="16"/></td></tr>
<tr><td bgcolor="#0c1220">

<br/>

ESP32 sensors + AI disease detection for automated smart agriculture.

<br/>

<img src="https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white&labelColor=161b22"/>
<img src="https://img.shields.io/badge/IoT-Edge-00d4ff?style=flat-square&labelColor=161b22"/>

<br/><br/>

<a href="https://github.com/Preethamn15/AI-Controlled-Automated-Hydroponic-Farming-System"><img src="https://img.shields.io/badge/▸_Launch_Repo-00d4ff?style=for-the-badge&labelColor=0a1628"/></a>

<br/><br/>

</td></tr>
</table>

</td>
</tr>
</table>

<br/>

<!-- ═══ ANALYTICS — framed in custom SVG monitor ═══ -->

<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 920 50" width="920">
  <rect x="0" y="20" width="920" height="1" fill="#1e3a5f"/>
  <rect x="30" y="10" width="120" height="24" rx="6" fill="#0f172a" stroke="#1e3a5f"/>
  <text x="90" y="26" fill="#00d4ff" font-family="monospace" font-size="10" text-anchor="middle">METRICS</text>
  <circle cx="870" cy="22" r="5" fill="#22c55e" opacity="0.8"/>
  <text x="850" y="26" fill="#64748b" font-family="monospace" font-size="9" text-anchor="end">LIVE</text>
</svg>

<table>
<tr>
<td><img height="170" src="https://github-readme-stats.vercel.app/api?username=Preethamn15&show_icons=true&theme=tokyonight&hide_border=true&bg_color=070b14&title_color=00d4ff&icon_color=00d4ff&text_color=c9d1d9&border_radius=14"/></td>
<td><img height="170" src="https://github-readme-streak-stats.demolab.com?user=Preethamn15&theme=tokyonight&hide_border=true&background=070b14&ring=00d4ff&fire=00d4ff&currStreakLabel=00d4ff&border_radius=14"/></td>
</tr>
<tr>
<td><img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Preethamn15&layout=compact&theme=tokyonight&hide_border=true&bg_color=070b14&title_color=00d4ff&text_color=c9d1d9&border_radius=14&langs_count=8"/></td>
<td><img height="170" src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=Preethamn15&theme=tokyonight&bg_color=070b14"/></td>
</tr>
</table>

<br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Preethamn15&theme=tokyo-night&hide_border=true&bg_color=070b14&color=00d4ff&line=0066ff&point=00d4ff&area=true&height=260"/>

<br/>

<img src="https://github-profile-trophy.vercel.app/?username=Preethamn15&theme=tokyonight&no-frame=true&no-bg=true&margin-w=6&column=7"/>

</div>

<br/>

<!-- ═══ ENGINEERING CORE — manifesto SVG ═══ -->

<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 920 160" width="920">
  <defs>
    <linearGradient id="quote" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#0066ff" stop-opacity="0"/>
      <stop offset="50%" stop-color="#00d4ff" stop-opacity="0.3"/>
      <stop offset="100%" stop-color="#6366f1" stop-opacity="0"/>
    </linearGradient>
  </defs>
  <style>
    @keyframes quoteGlow { 0%,100%{opacity:.6} 50%{opacity:1} }
    .qg{animation:quoteGlow 4s ease-in-out infinite}
  </style>
  <rect width="920" height="160" rx="16" fill="#070b14" stroke="#1e3a5f" stroke-width="1"/>
  <rect class="qg" x="60" y="30" width="800" height="2" fill="url(#quote)"/>
  <text x="460" y="70" fill="#e2e8f0" font-family="Georgia, serif" font-size="18" font-style="italic" text-anchor="middle">"Build systems you'd trust at 2 AM."</text>
  <text x="460" y="100" fill="#64748b" font-family="monospace" font-size="11" text-anchor="middle">Simplicity scales · Design for failure · Measure everything · Ship iteratively</text>
  <text x="460" y="130" fill="#475569" font-family="monospace" font-size="10" text-anchor="middle">— engineering.manifesto</text>
</svg>

</div>

<br/>

<table width="100%">
<tr valign="top">
<td width="50%">

<table width="98%">
<tr><td bgcolor="#111827">&nbsp; **`architecture.interests`**</td></tr>
<tr><td bgcolor="#0a1628">

<br/>

Microservices & bounded contexts

Event-driven architecture (Kafka)

CQRS · API gateways · load balancing

Caching layers · Redis patterns

K8s orchestration · service mesh

<br/>

</td></tr>
</table>

</td>
<td width="50%">

<table width="98%">
<tr><td bgcolor="#111827">&nbsp; **`current.mission`**</td></tr>
<tr><td bgcolor="#0a1628">

<br/>

→ Master backend engineering at enterprise scale

→ Production-grade Go microservices

→ Deep Kubernetes & system design

→ Ship open-source backend tools

→ Bridge AI inference into backends

<br/>

</td></tr>
</table>

</td>
</tr>
</table>

<br/>

<details>
<summary><b>▸ &nbsp; kernel.log — philosophy · roadmap · reading list</b></summary>
<br/>

<table width="100%">
<tr valign="top">
<td width="33%">

**System Design Topics**

Rate limiting · Consistent hashing

CAP theorem · DB sharding

Message queues · CDN caching

Circuit breakers · Idempotency

</td>
<td width="33%">

**2025–2026 Roadmap**

- [ ] Production Go microservice
- [ ] CKA certification
- [ ] Open-source library
- [ ] System design blog
- [ ] gRPC implementation

</td>
<td width="33%">

**Currently Reading**

Designing Data-Intensive Applications

System Design Interview (Vol 1 & 2)

Effective Go · K8s in Action

</td>
</tr>
</table>

<br/>

<table width="100%">
<tr valign="top">
<td width="50%">

**Backend Checklist**

☑ RESTful API design &nbsp; ☑ Auth patterns

☑ Database indexing &nbsp; ☐ Circuit breakers

☑ Connection pooling &nbsp; ☐ Distributed tracing

</td>
<td width="50%">

**This Week I Learned**

Idempotency keys prevent duplicate event processing

K8s liveness ≠ readiness — they serve different purposes

Connection pool sizing directly impacts p99 latency

</td>
</tr>
</table>

</details>

<br/>

<!-- ═══ FOOTER — animated wave SVG ═══ -->

<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 920 200" width="920">
  <defs>
    <linearGradient id="wave" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" stop-color="#070b14"/>
      <stop offset="100%" stop-color="#0a1628"/>
    </linearGradient>
    <linearGradient id="waveLine" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#0066ff"/>
      <stop offset="50%" stop-color="#00d4ff"/>
      <stop offset="100%" stop-color="#6366f1"/>
    </linearGradient>
  </defs>
  <style>
    @keyframes wave1 { 0%{d:path("M0,80 C230,120 460,40 920,80 L920,200 L0,200 Z")} 50%{d:path("M0,80 C230,40 460,120 920,80 L920,200 L0,200 Z")} 100%{d:path("M0,80 C230,120 460,40 920,80 L920,200 L0,200 Z")} }
    @keyframes heart { 0%,100%{transform:scale(1)} 50%{transform:scale(1.15)} }
    .w1{animation:wave1 6s ease-in-out infinite}
    .heart{animation:heart 1.5s ease-in-out infinite;transform-origin:460px 130px}
  </style>
  <rect width="920" height="200" fill="url(#wave)"/>
  <path class="w1" fill="url(#waveLine)" opacity="0.15" d="M0,80 C230,120 460,40 920,80 L920,200 L0,200 Z"/>
  <path fill="none" stroke="url(#waveLine)" stroke-width="1.5" opacity="0.4" d="M0,80 C230,120 460,40 920,80"/>
  <text x="460" y="110" fill="#e2e8f0" font-family="Georgia, serif" font-size="22" text-anchor="middle">Let's build something that scales.</text>
  <text x="460" y="140" fill="#64748b" font-family="monospace" font-size="11" text-anchor="middle">preetham.sys — graceful shutdown complete</text>
  <g class="heart">
    <text x="460" y="168" fill="#00d4ff" font-family="monospace" font-size="10" text-anchor="middle">♥ engineered with intent</text>
  </g>
</svg>

<br/>

<a href="https://github.com/Preethamn15"><img src="https://img.shields.io/badge/GitHub-@Preethamn15-181717?style=for-the-badge&logo=github"/></a>
&nbsp;
<a href="https://www.linkedin.com/in/preetham-n-672951284/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin"/></a>
&nbsp;
<a href="mailto:preethamn2004@gmail.com"><img src="https://img.shields.io/badge/Email-Reach_Out-EA4335?style=for-the-badge&logo=gmail"/></a>

<br/><br/>

<a href="mailto:preethamn2004@gmail.com"><img src="https://img.shields.io/badge/▸_Start_a_Conversation-00d4ff?style=for-the-badge&labelColor=0a1628"/></a>

<br/><br/>

<sub>© 2025 Preetham · Backend · Distributed Systems · Cloud Native</sub>

</div>
