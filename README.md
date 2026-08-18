<div align="center">

# Hi there, I'm Dhyan S Shetty 👋

<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=500&size=24&duration=3000&pause=900&color=6C63FF&center=true&vCenter=true&multiline=true&width=650&height=90&lines=Information+Science+Engineering+Student;Computer+Vision+%26+AI+Systems+Builder;Full-Stack+%2B+DevOps+Enthusiast;Turning+Ideas+Into+Production-Ready+Software" alt="Typing SVG" />

<p>
  <a href="https://linkedin.com/in/dhyan-shetty5" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:dhyanshetty7@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://github.com/Dhyan5" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

<img src="https://komarev.com/ghpvc/?username=Dhyan5&label=Profile%20Views&color=6c63ff&style=flat" alt="Profile views" />

</div>

<br/>

## 🎯 About Me

- 🎓 B.E. in **Information Science and Engineering**, Sahyadri College of Engineering and Management *(2023 – 2027)*
- 🩺 Building **HridyaDarpan** — an AI cardiovascular health SaaS with a real-time 3D Digital Heart Twin
- 🧭 Building **Software Archaeologist** — a static-analysis tool that helps developers understand legacy codebases
- ⚖️ Built **VakeelAI** — a legal-tech assistant that makes the Indian Penal Code and constitutional rights searchable in plain English
- 🎨 **Design Lead** at ISDC (Innovex Student Developer Community) — leading a team of 15
- 💬 Ask me about Python, computer vision, systems/resource monitoring, or full-stack development

<br/>

## 🛠️ Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,cpp,js,html,css,flask,opencv,webgl,threejs,linux,docker,githubactions,aws,git,github,vscode,figma,postman&theme=dark&perline=9" alt="Tech stack icons" />
</p>

<br/>

## 🚀 Featured Projects

### 🫀 HridyaDarpan — AI Cardiovascular Health SaaS
Enterprise cardiac risk-prediction platform combining Framingham and ASCVD models on XGBoost/LightGBM (74% prediction accuracy), a real-time WebGL 3D Digital Heart Twin running at 60 FPS, multi-agent clinical consultation workflows, and Google Maps Platform integration for emergency-care routing — cutting patient routing time by 35%.
`Python` `XGBoost` `LightGBM` `WebGL` `Google Maps API`

### 🔎 Software Archaeologist — Enterprise Repository Analysis
Automated codebase analysis tool for legacy, undocumented repositories using static analysis and AST symbol parsing, processing 50k+ lines of code. Builds dynamic dependency graphs and performs Git-history archaeology to surface historical context, speeding up developer onboarding by 40%.
`Python` `AST` `Static Analysis` `Git`

### ⚖️ VakeelAI — Legal Tech & Knowledge Assistant
Virtual legal intelligence platform that democratizes access to the Indian Penal Code (Bharatiya Nyaya Sanhita) and constitutional rights, serving 500+ user queries through natural-language statute search — a 45% reduction in search latency — plus automated legal document summaries.
`NLP` `Flask` `Search`

<br/>

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Dhyan5&show_icons=true&theme=radical&hide_border=true&count_private=true" height="165" alt="Dhyan's GitHub stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Dhyan5&layout=compact&theme=radical&hide_border=true" height="165" alt="Top languages" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Dhyan5&theme=radical&hide_border=true" alt="GitHub streak" />
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=Dhyan5&theme=radical&no-frame=true&row=1&column=6" alt="GitHub trophies" />
</p>

<br/>

## 🐍 Contribution Snake

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Dhyan5/Dhyan5/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Dhyan5/Dhyan5/output/github-contribution-grid-snake.svg" />
    <img alt="Contribution snake animation" src="https://raw.githubusercontent.com/Dhyan5/Dhyan5/output/github-contribution-grid-snake.svg" />
  </picture>
</p>

<br/>

## 💬 Quote of the Day

<p align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical" alt="Dynamic quote" />
</p>

<br/>

## 🏢 Organisation

**Design Lead**, ISDC (Innovex Student Developer Community) · 2024 – Present
Direct the visual identity and design principles for the org, lead a team of 15 building full-stack apps with 3D rendering and decentralized web tech (Web3.js, OpenGL, Three.js), and run Git/deployment workshops for 120+ students.

<br/>

<details>
<summary>⚙️ One-time setup: make the stats, streak, and snake actually go live</summary>

<br/>

1. Create a **public** repo named exactly `Dhyan5` (must match your GitHub username) and put this file in it as `README.md` — GitHub auto-renders that as your profile page. The stats/streak/trophy images above work immediately once that repo exists.

2. To activate the animated snake, add this file as `.github/workflows/snake.yml` in that same repo:

```yaml
name: generate snake

on:
  schedule:
    - cron: "0 0 * * *"   # runs once a day
  workflow_dispatch:
  push:
    branches:
      - main

jobs:
  generate:
    permissions:
      contents: write
    runs-on: ubuntu-latest
    steps:
      - name: generate snake animation
        uses: Platane/snk@v3
        with:
          github_user_name: Dhyan5
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - name: push generated svg to the output branch
        uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

3. Go to **Settings → Actions → General → Workflow permissions** and enable "Read and write permissions" so the action can push the generated SVG, then run it once from the **Actions** tab.

</details>
