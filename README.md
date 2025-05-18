<h2 align="center">Hey there 👋, I'm Rudrika Panigrahi</h2>

<p align="center">
  🌸Full Stack Dev | 🎨 Designer by Passion | 💻 B.Tech CSE @ KIIT University <br>
  ✨ Making interfaces that feel like magic ✨
</p>

---

### 🧠 About Me

- 🎓 Currently a 2nd-year B.Tech student in Computer Science at KIIT University
- 🌐 Frontend Developer & aspiring UI/UX designer
- 🔍 Exploring **ReactJS**, **TailwindCSS**, and **web animations**
- 🖼 I love creating visually soothing and user-friendly designs
- 📷 Outside tech: I enjoy **painting**, **reading**, **music**, and **photography**

---

### 🛠 Tech Stack

<div align="center">
  <img src="https://skillicons.dev/icons?i=html,css,js,react,tailwind,bootstrap,figma,vscode,github" />
</div>

---

### 🌟 My Projects

| Project | Tech Used | Description |
|--------|------------|-------------|
| 🎯 **Portfolio** | ReactJS, HTML, CSS, JS |A clean personal website to showcase who I am, what I build, and where I’m going. |
| 🎯 **EzzCook** | ReactJS, HTML, CSS, JS | A recipe app for lazy chefs – minimalist, clean & responsive |

---
## GitHub Stata

name: Generate Datas
on:
  schedule: # execute every 12 hours
    - cron: "* */12 * * *"
  workflow_dispatch:
jobs:
  build:
    name: Jobs to update datas
    runs-on: ubuntu-latest
    steps:
      # Snake Animation
      - uses: Platane/snk@master
        id: snake-gif
with:
          github_user_name: rudrika08
          svg_out_path: dist/github-contribution-grid-snake.svg
      - uses: crazy-max/ghaction-github-pages@v2.1.3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

  ---
  
### 📬 Let's Connect!

<p align="center">
  <a href="www.linkedin.com/in/rudrika-panigrahi-6085b5268" target="_blank">💼 LinkedIn</a> •
  <a href="mailto:rudrika08.panigrahi@gmail.com">📧 Email</a> •
  <a href="https://portfolio-rp-topaz.vercel.app/" target="_blank">🌐 Portfolio</a>
</p>

---

> *"Design is the soul, code is the structure. Web development is where both meet to tell a story"*



<!--
**rudrika08/rudrika08** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
