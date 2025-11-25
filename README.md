<!doctype html>
<html>
<head>
<meta charset="utf-8"/>
<title>Neon Welcome</title>
<style>
  :root { --pink: #ff2fa1; --blue: #00e0ff; --bg:#070617; }
  body { background: var(--bg); display:flex; align-items:center; justify-content:center; height:100vh; margin:0; font-family: 'Segoe UI', Roboto, Arial; }
  .wrap { color:#fff; font-weight:800; font-size:64px; letter-spacing:2px; filter:drop-shadow(0 0 12px rgba(255,47,161,0.6)); }
  .line { display:inline-block; white-space:nowrap; overflow:hidden; vertical-align:middle; }
  .char { display:inline-block; transform:translateY(10px); opacity:0; }
  /* typing entrance for each char, sequence created by increasing animation-delay */
  @keyframes typeIn { 0% { opacity:0; transform:translateY(10px); } 60% { opacity:1; transform:translateY(0); } 100% { opacity:1; transform:translateY(0);} }
  @keyframes fadeOut { 0%{opacity:1} 80%{opacity:1} 100%{opacity:0} }

  /* cycle: 6s */
  .welcome .char { animation: typeIn 0.45s ease forwards; }
  .name    .char { animation: typeIn 0.45s ease forwards; }

  /* schedule sequence: welcome 0s..3s, name 3s..6s */
  /* we define delays for each char programmatically via style attribute below */

  /* hide group when not active by applying fadeOut timed */
  .welcome { animation: fadeOut 6s linear infinite; animation-delay:0s; }
  .name    { animation: fadeOut 6s linear infinite; animation-delay:3s; }

  /* color alternation (pink/blue) */
  .pink { color:var(--pink); text-shadow:0 0 8px rgba(255,47,161,0.8); }
  .blue { color:var(--blue); text-shadow:0 0 12px rgba(0,224,255,0.8); }
</style>
</head>
<body>
  <div class="wrap">
    <span class="line welcome" aria-hidden="true">
      <!-- WELCOME, set incremental delays -->
      <span class="char pink" style="animation-delay:0s">W</span>
      <span class="char blue" style="animation-delay:0.12s">E</span>
      <span class="char pink" style="animation-delay:0.24s">L</span>
      <span class="char blue" style="animation-delay:0.36s">C</span>
      <span class="char pink" style="animation-delay:0.48s">O</span>
      <span class="char blue" style="animation-delay:0.60s">M</span>
      <span class="char pink" style="animation-delay:0.72s">E</span>
    </span>

    <span class="line name" aria-hidden="true" style="margin-left:12px;">
      <!-- G a b r i e l   R o k s -->
      <span class="char blue" style="animation-delay:3.00s">G</span>
      <span class="char pink" style="animation-delay:3.12s">a</span>
      <span class="char blue" style="animation-delay:3.24s">b</span>
      <span class="char pink" style="animation-delay:3.36s">r</span>
      <span class="char blue" style="animation-delay:3.48s">i</span>
      <span class="char pink" style="animation-delay:3.60s">e</span>
      <span class="char blue" style="animation-delay:3.72s">l</span>
      <span style="display:inline-block;width:16px"></span>
      <span class="char pink" style="animation-delay:3.96s">R</span>
      <span class="char blue" style="animation-delay:4.08s">o</span>
      <span class="char pink" style="animation-delay:4.20s">k</span>
      <span class="char blue" style="animation-delay:4.32s">s</span>
    </span>
  </div>
</body>
</html>

<p align="center">
  <strong>Systems Development Student (SENAI)</strong>  
  <br>
  Developer with experience as a <strong>Freelancer at ServiLar</strong>, working on building and maintaining digital solutions.  
  <br>
  Passionate about technology, backend engineering, and automation.  
</p>

---

<img src="https://github.com/GabrielRoks/GabrielRoks/blob/main/assets/cyberpunk-banner.gif" width="100%" />

---

# 🚀 Tech Stack & Skills

## 🧩 Languages & Tools

<div align="center">

<!-- BADGES (Cyberpunk Style) -->
<img src="https://img.shields.io/badge/Node.js-0d0d0d?style=for-the-badge&logo=node.js&logoColor=00ffcc" />
<img src="https://img.shields.io/badge/JavaScript-0d0d0d?style=for-the-badge&logo=javascript&logoColor=ff0099" />
<img src="https://img.shields.io/badge/Python-0d0d0d?style=for-the-badge&logo=python&logoColor=00aaff" />
<img src="https://img.shields.io/badge/SQL-0d0d0d?style=for-the-badge&logo=postgresql&logoColor=00eaff" />
<img src="https://img.shields.io/badge/Git-0d0d0d?style=for-the-badge&logo=git&logoColor=ff0066" />
<img src="https://img.shields.io/badge/GitHub-0d0d0d?style=for-the-badge&logo=github&logoColor=bb00ff" />

</div>

---

# ⚙️ Stats (Neon Mode)

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=GabrielRoks&show_icons=true&theme=tokyonight&hide_border=true&icon_color=ff00ff&title_color=00eaff&text_color=cccccc" />

<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=GabrielRoks&layout=compact&theme=tokyonight&hide_border=true&title_color=00eaff&text_color=cccccc" />

</div>

---

# 🏆 Certifications

### 🎓 **Back-End Node.js Immersion — Alura + Gemini**
- REST APIs with Node.js & Express  
- Database integration  
- Deploy & versioning  
- Practical backend projects using JavaScript  

---

# 📌 About Me

- 🎓 Systems Development Student — SENAI  
- 💼 Freelancer at **ServiLar**  
- 👨‍💻 Backend developer in progress (Node.js & Python)  
- 🌱 English level **B1**  
- 🔥 Always experimenting with new technologies  
- 💡 Interested in backend, automation, and best practices  

---

# 🔗 Contact

- 🔵 **LinkedIn:**  
  https://www.linkedin.com/in/gabriel-roks-gomes-rodrigues  

- 📧 **Email:**  
  **gabrielrokssz@gmail.com**

---

<h3 align="center" style="color:#00eaff;">✨ Thanks for stopping by — Stay Neon! ✨</h3>
