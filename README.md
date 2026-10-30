<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Press+Start+2P&size=22&duration=3000&pause=800&color=39FF14&background=0D0D1A00&center=true&vCenter=true&width=700&height=70&lines=PLAYER+1+READY!;HI%2C+I'M+NanditoDitama;FULL+STACK+DEVELOPER;INSERT+COIN+TO+CONTINUE" alt="Typing SVG" />

<br>

![Followers](https://img.shields.io/github/followers/NanditoDitama?style=for-the-badge&logo=github&color=00e5ff&labelColor=0d0d1a)

</div>

---

<h2 align="center">
  <img src="https://img.shields.io/badge/🎮_PLAY_GAMES-0d0d1a?style=for-the-badge&title_color=39ff14" alt="Play Games"/>
</h2>

| Game | Mainkan |
|------|---------|
| 🐍 **Pixel Snake** (8-bit, buatan sendiri) | [**▶ MAIN SEKARANG**](https://NanditoDitama.github.io/pixel-snake/) |
| ♟️ **Catur via Issue** | [**▶ Buat Langkah**](https://NanditoDitama.github.io/pixel-snake/csp/) |
| 👾 **Space Invaders (web)** | [**▶ Main**](https://NanditoDitama.github.io/pixel-snake/csp/) |
| 🏓 **Pong (web)** | [**▶ Main**](https://NanditoDitama.github.io/pixel-snake/csp/) |

---

<h2 align="center">
  <img src="https://img.shields.io/badge/🕹️_STATUS_PLAYER-0d0d1a?style=for-the-badge&title_color=39ff14" alt="Status Player"/>
</h2>

<div align="center">


<img src="https://streak-stats.demolab.com?user=NanditoDitama&theme=synthwave&hide_border=true&background=0d0d1a" height="170" />

</div>

---

<h2 align="center">
  <img src="https://img.shields.io/badge/⚔️_INVENTORY_(TECH_STACK)-0d0d1a?style=for-the-badge&title_color=39ff14" alt="Tech Stack"/>
</h2>

<div align="center">

<p>
  <img src="https://img.shields.io/badge/C++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white" />
  <img src="https://img.shields.io/badge/Qt-%2341CD52.svg?style=for-the-badge&logo=qt&logoColor=white" />
  <img src="https://img.shields.io/badge/Flutter-%2302569B.svg?style=for-the-badge&logo=flutter&logoColor=white" />
  <img src="https://img.shields.io/badge/CMake-%23008FBE.svg?style=for-the-badge&logo=cmake&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-%23F05032.svg?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-%233776AB.svg?style=for-the-badge&logo=python&logoColor=white" />
</p>

</div>

---


<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/NanditoDitama/NanditoDitama/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/NanditoDitama/NanditoDitama/output/github-snake.svg" />
  <img alt="snake animation" src="https://raw.githubusercontent.com/NanditoDitama/NanditoDitama/output/github-snake-dark.svg" />
</picture>

</div>

---

<h2 align="center">
  <img src="https://img.shields.io/badge/🔗_CONNECT-0d0d1a?style=for-the-badge&title_color=39ff14" alt="Connect"/>
</h2>

<div align="center">

[![Instagram](https://img.shields.io/badge/Instagram-ff00aa?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/NanditoDitama)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/NanditoDitama)
[![Email](https://img.shields.io/badge/Email-ea4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:nanditoditama@gmail.com)

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=100&section=footer" width="100%" />

</div>

<!--
===== SETUP SNAKE (animasi ular dari kontribusi) =====
Buat file: .github/workflows/snake.yml di repo NanditoDitama/NanditoDitama

name: Generate Snake
on:
  schedule: [{cron: "0 */12 * * *"}]
  workflow_dispatch:
  push: {branches: [main]}
permissions:
  contents: write
jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-snake.svg
            dist/github-snake-dark.svg?palette=github-dark
      - uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
-->
