<!--
  Updated modern profile README for Anurag Behura
  - Keeps all original content (no additions / no deletions)
  - Uses SVG + inline HTML for visuals (safe for GitHub)
-->

<div align="center">

<!-- HERO: animated gradient blob + avatar card -->
<svg width="100%" height="220" viewBox="0 0 1200 220" preserveAspectRatio="xMidYMid slice" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Hero background">
  <defs>
    <linearGradient id="g1" x1="0" x2="1">
      <stop offset="0" stop-color="#58a6ff"/>
      <stop offset="0.5" stop-color="#c678dd"/>
      <stop offset="1" stop-color="#38b2ac"/>
    </linearGradient>
    <filter id="f1" x="-20%" y="-20%" width="140%" height="140%">
      <feGaussianBlur stdDeviation="30" result="b"/>
      <feBlend in="SourceGraphic" in2="b"/>
    </filter>
    <linearGradient id="textGrad" x1="0" x2="1">
      <stop offset="0" stop-color="#58a6ff"/>
      <stop offset="0.5" stop-color="#c678dd"/>
      <stop offset="1" stop-color="#38b2ac"/>
    </linearGradient>
    <clipPath id="rounded">
      <rect x="40" y="18" rx="18" ry="18" width="1120" height="184"/>
    </clipPath>
  </defs>

  <!-- animated blobs (SVG animation is supported on GitHub) -->
  <g clip-path="url(#rounded)" filter="url(#f1)">
    <path fill="url(#g1)" opacity="0.18">
      <animate attributeName="d" dur="12s" repeatCount="indefinite"
        values="
          M0,120 C120,70 220,0 360,40 C500,80 620,180 780,160 C940,140 1040,60 1200,80 L1200,220 L0,220 Z;
          M0,100 C140,140 260,200 360,160 C460,120 620,40 780,60 C940,80 1040,160 1200,120 L1200,220 L0,220 Z;
          M0,120 C120,70 220,0 360,40 C500,80 620,180 780,160 C940,140 1040,60 1200,80 L1200,220 L0,220 Z
        " />
    </path>
    <path fill="#0b1223" opacity="0.12">
      <animate attributeName="d" dur="10s" repeatCount="indefinite"
        values="
          M0,160 C140,180 260,120 380,140 C500,160 620,220 760,200 C900,180 1040,140 1200,160 L1200,220 L0,220 Z;
          M0,140 C120,100 260,40 380,80 C500,120 620,160 760,140 C900,120 1040,200 1200,160 L1200,220 L0,220 Z;
          M0,160 C140,180 260,120 380,140 C500,160 620,220 760,200 C900,180 1040,140 1200,160 L1200,220 L0,220 Z
        " />
    </path>
  </g>

  <!-- Glassy hero card -->
  <g>
    <rect x="44" y="24" width="1112" height="172" rx="14" ry="14" fill="white" opacity="0.03"/>
    <rect x="44" y="24" width="1112" height="172" rx="14" ry="14" fill="url(#g1)" opacity="0.03" />
  </g>

  <!-- Main text -->
  <foreignObject x="80" y="38" width="1040" height="150">
    <div xmlns="http://www.w3.org/1999/xhtml" style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial; color: #e6eef8; padding: 6px 10px;">
      <h1 style="font-size:34px; margin:0 0 6px; line-height:1; font-weight:700;">
        <span style="color:#ffffff; opacity:0.95;">👋 Hey there, I'm</span>
        <span style="background:linear-gradient(90deg,#58a6ff,#c678dd); -webkit-background-clip:text; color:transparent; font-weight:800;"> Anurag Behura</span>
      </h1>
      <h3 style="margin:0; font-size:16px; color:#cfdff6; font-weight:500;">
        💻 Full Stack Developer | Building <span style="color:#c678dd; font-weight:700;">Chronicle</span> – AI-Powered Content Platform
      </h3>

      <p style="margin:10px 0 0; color:#c9d9f2; font-size:13px; max-width:920px;">
        Passionate about building <strong>scalable, user-centric web apps</strong> using modern technologies.
        Currently crafting <strong>Chronicle</strong> — an <strong>AI-powered content &amp; document platform</strong> inspired by Notion.
      </p>
    </div>
  </foreignObject>
</svg>

</div>

<!-- PROFILE BODY: glass panels layout -->
<div align="center" style="margin-top:18px;">

<table align="center" cellpadding="12" cellspacing="0" width="100%" style="max-width:960px;">
  <tr>
    <!-- LEFT COLUMN -->
    <td valign="top" width="60%" style="padding:8px;">
      <div style="background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01)); border-radius:14px; padding:18px; box-shadow: 0 10px 30px rgba(2,6,23,0.35); backdrop-filter: blur(6px);">
        <h1 align="center" style="margin:4px 0 8px; font-size:20px; color:#e7f0ff;">About Me</h1>

        <p style="color:#d6e6ff; font-size:14px; margin:8px 6px;">
          - 🔭 Building <strong>Chronicle</strong> — AI-powered content &amp; knowledge management platform<br/>
          - ⚙️ Skilled in <strong>Next.js</strong>, <strong>TypeScript</strong>, <strong>Node.js</strong>, and modern SaaS architecture<br/>
          - 💡 Strong foundation in <strong>Data Structures &amp; Algorithms</strong> — love writing clean, efficient code<br/>
          - 🌐 Portfolio: <a href="https://anuragbehura.vercel.app" target="_blank" rel="noopener" style="color:#58a6ff; font-weight:600;">anuragbehura.vercel.app</a><br/>
          - 📫 Reach me at: <strong>behura960@gmail.com</strong>
        </p>

        <hr style="border:none; height:1px; background:linear-gradient(90deg, rgba(88,166,255,0.12), rgba(198,120,221,0.06)); margin:12px 4px;">

        <h3 style="margin:6px 0; color:#e7f0ff;">🚀 Quick Summary</h3>
        <p style="color:#cfe5ff; font-size:13px; margin:6px;">
          Passionate about building <strong>scalable, user-centric web apps</strong>. Currently crafting <strong>Chronicle</strong> — an AI-powered content &amp; document platform.
        </p>
      </div>

      <!-- Tech stack badges -->
      <div style="margin-top:12px; background: linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01)); border-radius:14px; padding:14px; box-shadow: 0 8px 22px rgba(2,6,23,0.28);">
        <h3 style="margin:0 0 8px; color:#e7f0ff;">🛠️ Tech Stack</h3>
        <div style="display:flex; flex-wrap:wrap; gap:8px;">
          <!-- Keep original badges (unchanged content) -->
          <div>
            <strong style="font-size:12px; color:#cfe5ff;">Languages</strong>
            <div style="margin-top:8px;">
              ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
              ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
              ![Java](https://img.shields.io/badge/-Java-007396?style=flat&logo=java&logoColor=white)
              ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)
            </div>
          </div>

          <div style="margin-top:10px;">
            <strong style="font-size:12px; color:#cfe5ff;">Frontend</strong>
            <div style="margin-top:8px;">
              ![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat&logo=next.js&logoColor=white)
              ![React](https://img.shields.io/badge/-React-61DAFB?style=flat&logo=react&logoColor=black)
              ![Tailwind CSS](https://img.shields.io/badge/-Tailwind_CSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white)
              ![Redux](https://img.shields.io/badge/-Redux-764ABC?style=flat&logo=redux&logoColor=white)
            </div>
          </div>

          <div style="margin-top:10px;">
            <strong style="font-size:12px; color:#cfe5ff;">Backend</strong>
            <div style="margin-top:8px;">
              ![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat&logo=node.js&logoColor=white)
              ![Express.js](https://img.shields.io/badge/-Express.js-000000?style=flat&logo=express&logoColor=white)
              ![REST API](https://img.shields.io/badge/-REST_API-009688?style=flat&logo=fastapi&logoColor=white)
              ![JWT](https://img.shields.io/badge/-JWT-000000?style=flat&logo=json-web-tokens&logoColor=white)
            </div>
          </div>

          <div style="margin-top:10px;">
            <strong style="font-size:12px; color:#cfe5ff;">Database</strong>
            <div style="margin-top:8px;">
              ![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
              ![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
            </div>
          </div>

          <div style="margin-top:10px;">
            <strong style="font-size:12px; color:#cfe5ff;">Tools & DevOps</strong>
            <div style="margin-top:8px;">
              ![Git](https://img.shields.io/badge/-Git-F05032?style=flat&logo=git&logoColor=white)
              ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)
              ![Postman](https://img.shields.io/badge/-Postman-FF6C37?style=flat&logo=postman&logoColor=white)
              ![Vercel](https://img.shields.io/badge/-Vercel-000000?style=flat&logo=vercel&logoColor=white)
            </div>
          </div>

          <div style="margin-top:10px; width:100%;">
            <strong style="font-size:12px; color:#cfe5ff;">Core CS Fundamentals</strong>
            <p style="margin:8px 0 0; color:#cfe5ff; font-size:13px;">Data Structures &amp; Algorithms • Object-Oriented Programming • Database Management Systems • Operating Systems • Computer Networks</p>
          </div>
        </div>
      </div>
    </td>

    <!-- RIGHT COLUMN -->
    <td valign="top" width="40%" style="padding:8px;">
      <div style="border-radius:14px; padding:16px; background: linear-gradient(180deg, rgba(255,255,255,0.02), rgba(8,12,20,0.02)); box-shadow: 0 10px 24px rgba(2,6,23,0.30);">
        <h3 style="margin:4px 0 10px; color:#e7f0ff;">📊 GitHub Stats</h3>

        <div align="center" style="margin-bottom:10px;">
          <img src="https://github-readme-stats.vercel.app/api/top-langs?username=anuragbehura&show_icons=true&locale=en&layout=compact&theme=dark" alt="anuragbehura" style="border-radius:10px; max-width:100%;" />
        </div>

        <div align="center">
          <img src="https://github-readme-streak-stats.herokuapp.com/?user=anuragbehura&theme=dark" alt="anuragbehura" style="border-radius:10px; max-width:100%;" />
        </div>

        <hr style="border:none; height:1px; background:linear-gradient(90deg, rgba(88,166,255,0.08), rgba(198,120,221,0.04)); margin:12px 0;">

        <h3 style="margin:6px 0; color:#e7f0ff;">📫 Contact</h3>
        <p style="color:#cfe5ff; font-size:13px; margin:6px 0 0;">
          🎓 <strong>BTech CSE</strong> @ Government College of Engineering, Keonjhar<br/>
          💼 Open to <strong>SDE roles</strong><br/>
          ✍️ Writing on <a href="https://medium.com/@anuragbehura" target="_blank" rel="noopener" style="color:#58a6ff;">Medium</a>
        </p>
      </div>

      <!-- Social links -->
      <div style="margin-top:12px; text-align:left; background:linear-gradient(180deg, rgba(255,255,255,0.01), rgba(255,255,255,0.01)); border-radius:12px; padding:12px;">
        <h4 style="margin:6px 0 8px; color:#e7f0ff;">🤝 Connect with Me</h4>
        <p style="margin:6px 0;">
          <a href="https://linkedin.com/in/anuragbehura" target="_blank" rel="noopener" style="margin-right:10px;"><img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="LinkedIn" height="30" width="40" /></a>
          <a href="https://twitter.com/_anuragbehura_" target="_blank" rel="noopener" style="margin-right:10px;"><img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="Twitter" height="30" width="40" /></a>
          <a href="https://medium.com/@anuragbehura" target="_blank" rel="noopener"><img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/medium.svg" alt="Medium" height="30" width="40" /></a>
        </p>
      </div>
    </td>
  </tr>
</table>

<!-- Blog posts placeholder (keep exact placeholder tags) -->
<div style="max-width:960px; margin-top:14px; text-align:left;">
  <h3 style="color:#e7f0ff;">📝 Latest Blog Posts</h3>
  <!-- BLOG-POST-LIST:START -->
  <!-- BLOG-POST-LIST:END -->
</div>

</div>

<!-- FOOTER -->
<div align="center" style="margin-top:18px; color:#9fb6e6; font-style:italic;">
  <p>⚡ "Building the future, one commit at a time"</p>
</div>
