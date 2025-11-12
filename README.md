<h1 align="center">Hi 👋, I'm Adam ALLA</h1>
<h3 align="center">🧠 Computer application development student at Al Kendi (BTS center)</h3>

---

### 🚀 About Me
💡 I create themed desktop apps to stay consistent  
🎯 Passionate Flutter/Dart developer – Modern and High-Performance Mobile Applications  
🌀 Experienced in UI/UX design, API integration, and building scalable mobile apps  
💻 You can see my portfolio here 👉 [https://bit.ly/3LftXwp](https://bit.ly/3LftXwp)

---

<p align="center">
  <img src="https://www.animatedimages.org/data/media/562/animated-line-image-0184.gif" width="100%"/>
</p>

---

### 🏆 GitHub Trophies
<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=YOUR_GITHUB_USERNAME&theme=algolia&no-frame=true&no-bg=true&margin-w=4"/>
</p>

---

### 🌐 Socials
<p align="center">
  <a href="https://discord.com" target="blank"><img src="https://skillicons.dev/icons?i=discord" alt="discord"/></a>
  <a href="https://instagram.com" target="blank"><img src="https://skillicons.dev/icons?i=instagram" alt="instagram"/></a>
  <a href="https://linkedin.com" target="blank"><img src="https://skillicons.dev/icons?i=linkedin" alt="linkedin"/></a>
  <a href="mailto:example@gmail.com" target="blank"><img src="https://skillicons.dev/icons?i=gmail" alt="email"/></a>
</p>

---

### 💻 Tech Stack
<p align="center">
  <img src="https://skillicons.dev/icons?i=c,cs,dart,python,php,java,js,html,css,firebase,flutter,django,bootstrap,mysql,sqlite,git,github,photoshop,premiere,canva,wordpress,docker,cloudflare" />
</p>

---

### 📊 GitHub Stats
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=YOUR_GITHUB_USERNAME&show_icons=true&theme=tokyonight" alt="stats"/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=YOUR_GITHUB_USERNAME&theme=tokyonight" alt="streak"/>
</p>

---

### ✍️ Random Dev Quote
<p align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight" alt="quote"/>
</p>

---

### 🔝 Top Contributed Repo
<p align="center">
  <img src="https://github-contributor-stats.vercel.app/api?username=YOUR_GITHUB_USERNAME&limit=5&theme=tokyonight&combine_all_yearly_contributions=true"/>
</p>

---

### 🐍 Snake animation
name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * *"   # runs daily at 00:00 UTC (tweak as you want)
  workflow_dispatch:

permissions:
  contents: write        # مهم: باش يكتب الملف الناتج فالريبو

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - name: Checkout
        uses: actions/checkout@v4

      - name: Generate snake SVG
        # use the Platane action (svg-only variant)
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: YOUR_GITHUB_USERNAME
          # output path relative to repo root:
          output: output/github-contribution-grid-snake.svg
          palette: github-dark   # choices: github, github-dark, github-light (tweak)
          snake_color: "#ffd600"
          dot_color: "#00aaff"

---

<p align="center">
  <img src="https://www.animatedimages.org/data/media/562/animated-line-image-0184.gif" width="100%"/>
</p>

