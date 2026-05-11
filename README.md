<div align="center">
  <svg width="100%" height="280" viewBox="0 0 800 280" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
    <defs>
      <!-- Animated Mesh Gradient Background -->
      <linearGradient id="bgGrad" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" stop-color="#0a0a2e">
          <animate attributeName="stop-color" values="#0a0a2e;#1a1040;#0a0a2e" dur="6s" repeatCount="indefinite"/>
        </stop>
        <stop offset="50%" stop-color="#1e1450">
          <animate attributeName="stop-color" values="#1e1450;#2a1b66;#1e1450" dur="6s" repeatCount="indefinite"/>
        </stop>
        <stop offset="100%" stop-color="#0a0a2e">
          <animate attributeName="stop-color" values="#0a0a2e;#1a1040;#0a0a2e" dur="6s" repeatCount="indefinite"/>
        </stop>
      </linearGradient>
      <!-- Animated Dot Pattern Overlay -->
      <pattern id="dotPattern" x="0" y="0" width="50" height="50" patternUnits="userSpaceOnUse">
        <circle cx="2" cy="2" r="1.2" fill="#ffffff" opacity="0.08">
          <animate attributeName="opacity" values="0.08;0.2;0.08" dur="3s" repeatCount="indefinite"/>
        </circle>
      </pattern>
      <!-- Neon Glow Filter -->
      <filter id="glow" x="-20%" y="-20%" width="140%" height="140%">
        <feGaussianBlur in="SourceGraphic" stdDeviation="5" result="blur1"/>
        <feGaussianBlur in="SourceGraphic" stdDeviation="12" result="blur2"/>
        <feMerge>
          <feMergeNode in="blur2"/>
          <feMergeNode in="blur1"/>
          <feMergeNode in="SourceGraphic"/>
        </feMerge>
      </filter>
      <!-- Subtle Text Shadow -->
      <filter id="softShadow">
        <feDropShadow dx="0" dy="2" stdDeviation="3" flood-color="#000" flood-opacity="0.5"/>
      </filter>
    </defs>

    <!-- Background layers -->
    <rect width="800" height="280" fill="url(#bgGrad)" rx="20"/>
    <rect width="800" height="280" fill="url(#dotPattern)" rx="20"/>

    <!-- Decorative Animated Code Brackets -->
    <g opacity="0.12">
      <text x="40" y="240" font-family="'Fira Code', monospace" font-size="70" fill="#ffffff" filter="url(#softShadow)">
        &lt;
        <animate attributeName="y" values="240;220;240" dur="4.5s" repeatCount="indefinite" />
      </text>
      <text x="720" y="240" font-family="'Fira Code', monospace" font-size="70" fill="#ffffff" filter="url(#softShadow)">
        /&gt;
        <animate attributeName="y" values="240;260;240" dur="4.5s" repeatCount="indefinite" />
      </text>
    </g>

    <!-- Floating Tech Orbs -->
    <circle cx="120" cy="60" r="5" fill="#FF6584" opacity="0.9">
      <animate attributeName="cy" values="60;25;60" dur="3.2s" repeatCount="indefinite" />
      <animate attributeName="opacity" values="0.9;0.4;0.9" dur="3.2s" repeatCount="indefinite" />
    </circle>
    <circle cx="680" cy="90" r="7" fill="#6C63FF" opacity="0.7">
      <animate attributeName="cy" values="90;45;90" dur="3.8s" repeatCount="indefinite" />
    </circle>
    <circle cx="400" cy="40" r="4" fill="#00F7FF" opacity="0.8">
      <animate attributeName="cy" values="40;15;40" dur="2.9s" repeatCount="indefinite" />
    </circle>
    <circle cx="250" cy="70" r="3" fill="#FF6584" opacity="0.5">
      <animate attributeName="cy" values="70;35;70" dur="4s" repeatCount="indefinite" />
    </circle>
    <circle cx="550" cy="50" r="6" fill="#6C63FF" opacity="0.6">
      <animate attributeName="cy" values="50;20;50" dur="3.4s" repeatCount="indefinite" />
    </circle>

    <!-- Glowing Name -->
    <text x="400" y="110" text-anchor="middle" font-family="'Segoe UI', 'Fira Code', 'Poppins', sans-serif" font-size="48" font-weight="900" fill="#ffffff" filter="url(#glow)">
      Hi 👋, I'm Pawan Kumar
    </text>

    <!-- Embedded Typing Animation (exact external image) -->
    <image x="200" y="150" width="400" height="50" xlink:href="https://readme-typing-svg.herokuapp.com?font=Fira+Code&amp;weight=700&amp;size=22&amp;pause=1000&amp;color=00F7FF&amp;center=true&amp;vCenter=true&amp;width=400&amp;lines=Full+Stack+%26+AI+Developer;Building+Scalable+Marketplaces;MERN+%2B+AI+Engineer;LLM+%26+Cloud+Enthusiast" />

    <!-- Optional Rounded Bottom Border Glow -->
    <rect x="0" y="278" width="800" height="2" fill="url(#bgGrad)" rx="20">
      <animate attributeName="height" values="2;4;2" dur="2s" repeatCount="indefinite" />
    </rect>
  </svg>
</div>





<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:6C63FF,100:FF6584&height=3&section=header" width="100%">
</p>

<div align="center">
  <h2>💫 About Me</h2>
</div>

<p align="center">
  <img src="https://img.shields.io/badge/🎓-BTech_Uttaranchal_University-3b82f6?style=for-the-badge&labelColor=1e293b" />
  <img src="https://img.shields.io/badge/🌟-AI_%26_Full_Stack-ff6584?style=for-the-badge&labelColor=1e293b" />
  <img src="https://img.shields.io/badge/⚡-Building_Big_Systems-10b981?style=for-the-badge&labelColor=1e293b" />
  <img src="https://img.shields.io/badge/🧠-Distributed_Systems_Explorer-f59e0b?style=for-the-badge&labelColor=1e293b" />
  <img src="https://img.shields.io/badge/Focus-Scalable_AI_Driven_Big_Systems-6C63FF?style=for-the-badge&logo=ai&logoColor=white" />
  <img src="https://img.shields.io/badge/Location-India-FF6F00?style=for-the-badge&logo=google-earth&logoColor=white" />
</p>

<img align="right" alt="Coding" width="300" 
     src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" 
     style="border-radius: 16px; margin-left: 24px; box-shadow: 0 4px 15px rgba(0,0,0,0.2);">

**🎓 BTech Student** at Uttaranchal University  
**💡 Passionate about** AI systems, scalable backend architectures, cloud computing, and real‑world marketplace platforms  

**🚀 Currently Crafting**  
 🛒 **Opentrade** – Advanced Multi‑Vendor Marketplace  
 🤖 AI & LLM Powered Applications  
 💬 Real‑Time Messaging Systems  
 ☁️ Scalable Cloud Architectures  
 📦 Enterprise MERN Stack Systems  

**🌱 Deep Diving Into**  
 Distributed Systems • AI Engineering • DevOps & Cloud Infrastructure • Advanced Backend Design  

**🏆 Participations**  
 Hackathons • Coding Competitions • Technical Events  

**🎯 Goal**  
> Build powerful AI platforms that solve real‑world problems.  

**⚡ Fun Fact**  
> I love turning complex ideas into fully functional products — and I do it with a smile.  

<br clear="right"/>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:6C63FF,100:FF6584&height=3&section=header" width="100%">
</p>
<div align="center">
<h2>🌐 Connect With Me</h2>
</div>

<p align="center">
  <a href="https://linkedin.com/in/pavan-kumar-23a3402b3" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://x.com/Pawan3253702" target="_blank">
    <img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=twitter&logoColor=white" />
  </a>
  <a href="mailto:pk3253702@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://github.com/POWER-WORLD">
    <img src="https://img.shields.io/badge/GitHub-121011?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <a href="https://dev.to/power_world" target="_blank">
    <img src="https://img.shields.io/badge/dev.to-0A0A0A?style=for-the-badge&logo=devdotto&logoColor=white" />
  </a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:6C63FF,100:FF6584&height=3&section=header" width="100%">
</p>

<div align="center">
  <h2>💻 Tech Stack</h2>
</div>

<details open>
<summary align="center"><b>🚀 Languages</b></summary>
<br>
<p align="center">
  <img src="https://skillicons.dev/icons?i=python,javascript,typescript,php,c,java&perline=6" />
</p>
</details>

<details open>
<summary align="center"><b>🎨 Frontend</b></summary>
<br>
<p align="center">
  <img src="https://skillicons.dev/icons?i=html,css,react,nextjs,bootstrap,tailwind,vite&perline=7" />
</p>
</details>

<details open>
<summary align="center"><b>⚙️ Backend</b></summary>
<br>
<p align="center">
  <img src="https://skillicons.dev/icons?i=nodejs,express,nestjs,fastapi,firebase&perline=5" />
</p>
</details>

<details open>
<summary align="center"><b>🗄️ Databases</b></summary>
<br>
<p align="center">
  <img src="https://skillicons.dev/icons?i=mongodb,mysql,postgresql,sqlite&perline=4" />
</p>
</details>

<details open>
<summary align="center"><b>☁️ Cloud & DevOps</b></summary>
<br>
<p align="center">
  <img src="https://skillicons.dev/icons?i=aws,docker,nginx,vercel,netlify,render,githubactions&perline=7" />
</p>
</details>

<details open>
<summary align="center"><b>🤖 AI / Machine Learning</b></summary>
<br>
<p align="center">
  <img src="https://skillicons.dev/icons?i=tensorflow,pytorch&perline=2" />
  <br>
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
</p>
</details>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:6C63FF,100:FF6584&height=3&section=header" width="100%">
</p>

<div align="center">
  <h2>🚀 Featured Projects</h2>
</div>
<table>
  <tr>
    <td width="50%">
      <h3 align="center">🛒 Opentrade Marketplace</h3>
      <p align="center">
        <img src="https://img.shields.io/badge/Status-In_Progress-brightgreen?style=flat-square" />
        <img src="https://img.shields.io/badge/Stack-MERN-blue?style=flat-square" />
        <br>
        Advanced multi‑vendor e‑commerce platform with buyer, seller, admin, delivery & service‑provider roles. Real‑world commerce architecture.
      </p>
    </td>
    <td width="50%">
      <h3 align="center">🤖 AI Data Drift Detector</h3>
      <p align="center">
        <img src="https://img.shields.io/badge/Status-Completed-success?style=flat-square" />
        <img src="https://img.shields.io/badge/Tech-Python%20%7C%20ML-orange?style=flat-square" />
        <br>
        Intelligent monitoring system to detect dataset drift and validate production data pipelines.
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3 align="center">💬 Real-Time Messaging</h3>
      <p align="center">
        <img src="https://img.shields.io/badge/Status-Alpha-yellow?style=flat-square" />
        <img src="https://img.shields.io/badge/Tech-WebSockets%20%7C%20Node.js-lightgrey?style=flat-square" />
        <br>
        Scalable live chat with notifications, modern backend infrastructure & instant communication.
      </p>
    </td>
    <td width="50%">
      <h3 align="center">📊 LLM Playground (Coming)</h3>
      <p align="center">
        <img src="https://img.shields.io/badge/Status-Designing-blueviolet?style=flat-square" />
        <img src="https://img.shields.io/badge/Tech-LLM%20%7C%20Next.js-red?style=flat-square" />
        <br>
        Interactive environment to test and compare large language models with custom prompts.
      </p>
    </td>
  </tr>
</table>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:6C63FF,100:FF6584&height=3&section=header" width="100%">
</p>

<div align="center">
  <h2>📊 GitHub Stats</h2>
</div>

<p align="center">
  <!-- Streak Stats (reliable domain) -->
  <img src="https://streak-stats.demolab.com/?user=POWER-WORLD&theme=tokyonight&hide_border=true&date_format=M%20j%5B%2C%20Y%5D" height="200" width="100%"/>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:6C63FF,100:FF6584&height=3&section=header" width="100%">
</p>

<div align="center">
  <h2>🏆 GitHub Trophies</h2>
</div>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=POWER-WORLD&theme=tokyonight&no-frame=true&no-bg=true&margin-w=6" />
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:6C63FF,100:FF6584&height=3&section=header" width="100%">
</p>

<div align="center">
  <h2>📈 Contribution Graph</h2>
</div>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=POWER-WORLD&theme=tokyo-night&hide_border=true&area=true" />
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:6C63FF,100:FF6584&height=3&section=header" width="100%">
</p>

<div align="center">
  <h2>🧠 Developer Mindset</h2>
</div>

```javascript
const pawan = {
    code: ["JavaScript", "Python", "PHP", "TypeScript"],
    technologies: {
        frontend: ["React", "Next.js", "HTML", "CSS"],
        backend: ["Node.js", "Express", "NestJS", "FastAPI"],
        databases: ["MongoDB", "PostgreSQL", "MySQL"],
        cloud: ["AWS", "Firebase", "Docker"],
        ai_ml: ["TensorFlow", "PyTorch", "Scikit-Learn"]
    },
    currentFocus: "Building scalable AI-powered systems",
    lifePhilosophy: "Build systems that create real impact."
};
