- uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.shohjahonsherzodov }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:     A preset of color, one of [github, github-dark, github-light]
    #  - color_snake: Color of the snake
    #  - color_dots:  Coma separated list of dots color.
    #                 The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                 Exactly 5 colors are expected.
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="github-snake.svg" />
  <img alt="github-snake" src="github-snake.svg" />
</picture>

<h1 align="center">👋 Salom, men Shohjahonman!</h1>


<p align="center">
  <img src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" width="200">
</p>

<p align="center">
  <a href="https://t.me/shohjahon2011_blog">
    <img src="https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram Badge"/>
  </a>
  <a href="https://instagram.com/shoh_coder">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram Badge"/>
  </a>
  <a href="https://youtube.com/@shoh-coder">
    <img src="https://img.shields.io/badge/Youtube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube Badge"/>
  </a>
</p>

---

## 👨‍💻 Men haqimda

Salom! Men **Sherzodov Shohjahon**, FULL STACK WEB DEVELOPER. 

---

## 🛠 Biladigan texnologiyalarim

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

## 📊 GitHub statistikam

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=shohjahonsherzodov&show_icons=true&theme=tokyonight" width="47%">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=shohjahonsherzodov&theme=tokyonight" width="47%">
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=shoh-coder&layout=compact&theme=tokyonight" width="40%">
</p>

---

## 🚀 Mening loyihalarim
<table>
  <tr>
    <td align="center">
      <img src="https://via.placeholder.com/300x180.png?text=Django+Blog" width="300"/><br>
      <strong>Django Blog</strong><br>
      Django asosida yaratilgan blog sayt, foydalanuvchi post qo‘shadi, tahrirlaydi, o‘chiradi.
      <br><br>
      <a href="https://github.com/shoh-coder/django-blog">
        <img src="https://img.shields.io/badge/View%20on%20GitHub-24292E?style=for-the-badge&logo=github&logoColor=white">
      </a>
    </td>
    <td align="center">
      <img src="https://via.placeholder.com/300x180.png?text=Quiz+Bot" width="300"/><br>
      <strong>Python Quiz Bot</strong><br>
      Telegram orqali ishlaydigan test bot, 50 ta Python savollar bilan.
      <br><br>
      <a href="https://github.com/shoh-coder/python-quiz-bot">
        <img src="https://img.shields.io/badge/View%20on%20GitHub-24292E?style=for-the-badge&logo=github&logoColor=white">
      </a>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://via.placeholder.com/300x180.png?text=Ustoz+Bot" width="300"/><br>
      <strong>Ustoz Bot</strong><br>
      O‘quvchilarga Python darslarini interaktiv o‘rgatadigan Telegram bot.
      <br><br>
      <a href="https://github.com/shoh-coder/ustoz-bot">
        <img src="https://img.shields.io/badge/View%20on%20GitHub-24292E?style=for-the-badge&logo=github&logoColor=white">
      </a>
    </td>
    <td align="center">
      <img src="https://via.placeholder.com/300x180.png?text=Portfolio" width="300"/><br>
      <strong>Portfolio Website</strong><br>
      O‘z faoliyatingizni ko‘rsatadigan shaxsiy portfolio sayt.
      <br><br>
      <a href="https://github.com/shoh-coder/portfolio-website">
        <img src="https://img.shields.io/badge/View%20on%20GitHub-24292E?style=for-the-badge&logo=github&logoColor=white">
      </a>
    </td>
  </tr>
</table>
