<!-- GANTI: USERNAME = username GitHub kamu, NAMA = namamu -->

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Press+Start+2P&size=22&duration=3000&pause=800&color=39FF14&background=0D0D1A&center=true&vCenter=true&width=700&height=70&lines=PLAYER+1+READY!;HI%2C+I'M+NAMA;FULL+STACK+DEVELOPER;INSERT+COIN+TO+CONTINUE" alt="Typing SVG" />

<br>

![Profile Views](https://komarev.com/ghpvc/?username=USERNAME&label=PLAYER+VISITS&color=ff00aa&style=for-the-badge)
![Followers](https://img.shields.io/github/followers/USERNAME?style=for-the-badge&logo=github&color=00e5ff&labelColor=0d0d1a)

</div>

---

## 🎮 PLAY GAMES

| Game | Mainkan |
|------|---------|
| 🐍 **Pixel Snake** (8-bit, buatan sendiri) | [**▶ MAIN SEKARANG**](https://USERNAME.github.io/pixel-snake/) |
| ♟️ **Catur via Issue** | [**▶ Buat Langkah**](https://github.com/timburgan/timburgan/issues/new?title=chess%7Cnew&body=Just+push+%27Submit+new+issue%27.) |
| 👾 **Space Invaders (web)** | [**▶ Main**](https://freeinvaders.org/) |
| 🏓 **Pong (web)** | [**▶ Main**](https://playpong.netlify.app/) |

> 💡 File `index.html` game Snake ada di file terpisah (`pixel-snake.html`). Cara pasang ada di bagian bawah.

---

## 🕹️ STATUS PLAYER

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=USERNAME&show_icons=true&theme=synthwave&hide_border=true&bg_color=0d0d1a&title_color=39ff14&icon_color=ff00aa&text_color=ffffff" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=USERNAME&layout=compact&theme=synthwave&hide_border=true&bg_color=0d0d1a&title_color=39ff14&text_color=ffffff" />

<br>

<img src="https://streak-stats.demolab.com?user=USERNAME&theme=synthwave&hide_border=true&background=0d0d1a" height="170" />

</div>

---

## ⚔️ INVENTORY (TECH STACK)

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-f7df1e?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178c6?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232a?style=for-the-badge&logo=react&logoColor=61dafb)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776ab?style=for-the-badge&logo=python&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777bb4?style=for-the-badge&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479a1?style=for-the-badge&logo=mysql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ed?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-f05032?style=for-the-badge&logo=git&logoColor=white)

</div>

---

## 🐍 CONTRIBUTION SNAKE

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/USERNAME/USERNAME/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/USERNAME/USERNAME/output/github-snake.svg" />
  <img alt="snake animation" src="https://raw.githubusercontent.com/USERNAME/USERNAME/output/github-snake-dark.svg" />
</picture>

</div>

---

## 📜 QUEST LOG

```text
> NAMA@github:~$ whoami
  Developer yang suka ngoding, ngopi, dan main game retro.

> NAMA@github:~$ cat now.txt
  🔭 Lagi ngerjain  : proyek keren berikutnya
  🌱 Lagi belajar   : hal baru setiap hari
  💬 Tanya aku soal : JavaScript, Python, web dev
  ⚡ Fun fact       : bug pertamaku masih hidup sampai sekarang

> NAMA@github:~$ _
```

## 🔗 CONNECT

<div align="center">

[![Instagram](https://img.shields.io/badge/Instagram-ff00aa?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/USERNAME)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/USERNAME)
[![Email](https://img.shields.io/badge/Email-ea4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:email@kamu.com)

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=100&section=footer" width="100%" />

</div>

<!--
===== SETUP SNAKE (animasi ular dari kontribusi) =====
Buat file: .github/workflows/snake.yml di repo USERNAME/USERNAME

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
