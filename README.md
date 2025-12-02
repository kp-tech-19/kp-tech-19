<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Priyadharshini K — GitHub Profile</title>
  <style>
    :root{
      --orange:#FF7F00;
      --dark:#0F1720;
      --muted:#6B7280;
      --card-bg: rgba(255,255,255,0.03);
      --glass: rgba(255,255,255,0.04);
      --radius:16px;
      font-family: Inter, ui-sans-serif, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }
    html,body{height:100%;margin:0;background:linear-gradient(180deg,#0f1720 0%, #12222a 100%);color:#E6EEF3}
    .container{max-width:900px;margin:28px auto;padding:24px}
    .wave{width:100%;display:block;border-radius:12px;overflow:hidden}
    header{text-align:center;margin-top:8px}
    h1{font-size:38px;margin:10px 0}
    .gif{border-radius:12px;box-shadow:0 6px 24px rgba(0,0,0,0.6);display:inline-block}

    .card{background:linear-gradient(180deg, rgba(255,255,255,0.03), rgba(255,255,255,0.02));padding:20px;border-radius:var(--radius);margin-top:18px;box-shadow:0 8px 30px rgba(2,6,23,0.6)}
    .row{display:flex;gap:16px;align-items:center;flex-wrap:wrap}
    .badges img{margin:6px}

    .stats img{width:100%;max-width:360px;border-radius:12px}
    .trophies img{max-width:100%}

    .section-title{color:var(--orange);font-weight:600;margin:6px 0}
    .socials a{margin-right:12px;text-decoration:none}

    footer{margin-top:20px;text-align:center}

    /* responsive */
    @media (max-width:720px){
      .container{padding:14px}
      h1{font-size:28px}
    }
  </style>
</head>
<body>
  <div class="container">
    <!-- Top orange wave -->
    <img class="wave" src="https://capsule-render.vercel.app/api?type=waving&height=120&color=FF7F00&section=header" alt="orange-wave-top"/>

    <header>
      <h1>Hey there 👋</h1>
      <div class="gif">
        <img height="150" src="https://media.giphy.com/media/M9gbBd9nbDrOTu1Mqx/giphy.gif" alt="wave-gif" />
      </div>
    </header>

    <main class="card">
      <section>
        <h2 class="section-title">💫 About Me</h2>
        <p>I'm <strong>Priyadharshini K</strong>, an ECE Undergraduate passionate about technology, innovation, and real-world engineering.</p>
      </section>

      <section style="margin-top:14px">
        <h3 class="section-title">🌐 Socials</h3>
        <p class="socials">
          <a href="https://www.linkedin.com/in/priyadharshini-k-34076a304/" target="_blank" rel="noopener noreferrer">
            <img src="https://img.shields.io/badge/LinkedIn-0077B5?logo=linkedin&logoColor=white" alt="LinkedIn" />
          </a>
          <a href="mailto:priyadharshinik1901@gmail.com">
            <img src="https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white" alt="Email" />
          </a>
        </p>
      </section>

      <section style="margin-top:14px">
        <h3 class="section-title">💻 Tech Stack</h3>
        <div class="badges">
          <img src="https://img.shields.io/badge/c-00599C?style=for-the-badge&logo=c&logoColor=white" alt="C" />
          <img src="https://img.shields.io/badge/c%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" alt="C++" />
          <img src="https://img.shields.io/badge/java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
          <img src="https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" alt="Python" />
          <img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
          <img src="https://img.shields.io/badge/git-F05033?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
          <img src="https://img.shields.io/badge/github-121011?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
          <img src="https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=Arduino&logoColor=white" alt="Arduino" />
          <img src="https://img.shields.io/badge/Raspberry_Pi-C51A4A?style=for-the-badge&logo=Raspberry-Pi&logoColor=white" alt="Raspberry Pi" />
          <img src="https://img.shields.io/badge/Canva-00C4CC?style=for-the-badge&logo=Canva&logoColor=white" alt="Canva" />
        </div>
      </section>

      <section style="margin-top:18px">
        <h3 class="section-title">📊 GitHub Stats</h3>
        <div class="row stats">
          <img src="https://github-readme-stats.vercel.app/api?username=kp-tech-19&theme=radical&hide_border=false&include_all_commits=false&count_private=false" alt="GitHub Stats" />
          <img src="https://nirzak-streak-stats.vercel.app/?user=kp-tech-19&theme=radical&hide_border=false" alt="Streak Stats" />
        </div>
        <p style="margin-top:12px">Top languages and contributions:</p>
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=kp-tech-19&theme=radical&layout=compact" alt="Top Languages" style="max-width:420px;border-radius:10px" />
      </section>

      <section style="margin-top:18px">
        <h3 class="section-title">🏆 GitHub Trophies</h3>
        <img src="https://github-profile-trophy.vercel.app/?username=kp-tech-19&theme=radical&no-frame=false&no-bg=false&margin-w=4" alt="Trophies" style="max-width:100%" />
      </section>

      <section style="margin-top:18px">
        <h3 class="section-title">✍️ Random Dev Quote</h3>
        <img src="https://quotes-github-readme.vercel.app/api?type=vetical&theme=radical" alt="Quote" style="max-width:100%" />
      </section>

      <section style="margin-top:18px">
        <h3 class="section-title">🔝 Top Contributed Repo</h3>
        <img src="https://github-contributor-stats.vercel.app/api?username=kp-tech-19&limit=5&theme=radical&combine_all_yearly_contributions=true" alt="Top Repo" style="max-width:100%" />
      </section>

      <section style="margin-top:18px; text-align:center">
        <a href="https://visitcount.itsvg.in" target="_blank" rel="noopener noreferrer">
          <img src="https://visitcount.itsvg.in/api?id=kp-tech-19&icon=0&color=FF7F00" alt="visit count" />
        </a>
      </section>

    </main>

    <!-- Bottom orange wave -->
    <img class="wave" src="https://capsule-render.vercel.app/api?type=waving&color=FF7F00&height=120&section=footer" alt="orange-wave-bottom"/>

    <footer style="text-align:center;color:var(--muted);margin-top:8px;font-size:13px">Made with ❤️ &nbsp;•&nbsp; HTML • GitHub Profile</footer>

  </div>
</body>
</html>
