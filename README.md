<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:000000,50:171717,100:404040&height=180&section=header&text=RAHUL&fontSize=52&fontColor=E5E5E5&animation=fadeIn&fontAlignY=55" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=1000&color=C0C0C0&center=true&vCenter=true&width=750&lines=Full+Stack+Developer;Web+%7C+Mobile+%7C+Backend;AI+%2F+ML+Application+Builder;Automation+%7C+Cloud+%7C+Testing;Always+Learning+%26+Building" />
</p>

<p align="center">
  <a href="https://github.com/codeofrealm">
    <img src="https://img.shields.io/badge/GitHub-000000?style=for-the-badge&logo=github&logoColor=FFFFFF" />
  </a>
  <a href="https://github.com/codeofrealm?tab=repositories">
    <img src="https://img.shields.io/badge/Repositories-171717?style=for-the-badge&logo=github&logoColor=FFFFFF" />
  </a>
  <img src="https://komarev.com/ghpvc/?username=codeofrealm&style=for-the-badge&color=404040&label=PROFILE+VIEWS" />
</p>

🖥️ Skills & Technology

🌐 Frontend Development

<p>
  <img src="https://skillicons.dev/icons?i=react,nextjs,flutter&theme=dark" />
</p>

React Next.js Flutter React Native

⚙️ Backend Development

<p>
  <img src="https://skillicons.dev/icons?i=django,fastapi,spring&theme=dark" />
</p>

Django FastAPI Spring Boot

💻 Programming Languages

<p>
  <img src="https://skillicons.dev/icons?i=python,java,js,ts&theme=dark" />
</p>

Python Java JavaScript TypeScript

🗄️ Databases

<p>
  <img src="https://skillicons.dev/icons?i=mongodb,mysql,postgres&theme=dark" />
</p>

MongoDB MySQL PostgreSQL

🤖 AI / ML

┌─────────────────────────────────────┐
│             AI / ML                 │
├─────────────────────────────────────┤
│                                     │
│  🧠 ML Training                     │
│  🤖 AI Applications                 │
│                                     │
└─────────────────────────────────────┘

ML Training AI Applications

☁️ Cloud

<p>
  <img src="https://skillicons.dev/icons?i=aws,firebase&theme=dark" />
</p>

AWS Firebase Supabase

🔄 Automation

┌─────────────────────────────────────┐
│            AUTOMATION               │
├─────────────────────────────────────┤
│                                     │
│  🔄 n8n                             │
│  ⚙️ Automation Testing              │
│                                     │
└─────────────────────────────────────┘

n8n Automation Testing

🎮 Game Development

<p>
  <img src="https://skillicons.dev/icons?i=blender,godot&theme=dark" />
</p>

Blender Godot Engine

🧪 Testing

┌─────────────────────────────────────┐
│              TESTING                │
├─────────────────────────────────────┤
│                                     │
│  🔍 Manual Testing                  │
│  ⚙️ Automation Testing              │
│                                     │
└─────────────────────────────────────┘

Manual Testing Automation Testing

📊 GitHub Analytics

<p align="center">
  <img src="./github-metrics.svg" alt="GitHub Analytics" width="100%" />
</p>

GitHub analytics are generated automatically with the lowlighter/metrics GitHub Action.

📅 Contribution Activity

<p align="center">
  <img src="./github-metrics-habits.svg" alt="Contribution Activity and Coding Habits" width="100%" />
</p>

The metrics workflow generates contribution activity, coding habits and activity visualizations automatically.

🏆 GitHub Achievements

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=codeofrealm&theme=darkhub&no-frame=true&no-bg=true&margin-w=8&row=1&column=7" alt="GitHub Achievements" width="100%" />
</p>

🖥️ 3D Cyber PC Showcase

<p align="center">
  <a href="YOUR_PORTFOLIO_3D_MODEL_LINK">
    <img
      src="YOUR_3D_MODEL_PREVIEW_GIF"
      alt="Cyber PC 3D Model"
      width="850"
    />
  </a>
</p>

<p align="center">
  <strong>Interactive 3D Cyber PC</strong><br/>
  Scroll-driven 3D experience • Three.js • React Three Fiber • Blender
</p>

<p align="center">
  <a href="YOUR_PORTFOLIO_3D_MODEL_LINK">
    <img src="https://img.shields.io/badge/VIEW%203D%20MODEL-000000?style=for-the-badge&logo=three.js&logoColor=white" />
  </a>
  <a href="YOUR_3D_MODEL_DOWNLOAD_LINK">
    <img src="https://img.shields.io/badge/DOWNLOAD%20MODEL-262626?style=for-the-badge&logo=blender&logoColor=white" />
  </a>
</p>

A cyber-style 3D PC experience where scrolling through the portfolio controls the camera and model movement.

⚙️ GitHub Metrics Setup

The analytics above are generated using lowlighter/metrics.

Create:

.github/
└── workflows/
    └── metrics.yml

Example configuration:

name: GitHub Metrics

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:

jobs:
  github-metrics:
    runs-on: ubuntu-latest

    permissions:
      contents: write

    steps:
      - name: Generate GitHub Analytics
        uses: lowlighter/metrics@latest
        with:
          token: ${{ secrets.GITHUB_TOKEN }}
          user: codeofrealm
          filename: github-metrics.svg
          template: classic
          config_timezone: Asia/Kolkata
          base: header, activity, community, repositories, metadata
          plugin_isocalendar: yes
          plugin_isocalendar_duration: full-year
          plugin_languages: yes
          plugin_habits: yes
          plugin_habits_from: 300
          plugin_habits_days: 30
          plugin_habits_charts: yes
          output_action: commit

      - name: Generate Contribution Activity
        uses: lowlighter/metrics@latest
        with:
          token: ${{ secrets.GITHUB_TOKEN }}
          user: codeofrealm
          filename: github-metrics-habits.svg
          template: classic
          config_timezone: Asia/Kolkata
          base: activity
          plugin_calendar: yes
          plugin_calendar_limit: 1
          plugin_habits: yes
          plugin_habits_from: 300
          plugin_habits_days: 30
          plugin_habits_charts: yes
          output_action: commit

The isocalendar plugin provides the isometric contribution calendar, while the habits plugin provides coding-activity and habits visualizations. The current lowlighter/metrics documentation lists both plugins and supports committing generated SVG output from the Action.

🌐 GitHub

<p align="center">
  <a href="https://github.com/codeofrealm">
    <img src="https://img.shields.io/badge/GitHub-000000?style=for-the-badge&logo=github&logoColor=FFFFFF" />
  </a>

  <a href="https://github.com/codeofrealm?tab=repositories">
    <img src="https://img.shields.io/badge/Repositories-262626?style=for-the-badge&logo=github&logoColor=FFFFFF" />
  </a>
</p>

👀 Profile Views

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=codeofrealm&style=for-the-badge&color=404040&labelColor=000000&label=PROFILE+VIEWS" />
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:404040,50:171717,100:000000&height=130&section=footer" />

  <br/>

⚫ ZERONEX

Developer • Builder • Learner • Creator

Thanks for visiting my GitHub profile.

</p>

<p align="center">
  <sub>© Rahul • Built with code, curiosity and consistency.</sub>
</p>
