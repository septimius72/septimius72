<!-- CYBERPUNK SVG BANNER -->
<div align="center">
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 300" width="100%" height="100%">
    <defs>
      <linearGradient id="bgGrad" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" stop-color="#030712" />
        <stop offset="50%" stop-color="#0b0f19" />
        <stop offset="100%" stop-color="#02040a" />
      </linearGradient>
      <linearGradient id="primaryGrad" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" stop-color="#00FF66" />
        <stop offset="100%" stop-color="#FFB800" />
      </linearGradient>
      <linearGradient id="secondaryGrad" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" stop-color="#10B981" />
        <stop offset="100%" stop-color="#06B6D4" />
      </linearGradient>
      <filter id="glowGreen" x="-20%" y="-20%" width="140%" height="140%">
        <feGaussianBlur stdDeviation="6" result="blur" />
        <feMerge>
          <feMergeNode in="blur" />
          <feMergeNode in="SourceGraphic" />
        </feMerge>
      </filter>
      <filter id="glowAmber" x="-20%" y="-20%" width="140%" height="140%">
        <feGaussianBlur stdDeviation="6" result="blur" />
        <feMerge>
          <feMergeNode in="blur" />
          <feMergeNode in="SourceGraphic" />
        </feMerge>
      </filter>
      <pattern id="grid" width="40" height="40" patternUnits="userSpaceOnUse">
        <path d="M 40 0 L 0 0 0 40" fill="none" stroke="#00FF66" stroke-width="0.5" stroke-opacity="0.08" />
      </pattern>
    </defs>
    <style>
      .title { font-family: 'Fira Code', Monaco, Consolas, monospace; font-weight: 800; font-size: 52px; fill: #ffffff; letter-spacing: 6px; }
      .subtitle { font-family: 'Fira Code', Monaco, Consolas, monospace; font-weight: 600; font-size: 18px; fill: #00FF66; letter-spacing: 3px; }
      .code-text { font-family: 'Fira Code', Monaco, Consolas, monospace; font-size: 13px; fill: #9CA3AF; }
      .accent-green { fill: #00FF66; }
      .accent-amber { fill: #FFB800; }
      @keyframes pulseGlow { 0% { opacity: 0.5; } 50% { opacity: 1; } 100% { opacity: 0.5; } }
      .pulsing { animation: pulseGlow 2.5s infinite ease-in-out; }
    </style>
    <rect width="1200" height="300" fill="url(#bgGrad)" rx="12" />
    <rect width="1200" height="300" fill="url(#grid)" rx="12" />
    <path d="M-50 300 L250 0 L350 0 L50 300 Z" fill="url(#primaryGrad)" opacity="0.06" />
    <path d="M850 0 L1050 300 L1250 300 L1050 0 Z" fill="url(#secondaryGrad)" opacity="0.06" />
    <path d="M 20 50 L 20 20 L 50 20" fill="none" stroke="#00FF66" stroke-width="3" filter="url(#glowGreen)" />
    <path d="M 1180 250 L 1180 280 L 1150 280" fill="none" stroke="#FFB800" stroke-width="3" filter="url(#glowAmber)" />
    <path d="M 150 20 L 450 20 L 480 50 L 720 50 L 750 20 L 1050 20" fill="none" stroke="#00FF66" stroke-width="1.5" stroke-opacity="0.3" />
    <circle cx="480" cy="50" r="3.5" fill="#00FF66" class="pulsing" />
    <circle cx="720" cy="50" r="3.5" fill="#FFB800" class="pulsing" />
    <path d="M 80 250 L 1120 250" fill="none" stroke="#10B981" stroke-width="1" stroke-dasharray="8 4" stroke-opacity="0.4" />
    <g transform="translate(600, 115)" text-anchor="middle">
      <text x="0" y="0" class="title" filter="url(#glowGreen)">ALEXANDER BECZ</text>
      <text x="0" y="42" class="subtitle" filter="url(#glowAmber)">&gt;_ SR. TECHNICAL RECRUITER  |  AI TALENT PARTNER  |  TA TECHIE</text>
    </g>
    <g transform="translate(600, 210)" text-anchor="middle" class="code-text">
      <rect x="-380" y="-18" width="760" height="34" rx="6" fill="#030712" stroke="#00FF66" stroke-width="1" stroke-opacity="0.4" />
      <text x="0" y="4" fill="#F3F4F6">
        <tspan class="accent-green">const</tspan> <tspan class="accent-amber">focus</tspan> = [<tspan fill="#6EE7B7">"Cybersecurity"</tspan>, <tspan fill="#6EE7B7">"Ruby on Rails"</tspan>, <tspan fill="#6EE7B7">"AI Workflows"</tspan>, <tspan fill="#6EE7B7">"TypeScript/React"</tspan>];
      </text>
    </g>
    <g transform="translate(40, 140)" class="code-text">
      <text x="0" y="-20" fill="#00FF66" font-weight="bold">SYS.LOC // UT, USA</text>
      <text x="0" y="0" fill="#9CA3AF">OSINT // ACTIVE</text>
      <text x="0" y="20" fill="#FFB800">STATUS // ONLINE</text>
    </g>
    <g transform="translate(1040, 140)" class="code-text" text-anchor="end">
      <text x="0" y="-20" fill="#FFB800" font-weight="bold">CLEARANCE // TOP</text>
      <text x="0" y="0" fill="#9CA3AF">STACK // FULL-STACK</text>
      <text x="0" y="20" fill="#00FF66">AI // GEMINI + CLAUDE</text>
    </g>
  </svg>
</div>

<br />

<!-- TYPING ANIMATION SUBTITLE -->
<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=24&pause=1000&color=00FF66&center=true&vcenter=true&width=700&height=50&lines=ALEXANDER+BECZ;Sr.+Technical+Recruiter+%7C+TA+Techie;AI+Workflows+%7C+Full-Stack+Engineering;OSINT+%7C+Automation+%7C+Building+Teams" alt="Alexander Becz Header" />

  <p align="center">
    <img src="https://img.shields.io/badge/STATUS-OPERATIONAL-00FF66?style=for-the-badge&logoColor=black" alt="Status" />
    <img src="https://img.shields.io/badge/CLEARANCE-TOP_TIER-10B981?style=for-the-badge&logoColor=black" alt="Clearance" />
    <img src="https://img.shields.io/badge/DOMAIN-CYBERSECURITY_%26_AI-FFB800?style=for-the-badge&logoColor=black" alt="Domain" />
  </p>
</div>

<div align="center">
  <a href="https://sashik.rf.gd/"><img src="https://img.shields.io/badge/Personal_Site-00FF66?style=for-the-badge&logo=googlechrome&logoColor=black" alt="Website"></a>
  <a href="https://linkedin.com/in/alxhb"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://proximoalex.weebly.com/"><img src="https://img.shields.io/badge/Portfolio-10B981?style=for-the-badge&logo=weebly&logoColor=black" alt="Portfolio"></a>
  <a href="mailto:shanko.becz@gmail.com"><img src="https://img.shields.io/badge/Email_Me-FFB800?style=for-the-badge&logo=gmail&logoColor=black" alt="Email"></a>
</div>

---

### ⚡ `sys.status` // System Overview

```typescript
interface DeveloperRecruiter {
  name: string;
  location: string;
  role: string;
  languages: string[];
  taSpecialties: string[];
  status: string;
}

const alex: DeveloperRecruiter = {
  name: "Alexander Becz",
  location: "Riverton, UT",
  role: "Sr. Technical Recruiter & Full-Stack TA Techie",
  languages: ["TypeScript", "JavaScript", "React", "Tailwind CSS", "Python", "HTML/CSS"],
  taSpecialties: ["Ruby on Rails Backend", "Threat Hunters", "SOC Analysts", "AI/ML Engineers"],
  status: "⚡ Building high-impact tech teams & engineering modern web apps"
};
