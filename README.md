
<!DOCTYPE html>
<html lang="ar" dir="ltr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Abdulrhman Mohamed | Profile README</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Tajawal:wght@500;700;900&family=Montserrat:wght@500;600&display=swap');
    body {
      font-family: 'Tajawal', 'Montserrat', Arial, sans-serif;
      background: #20232A;
      color: #e2eaff;
      margin: 0;
      padding: 0;
    }
    .container {
      max-width: 870px;
      margin: 30px auto 32px auto;
      background: rgba(37,41,54,0.96);
      border-radius: 23px;
      box-shadow: 0 12px 38px #07101729;
      padding: 32px 20px 20px 20px;
      position: relative;
      overflow: hidden;
    }
    .badge-right {
      position: absolute;
      right: 22px;
      top: 18px;
    }
    .contact-row {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px 12px;
      margin: 14px 0 26px 0;
    }
    .contact-row a {
      text-decoration: none;
      font-size: 1.07em;
      color: #64b5f6;
      font-weight: 600;
      transition: color 0.3s;
      border-radius: 9px;
      display: flex;
      align-items: center;
      gap: 6px;
      padding: 6px 13px 6px 11px;
      background: #222a36ed;
      box-shadow: 0 2px 11px #20252a33;
    }
    .contact-row a:hover {
      color: #fff;
      background: linear-gradient(90deg, #60a9e6 0%, #61dafb 100%);
    }
    .hero {
      margin-top: 18px;
      margin-bottom: 12px;
      text-align: center;
    }
    .hero-title {
      margin-bottom: 0.1em;
      font-family: 'Montserrat', 'Tajawal', Arial, sans-serif;
      font-size: 2.4rem;
      font-weight: 900;
      letter-spacing: 2px;
      color: #61dafb;
    }
    .subtitle {
      font-size: 1.13rem;
      line-height: 1.5;
      color: #eee;
      font-weight: 500;
      max-width: 660px;
      margin: 0 auto 1.4em auto;
    }
    .gradient-divider {
      width: 96%;
      height: 7px;
      border: none;
      margin: 28px auto 30px auto;
      border-radius: 99px;
      background: linear-gradient(90deg,#61dafb, #3BA4D8 40%, #66ffcc 80% );
      opacity:0.35;
      box-shadow: 0 2px 9px #2a99a840;
    }
    .tech-stack-card {
      margin: 0 auto 34px auto;
      background: #23272f;
      border-radius: 18px;
      box-shadow: 0 4px 12px #0001;
      padding: 28px 6px 18px 6px;
      width: 98%;
      max-width: 720px;
      text-align: center;
      display: flex;
      flex-direction: column;
      gap: 0.6em;
      align-items: center;
    }
    .tech-stack-card h2 {
      color: #61dafb;
      margin-bottom: 19px;
      font-family: 'Montserrat', sans-serif;
      font-size: 1.25em;
      letter-spacing: 2px;
      text-shadow: 0 3px 9px #061f3380;
    }
    .badges {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 11px;
      margin-bottom: 2px;
    }
    .badges img {
      filter: drop-shadow(0 1px 3px #061f3344);
      margin-bottom: 3px;
    }
    /* Github and projects section */
    .section-title {
      text-align: center;
      color: #90caf9;
      font-size: 1.2em;
      margin: 28px 0 10px 0;
      font-family: 'Montserrat', 'Tajawal', Arial, sans-serif;
      letter-spacing: 1.1px;
    }
    .github-stats {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 22px;
    }
    .github-stats img {
      border-radius: 12px;
      margin-bottom: 9px;
      margin-top: 5px;
      box-shadow: 0 2px 12px #0f182244;
    }
    .activity-graph {
      text-align: center;
      margin: 14px auto;
    }
    .activity-graph img {
      border-radius: 9px;
      border: 1px solid #282e39;
      box-shadow: 0 2px 10px #1c416722;
      width: 95%;
      max-width: 820px;
      min-width: 320px;
    }
    .projects-row {
      display: flex;
      flex-wrap: wrap;
      gap: 18px;
      justify-content: center;
      margin-bottom: 7px;
    }
    .projects-row img {
      border-radius: 16px;
      min-width: 250px;
      max-width: 343px;
      height: 120px;
      object-fit: cover;
      box-shadow: 0 3px 18px #0821422f;
    }
    .more-btn {
      padding: 9px 28px;
      background: linear-gradient(90deg,#61dafb 10%, #60a9e6 90%);
      color: #273043;
      font-weight: bold;
      font-size: 1.09em;
      border-radius: 14px;
      box-shadow: 0 2px 16px #67cfec52;
      border: none;
      margin: 12px auto 7px auto;
      display: block;
      cursor: pointer;
      transition: background 0.2s, color 0.18s;
      letter-spacing: 1.2px;
    }
    .more-btn:hover {
      background: linear-gradient(90deg,#43e3c3,#61dafb 70%);
      color: #212934;
    }
    @media (max-width: 630px){
      .container {
        padding: 14px 0 9px 0;
      }
      .projects-row img {
        max-width: 100%;
        min-width: 99px;
        height: 92px;
        margin: 0 auto;
      }
    }
  </style>
</head>
<body>
<div class="container">
  <span class="badge-right">
    <img src="https://visitor-badge.laobi.icu/badge?page_id=AbdulrhmanM0hamed.AbdulrhmanM0hamed" alt="Visitor Count"/>
  </span>
  <!-- Typing SVG header -->
  <div class="hero">
    <a href="https://git.io/typing-svg">
      <img src="https://readme-typing-svg.herokuapp.com/?lines=Hello,+There!+👋;I'm+Abdulrhman+Mohamed...;Flutter+Developer+|+Tech+Entrepreneur&center=true&size=30" alt="Typing SVG Animated Header"/>
    </a>
    <h1 class="hero-title">Abdulrhman Mohamed</h1>
    <div class="subtitle">👋 Passionate <b>Flutter Developer</b> with 2.5+ years experience building scalable, elegant cross-platform apps.<br>
      💼 Founder of <a style="color:#4dd6a1;font-weight:700;text-decoration:none;" href="https://drkomy.com">drKomy Software Solutions</a> — turning ideas into real products.<br>
      🎓 BSc in Software Engineering · 🚀 Eager to learn &amp; deliver impactful solutions.
    </div>
  </div>
  
  <div class="contact-row">
    <a href="https://www.linkedin.com/in/abdulrhman-mohamed-080238251/" title="LinkedIn Profile">
      <img width="24" src="images/linkedin.svg" alt="LinkedIn"> LinkedIn
    </a>
    <a href="https://drkomy.com" title="drKomy Team">
      <img width="24" src="images/drkomy.svg" alt="drKomy"> drKomy
    </a>
    <a href="mailto:abdulrhman.mohamed.it@gmail.com" title="Email">
      <img width="24" src="images/email.svg" alt="Email"> Email
    </a>
  </div>

  <hr class="gradient-divider"/>

  <!-- Tech Stack Card -->
  <div class="tech-stack-card">
    <h2>🛠️ Tech Stack &amp; Tools</h2>
    <div class="badges">
      <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" height="32" alt="Flutter"/>
      <img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white" height="32" alt="Dart"/>
      <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" height="32" alt="Firebase"/>
      <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white" height="32" alt="Supabase"/>
      <img src="https://img.shields.io/badge/BLoC-21DEF7?style=for-the-badge&logo=bloc&logoColor=white" height="32" alt="BLoC"/>
      <img src="https://img.shields.io/badge/Clean%20Architecture-1B2227?style=for-the-badge&logo=semanticweb&logoColor=white" height="32" alt="Clean Architecture"/>
      <img src="https://img.shields.io/badge/REST%20API-011627?style=for-the-badge&logo=apollographql&logoColor=white" height="32" alt="REST API"/>
      <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" height="32" alt="Postman"/>
      <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" height="32" alt="Figma"/>
      <img src="https://img.shields.io/badge/Git-E44C30?style=for-the-badge&logo=git&logoColor=white" height="32" alt="Git"/>
      <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" height="32" alt="GitHub"/>
      <img src="https://img.shields.io/badge/VSCode-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white" height="32" alt="VS Code"/>
      <img src="https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white" height="32" alt="Android"/>
      <img src="https://img.shields.io/badge/iOS-000000?style=for-the-badge&logo=apple&logoColor=white" height="32" alt="iOS"/>
      <img src="https://img.shields.io/badge/Google%20Maps-4285F4?style=for-the-badge&logo=googlemaps&logoColor=white" height="32" alt="Google Maps"/>
    </div>
  </div>

  <div class="section-title">📈 GitHub Stats</div>
  <div class="github-stats">
    <img width="47%" src="https://github-readme-stats.vercel.app/api?username=AbdulrhmanM0hamed&show_icons=true&theme=react&border_color=61dafb&hide_border=true" alt="github stats"/>
    <img width="47%" src="https://streak-stats.demolab.com?user=AbdulrhmanM0hamed&theme=react&border=61dafb&hide_border=true" alt="Github Streak"/>
  </div>

  <div class="github-stats">
    <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=AbdulrhmanM0hamed&layout=compact&theme=react&hide_border=true&langs_count=8&border_color=61dafb" alt="Top Languages" />
  </div>
  <div class="activity-graph">
    <img src="https://github-readme-activity-graph.vercel.app/graph?username=AbdulrhmanM0hamed&theme=react-dark&bg_color=20232a&hide_border=true" alt="Activity Graph" />
  </div>

  <hr class="gradient-divider"/>

  <div class="section-title">🚀 Highlighted Projects</div>

  <div class="projects-row">
    <a href="https://github.com/AbdulrhmanM0hamed/Reef-Coffe">
      <img src="https://github-readme-stats.vercel.app/api/pin/?username=AbdulrhmanM0hamed&repo=Reef-Coffe&theme=react&border_color=61dafb&border_radius=10" alt="Reef-Coffe"/>
    </a>
    <a href="https://github.com/AbdulrhmanM0hamed/beat_elslam">
      <img src="https://github-readme-stats.vercel.app/api/pin/?username=AbdulrhmanM0hamed&repo=beat_elslam&theme=react&border_color=61dafb&border_radius=10" alt="beat_elslam"/>
    </a>
    <a href="https://github.com/AbdulrhmanM0hamed/Beautilly">
      <img src="https://github-readme-stats.vercel.app/api/pin/?username=AbdulrhmanM0hamed&repo=Beautilly&theme=react&border_color=61dafb&border_radius=10" alt="Beautilly"/>
    </a>
    <a href="https://github.com/AbdulrhmanM0hamed/Web_Dashboard_Supabase">
      <img src="https://github-readme-stats.vercel.app/api/pin/?username=AbdulrhmanM0hamed&repo=Web_Dashboard_Supabase&theme=react&border_color=61dafb&border_radius=10" alt="Web_Dashboard_Supabase"/>
    </a>
  </div>

  <a href="https://github.com/AbdulrhmanM0hamed?tab=repositories" title="Show More Repos">
    <button class="more-btn">🔎 Show More 🔍</button>
  </a>
</div>
</body>
</html>

