<div align="center">

  <!-- 3D Modern Tech Banner -->
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1100 320" width="100%">
    <defs>
      <!-- Background Linear Gradients -->
      <linearGradient id="bg-grad" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" stop-color="#080c14"/>
        <stop offset="50%" stop-color="#0d1527"/>
        <stop offset="100%" stop-color="#050811"/>
      </linearGradient>

      <!-- Grid Pattern -->
      <pattern id="grid" width="40" height="40" patternUnits="userSpaceOnUse">
        <path d="M 40 0 L 0 0 0 40" fill="none" stroke="#1d2b45" stroke-width="1" opacity="0.4"/>
      </pattern>

      <!-- Glow Filters -->
      <filter id="glow-cyan" x="-20%" y="-20%" width="140%" height="140%">
        <feGaussianBlur stdDeviation="8" result="blur" />
        <feComposite in="SourceGraphic" in2="blur" operator="over"/>
      </filter>
      
      <filter id="glow-blue" x="-20%" y="-20%" width="140%" height="140%">
        <feGaussianBlur stdDeviation="15" result="blur" />
        <feComposite in="SourceGraphic" in2="blur" operator="over"/>
      </filter>

      <!-- Card Gradients -->
      <linearGradient id="card-grad" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" stop-color="#162238" stop-opacity="0.8"/>
        <stop offset="100%" stop-color="#0a101d" stop-opacity="0.9"/>
      </linearGradient>
      
      <linearGradient id="accent-cyan" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" stop-color="#00f2fe"/>
        <stop offset="100%" stop-color="#4facfe"/>
      </linearGradient>

      <!-- 3D Perspective Grid Cube -->
      <linearGradient id="cube-side" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" stop-color="#00f2fe" stop-opacity="0.3"/>
        <stop offset="100%" stop-color="#007acc" stop-opacity="0.05"/>
      </linearGradient>
    </defs>

    <!-- Base Canvas -->
    <rect width="1100" height="320" rx="16" fill="url(#bg-grad)"/>
    <rect width="1100" height="320" rx="16" fill="url(#grid)"/>

    <!-- 3D Floating Perspective Grid Lines Left & Right (Wireframe Frames) -->
    <path d="M 40 40 L 120 40 L 120 280 L 40 280 Z" fill="none" stroke="#00f2fe" stroke-width="2" opacity="0.5" filter="url(#glow-cyan)"/>
    <path d="M 40 40 L 70 70 L 70 250 L 40 280 Z" fill="url(#cube-side)"/>
    
    <path d="M 1060 40 L 980 40 L 980 280 L 1060 280 Z" fill="none" stroke="#00f2fe" stroke-width="2" opacity="0.5" filter="url(#glow-cyan)"/>
    <path d="M 1060 40 L 1030 70 L 1030 250 L 1060 280 Z" fill="url(#cube-side)"/>

    <!-- Ambient 3D Glowing Spheres -->
    <circle cx="220" cy="80" r="60" fill="#00f2fe" opacity="0.15" filter="url(#glow-blue)"/>
    <circle cx="880" cy="240" r="80" fill="#007acc" opacity="0.2" filter="url(#glow-blue)"/>

    <!-- Left Side: 3D Badge Pills -->
    <g transform="translate(140, 65)">
      <!-- Role Badge -->
      <rect x="0" y="0" width="145" height="28" rx="6" fill="#0d1b2a" stroke="#00f2fe" stroke-width="1.5"/>
      <text x="72" y="18" font-family="'Fira Code', 'Courier New', monospace" font-size="11" font-weight="bold" fill="#00f2fe" text-anchor="middle">Full Stack Developer</text>

      <!-- Status Badge -->
      <rect x="155" y="0" width="110" height="28" rx="6" fill="#0d1b2a" stroke="#43A047" stroke-width="1.5"/>
      <text x="210" y="18" font-family="'Fira Code', 'Courier New', monospace" font-size="11" font-weight="bold" fill="#43A047" text-anchor="middle">Open to Work</text>

      <!-- Sub Greeting -->
      <text x="2" y="62" font-family="'Segoe UI', Roboto, sans-serif" font-size="18" fill="#8b949e" letter-spacing="1">Hello, I'm</text>
      
      <!-- Main Name Heading -->
      <text x="0" y="120" font-family="'Segoe UI', Roboto, sans-serif" font-size="48" font-weight="900" fill="#ffffff" letter-spacing="1.5">Md. Rahim Miah</text>
      
      <!-- Cyan Accent Underline Line -->
      <rect x="0" y="132" width="380" height="3" fill="url(#accent-cyan)" filter="url(#glow-cyan)"/>

      <!-- Stack Tech Tags -->
      <text x="2" y="165" font-family="'Fira Code', monospace" font-size="14" font-weight="600" fill="#36BCF7">Next.js 15 &bull; TypeScript &bull; Express.js &bull; MongoDB</text>
    </g>

    <!-- Right Side: 3D Interactive Floating Skill Grid Cards -->
    <g transform="translate(680, 50)">
      <!-- Row 1 -->
      <g transform="translate(0, 0)">
        <rect width="105" height="42" rx="8" fill="url(#card-grad)" stroke="#1f3352" stroke-width="1.5"/>
        <text x="52" y="26" font-family="'Fira Code', monospace" font-size="13" font-weight="600" fill="#e6edf3" text-anchor="middle">JavaScript</text>
      </g>
      <g transform="translate(118, 0)">
        <rect width="105" height="42" rx="8" fill="url(#card-grad)" stroke="#1f3352" stroke-width="1.5"/>
        <text x="52" y="26" font-family="'Fira Code', monospace" font-size="13" font-weight="600" fill="#e6edf3" text-anchor="middle">TypeScript</text>
      </g>

      <!-- Row 2 -->
      <g transform="translate(0, 54)">
        <rect width="105" height="42" rx="8" fill="url(#card-grad)" stroke="#00f2fe" stroke-width="1.5" filter="url(#glow-cyan)" opacity="0.9"/>
        <text x="52" y="26" font-family="'Fira Code', monospace" font-size="13" font-weight="bold" fill="#00f2fe" text-anchor="middle">React.js</text>
      </g>
      <g transform="translate(118, 54)">
        <rect width="105" height="42" rx="8" fill="url(#card-grad)" stroke="#00f2fe" stroke-width="1.5" filter="url(#glow-cyan)" opacity="0.9"/>
        <text x="52" y="26" font-family="'Fira Code', monospace" font-size="13" font-weight="bold" fill="#00f2fe" text-anchor="middle">Next.js 15</text>
      </g>

      <!-- Row 3 -->
      <g transform="translate(0, 108)">
        <rect width="105" height="42" rx="8" fill="url(#card-grad)" stroke="#1f3352" stroke-width="1.5"/>
        <text x="52" y="26" font-family="'Fira Code', monospace" font-size="13" font-weight="600" fill="#e6edf3" text-anchor="middle">Node.js</text>
      </g>
      <g transform="translate(118, 108)">
        <rect width="105" height="42" rx="8" fill="url(#card-grad)" stroke="#1f3352" stroke-width="1.5"/>
        <text x="52" y="26" font-family="'Fira Code', monospace" font-size="13" font-weight="600" fill="#e6edf3" text-anchor="middle">Express.js</text>
      </g>

      <!-- Row 4 -->
      <g transform="translate(0, 162)">
        <rect width="105" height="42" rx="8" fill="url(#card-grad)" stroke="#1f3352" stroke-width="1.5"/>
        <text x="52" y="26" font-family="'Fira Code', monospace" font-size="13" font-weight="600" fill="#e6edf3" text-anchor="middle">MongoDB</text>
      </g>
      <g transform="translate(118, 162)">
        <rect width="105" height="42" rx="8" fill="url(#card-grad)" stroke="#1f3352" stroke-width="1.5"/>
        <text x="52" y="26" font-family="'Fira Code', monospace" font-size="13" font-weight="600" fill="#e6edf3" text-anchor="middle">Tailwind</text>
      </g>
    </g>
  </svg>

  <br/>

  <!-- Dynamic Typing Header -->
  <a href="https://github.com/Rahim-Ahmed-10">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=36BCF7&center=true&width=550&lines=Full+Stack+Developer;Next.js+%26+TypeScript+Specialist;Building+Scalable+Web+Applications;Turning+Ideas+Into+Functional+Products" alt="Typing SVG" />
  </a>

  <br/><br/>

  <!-- Status & Role Badges -->
  <p align="center">
    <a href="https://github.com/Rahim-Ahmed-10"><img src="https://img.shields.io/badge/Role-Full%20Stack%20Developer-007ACC?style=for-the-badge&logo=codeforces&logoColor=white" /></a>
    <a href="https://github.com/Rahim-Ahmed-10"><img src="https://img.shields.io/badge/Stack-Full--Stack%20Web%20Dev-61DAFB?style=for-the-badge&logo=react&logoColor=black" /></a>
    <a href="https://github.com/Rahim-Ahmed-10"><img src="https://img.shields.io/badge/Location-Bangladesh-FF4B4B?style=for-the-badge&logo=googlemaps&logoColor=white" /></a>
    <a href="mailto:rahimahmed01690@gmail.com"><img src="https://img.shields.io/badge/Hire%20Me-Open%20To%20Work-43A047?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  </p>

</div>

<br/>

---

## 👨‍💻 About Me

<table>
  <tr>
    <td width="60%" valign="top">
      <ul>
        <li>🔭 <b>Current Focus:</b> Engineering scalable full-stack web applications with <b>Next.js 15 (App Router)</b>, <b>TypeScript</b>, and <b>Express.js</b>.</li>
        <li>🎓 <b>Engineering Journey:</b> Transitioned into full-time Software Engineering through intensive daily application development and full-stack project building.</li>
        <li>⚡ <b>Commitment:</b> Devoting <b>6–7 hours daily</b> to core logic building, API optimization, and end-to-end web architecture design.</li>
        <li>⚽ <b>Personal Interest:</b> Active midfielder for local football club Brothers FC Kolatuli!</li>
        <li>⚡ <b>Fun Fact:</b> Passionate about optimizing backend APIs and creating seamless interactive UI transitions.</li>
      </ul>
    </td>
    <td width="40%" align="center" valign="middle">
      <img src="https://cdn.dribbble.com/users/1162077/screenshots/3848914/programmer.gif" width="100%" alt="Developer Coding GIF" />
    </td>
  </tr>
</table>

<br/>

---

## 🏆 GitHub Trophies

<div align="center">
  <a href="https://github.com/ryo-ma/github-profile-trophy">
    <img src="https://github-profile-trophy.vercel.app/?username=Rahim-Ahmed-10&theme=tokyonight&column=6&margin-w=15&margin-h=15&no-bg=true" alt="GitHub Trophies" />
  </a>
</div>

<br/>

---

## 🛠 Tech Stack & Capabilities

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">🎨 Frontend Engineering</h3>
      <p align="center">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg" alt="HTML5" width="38" height="38"/> &nbsp;
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg" alt="CSS3" width="38" height="38"/> &nbsp;
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="JavaScript" width="38" height="38"/> &nbsp;
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="TypeScript" width="38" height="38"/> &nbsp;
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" alt="React" width="38" height="38"/> &nbsp;
        <img src="https://cdn.worldvectorlogo.com/logos/nextjs-2.svg" alt="Next.js" width="38" height="38"/> &nbsp;
        <img src="https://www.vectorlogo.zone/logos/tailwindcss/tailwindcss-icon.svg" alt="Tailwind CSS" width="38" height="38"/>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">⚙️ Backend & Architecture</h3>
      <p align="center">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original.svg" alt="Node.js" width="38" height="38"/> &nbsp;
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original.svg" alt="Express.js" width="38" height="38"/> &nbsp;
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original.svg" alt="MongoDB" width="38" height="38"/> &nbsp;
        <img src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" alt="Firebase" width="38" height="38"/> &nbsp;
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/prisma/prisma-original.svg" alt="Prisma ORM" width="38" height="38"/>
      </p>
    </td>
  </tr>
  <tr>
    <td colspan="2" valign="top">
      <h3 align="center">🛠️ Workflow & Infrastructure Tools</h3>
      <p align="center">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/vscode/vscode-original.svg" alt="VS Code" width="38" height="38"/> &nbsp;
        <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="Git" width="38" height="38"/> &nbsp;
        <img src="https://www.vectorlogo.zone/logos/github/github-icon.svg" alt="GitHub" width="38" height="38"/> &nbsp;
        <img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" alt="Postman" width="38" height="38"/> &nbsp;
        <img src="https://www.vectorlogo.zone/logos/vercel/vercel-icon.svg" alt="Vercel" width="38" height="38"/> &nbsp;
        <img src="https://www.vectorlogo.zone/logos/netlify/netlify-icon.svg" alt="Netlify" width="38" height="38"/>
      </p>
    </td>
  </tr>
</table>

<br/>

---

## 🚀 Featured Production Projects

<br/>

<table>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">⚽ SquadCraft</h3>
      <p align="center"><b>Sports Management & Tactical Planning Platform</b></p>
      <p>Full-stack football management platform featuring interactive squad arrangement builders, tactical lineup configurations, and team roster management.</p>
      <hr/>
      <p><b>✨ Key Tech:</b> <code>Next.js 15</code>, <code>Tailwind CSS</code>, <code>Node.js</code>, <code>MongoDB</code>, <code>JWT</code></p>
      <div align="center">
        <a href="https://squadraft-client.vercel.app" target="_blank">🌐 Live Application</a> | 
        <a href="https://github.com/Rahim-Ahmed-10/Squadraft-client" target="_blank">💻 Source Code</a>
      </div>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">🏥 MediCare Connect</h3>
      <p align="center"><b>Healthcare Digital Ecosystem & Telemedicine</b></p>
      <p>Comprehensive healthcare web portal enabling online doctor consultations, appointment booking, Stripe payment integration, and real-time patient management.</p>
      <hr/>
      <p><b>✨ Key Tech:</b> <code>Next.js</code>, <code>Express.js</code>, <code>MongoDB</code>, <code>Stripe</code>, <code>Framer Motion</code></p>
      <div align="center">
        <a href="https://medicare-connect-client-theta.vercel.app" target="_blank">🌐 Live Application</a> | 
        <a href="https://github.com/Rahim-Ahmed-10/medicare-connect-client" target="_blank">💻 Source Code</a>
      </div>
    </td>
  </tr>
</table>

<br/>

---

## 📊 Analytics & Coding Contributions

<div align="center">

  <!-- GitHub Streak Card -->
  <p align="center">
    <img src="https://streak-stats.demolab.com/?user=Rahim-Ahmed-10&theme=tokyonight&hide_border=true" alt="GitHub Streak Stats" />
  </p>

  <!-- GitHub Main Stats Card -->
  <p align="center">
    <img src="https://github-readme-stats.vercel.app/api?username=Rahim-Ahmed-10&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub Stats" />
  </p>

</div>

<br/>

---

## 💬 Developer Mindset

<div align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight" alt="Developer Quote" />
</div>

<br/>

---

## 📬 Let's Connect & Collaborate

<div align="center">
  <p>I am open to full-time remote/onsite Full Stack Developer positions, freelance contracts, and open-source contributions.</p>

  <a href="mailto:rahimahmed01690@gmail.com">
    <img src="https://img.shields.io/badge/Email-rahimahmed01690%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  &nbsp;
  <a href="https://fb.com/100071816113262" target="_blank">
    <img src="https://img.shields.io/badge/Facebook-Md._Rahim_Miah-1877F2?style=for-the-badge&logo=facebook&logoColor=white" />
  </a>
  &nbsp;
  <a href="https://rahim-digital-portfolio.netlify.app" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio-Visit%20Website-00C7B7?style=for-the-badge&logo=netlify&logoColor=white" />
  </a>

  <br/><br/>

  <!-- Profile Visitor Counter -->
  <p>
    <img src="https://komarev.com/ghpvc/?username=rahim-ahmed-10&label=Profile%20Views&color=007ACC&style=for-the-badge" alt="Profile Views" />
  </p>
</div>
