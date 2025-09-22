<!-- Profile Header -->
<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Inter&weight=600&size=28&duration=3000&pause=800&color=36BCF7&center=true&vCenter=true&multiline=true&repeat=true&width=800&height=120&lines=Hi%2C+I'm+Evindu+Ishen+%F0%9F%91%8B;Software+Engineering+Undergraduate;="Typing SVG">
</p>

<p align="center">
  <a href="mailto:ishenevindu@gmail.com"><img alt="Mail" src="https://img.shields.io/badge/Email-ishenevindu%40gmail.com-1a73e8?logo=gmail&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/evindu-ishen-a35a48303/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-evindu--ishen-0A66C2?logo=linkedin&logoColor=white"></a>
  <a href="https://github.com/EvinduIshen"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-EvinduIshen-181717?logo=github&logoColor=white"></a>
  <img alt="Visitors" src="https://komarev.com/ghpvc/?username=EvinduIshen&style=flat&color=36BCF7">
</p>

---

### 👨‍🎓 About Me
- 🇱🇰 Based in **Colombo, Sri Lanka**  
- 🎓 **BSc (Hons) in IT – Software Engineering**, **SLIIT** (2023–Present)  
- 💼 Seeking an **IT Internship** to apply full-stack & mobile dev skills in real projects  
- 🤝 I love **teamwork, solving practical problems, and building clean UIs**  
- 🌱 Exploring **AI/ML fundamentals** alongside core software engineering

---

### 🛠 Tech Stack
**Languages:** `Java` · `Python` · `C++` · `Kotlin` · `R`  
**Web:** `HTML` · `CSS` · `JavaScript` · `React.js` · `Node.js` · `Express.js` · `Vite` · `Tailwind CSS`  
**Mobile:** `Android (Kotlin, XML)`  
**Databases:** `MySQL` · `MongoDB (Mongoose)`  
**Tools:** `VS Code` · `IntelliJ IDEA` · `Android Studio` · `RStudio` · `Git/GitHub` · `Figma`  
**Cloud & Media:** `Cloudinary` · `Multer (file uploads)` · `JWT`

<p>
  <img src="https://skillicons.dev/icons?i=java,py,cpp,kotlin,js,ts,html,css,react,nodejs,express,mongodb,mysql,vite,tailwind,androidstudio,idea,vscode,git,figma&perline=10" height="44" />
</p>

---

### 🚀 Highlight Projects
#### 🛒 Life Fashion – E-commerce Platform
- 50+ product listings, auth, and admin management  
- Optimized Express.js + MongoDB queries → **~40% faster API responses**  
- Robust media pipeline with **Cloudinary + Multer** (100+ secure uploads)
- **Stack:** React, Vite, CSS, Node.js, Express.js, MongoDB, Mongoose, Cloudinary, Multer, JWT

#### 💸 Finance Tracker – Android App
- Secure accounts, categorized transactions, real-time expense management  
- **Dashboards** that help users budget **~40% more efficiently**  
- **Stack:** Kotlin, Android SDK, XML (App size < 20MB)

#### 🎉 Online Event Planning System
- Led development & integrated user feedback loops  
- Improved scheduling efficiency by **~30%** and reduced planning errors  
- **Stack:** Java, JSP, Servlets, MySQL

#### 🐾 Paws Shop (UI)
- Figma UI for mobile shopping flows  
- **Role:** UI/UX design and prototyping

---

### 📈 GitHub Analytics
<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com?user=EvinduIshen&theme=default" alt="GitHub Streak" />
</p>
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=EvinduIshen&show_icons=true&hide_title=true" alt="GitHub Stats"/>
</p>
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=EvinduIshen&layout=compact" alt="Top Languages"/>
</p>

---

### 🧩 What I’m Learning / Into
- 📱 **Mobile app development** (Kotlin + Android)  
- 🌐 **Full-stack web** with React + Node/Express  
- 🤖 **AI/ML basics** with Python & beginner-friendly tools  
- 🗣 **Presenting & communication**, **team collaboration**

---

### 🏅 Activities & Leadership
- 🇱🇰 National **Cadet** (2017–2020): leadership, coordination, discipline  
- 🦁 **Leo Club** of D. S. Senanayake College (2020–2022): community & service

---

### 📬 Reach Me
- **Email:** <a href="mailto:ishenevindu@gmail.com">ishenevindu@gmail.com</a>  
- **LinkedIn:** <a href="https://www.linkedin.com/in/evindu-ishen-a35a48303/">evindu-ishen-a35a48303</a>  
- **GitHub:** <a href="https://github.com/EvinduIshen">EvinduIshen</a>

---

### 🐍 Fun Animation – Contribution Snake
> Add this to a workflow file at: `.github/workflows/snake.yml` in **this** repo to generate the snake.
```yaml
name: Generate snake
on:
  schedule: [{ cron: "0 0 * * *" }]
  workflow_dispatch:
  push: { branches: ["main"] }
jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: EvinduIshen
          outputs: |
            dist/snake.svg
      - name: Push snake
        uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
