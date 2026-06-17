<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=4F46E5&height=180&section=header&text=Maike%20Silva&fontSize=50&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Full-Stack%20%7C%20AI%20Tools%20Builder%20%7C%20Open%20Source&descSize=16&descAlignY=55" width="100%"/>
</p>

<p align="center">
  <a href="https://github.com/devmkpro/codebrain"><img src="https://img.shields.io/badge/🧠_Building-Codebrain-4F46E5?style=for-the-badge" alt="Codebrain"/></a>
  <img src="https://komarev.com/ghpvc/?username=devmkpro&label=Profile+views&color=4F46E5&style=for-the-badge" alt="views"/>
</p>

<p align="center">
  <a href="https://github.com/devmkpro/codebrain">
    <img src="https://readme-typing-svg.demolab.com/?font=JetBrains+Mono&weight=600&size=15&pause=1000&color=4F46E5&center=true&vCenter=true&width=550&lines=Building+Codebrain+-+Multi-Agent+AI+IDE;244+MCP+tools+%7C+Browser+automation+%7C+Shared+memory" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="https://github.com/devmkpro/codebrain"><img src="https://img.shields.io/github/stars/devmkpro/codebrain?style=social" alt="Stars"></a>
  <img src="https://img.shields.io/badge/version-1.10.6-4F46E5?style=flat-square&logo=semver" alt="Version">
  <img src="https://img.shields.io/badge/license-MIT-10B981?style=flat-square" alt="MIT">
  <img src="https://img.shields.io/badge/MCP_tools-244-F59E0B?style=flat-square" alt="244 MCP tools">
  <img src="https://img.shields.io/badge/agents-multi--agent-8B5CF6?style=flat-square" alt="Multi-agent">
</p>

---

## What I'm Building

<table>
<tr>
<td width="50%" valign="top">

### 🧠 [Codebrain](https://github.com/devmkpro/codebrain)
**Multi-Agent AI IDE**

> Where AI agents work together, not alone.

Electron desktop app where multiple AI agents (Claude, Gemini, MIMO, Codex) orchestrate in a visible terminal grid.

```
244 MCP tools       Browser automation
Multi-agent squads  Shared memory (SQLite)
Pattern learning    LSP integration
Session checkpoints Goal/Judge system
Mission management  Marketplace
```

![Electron](https://img.shields.io/badge/Electron-47848F?style=flat&logo=electron&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)

</td>
<td width="50%" valign="top">

### 🔧 [AiParts](https://aiparts.com.br/)
**Auto Parts Intelligence**

> Laravel + AI for automotive parts e-commerce.

Full-stack platform with AI-powered search, supplier portal, order tracking, and multi-channel integrations.

```
AI agents           MCP tools
WhatsApp API        Shipping integration
Supplier portal     Real-time tracking
Multi-tenant admin  Adaptive engine
```

![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat&logo=laravel&logoColor=white)
![Filament](https://img.shields.io/badge/Filament-4F46E5?style=flat&logo=filament&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)

</td>
</tr>
</table>

---

## Architecture

```
Codebrain Architecture
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ┌─────────────────────────────────────────────────────────────┐
  │                    Electron Desktop App                       │
  │  ┌─────────────┐  ┌─────────────┐  ┌─────────────┐          │
  │  │  Orchestrator│  │   Worker 1  │  │   Worker 2  │  ...     │
  │  │  (Opus)      │  │  (Sonnet)   │  │  (Gemini)   │          │
  │  └──────┬───────┘  └──────┬──────┘  └──────┬──────┘          │
  │         │                 │                 │                 │
  │         └────────┬────────┴────────┬────────┘                 │
  │                  │                 │                          │
  │         ┌────────▼────────┐ ┌──────▼───────┐                 │
  │         │   MCP Server    │ │ Shared Memory │                 │
  │         │  (244 tools)    │ │   (SQLite)    │                 │
  │         └────────┬────────┘ └──────────────┘                 │
  │                  │                                            │
  │    ┌─────────────┼─────────────┐                             │
  │    │             │             │                              │
  │  Browser      Filesystem    Network                          │
  │  (CDP)        (read/write)  (fetch/MCP)                      │
  └─────────────────────────────────────────────────────────────┘
```

---

## Tech Stack

<p align="center">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="TypeScript" width="40" height="40">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="JavaScript" width="40" height="40">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" alt="PHP" width="40" height="40">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" width="40" height="40">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/go/go-original.svg" alt="Go" width="40" height="40">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="Java" width="40" height="40">
  &nbsp;&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" alt="React" width="40" height="40">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/electron/electron-original.svg" alt="Element" width="40" height="40">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/laravel/laravel-original.svg" alt="Laravel" width="40" height="40">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/tailwindcss/tailwindcss-original.svg" alt="Tailwind" width="40" height="40">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/vuejs/vuejs-original.svg" alt="Vue" width="40" height="40">
  &nbsp;&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg" alt="PostgreSQL" width="40" height="40">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" alt="Docker" width="40" height="40">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="Linux" width="40" height="40">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redis/redis-original.svg" alt="Redis" width="40" height="40">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nginx/nginx-original.svg" alt="Nginx" width="40" height="40">
</p>

---

## GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=devmkpro&show_icons=true&theme=transparent&bg_color=0D1117&hide_border=true&title_color=4F46E5&icon_color=4F46E5&text_color=C9D1D9&ring_color=4F46E5" alt="Stats" height="165">
  &nbsp;&nbsp;
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=devmkpro&layout=compact&theme=transparent&bg_color=0D1117&hide_border=true&title_color=4F46E5&text_color=C9D1D9" alt="Top Langs" height="165">
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=devmkpro&theme=transparent&background=0D1117&hide_border=true&ring=4F46E5&fire=4F46E5&currStreakLabel=4F46E5" alt="Streak" height="150">
</p>

---

## Connect

<p align="center">
  <a href="https://www.linkedin.com/in/maike-s-3090141ab/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://instagram.com/_devmk"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram"></a>
  <a href="https://discord.gg/_devmk"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord"></a>
</p>

---

<p align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=dark" alt="Random Dev Quote"/>
</p>

<p align="center">
  <i>"Building the tools I wish existed."</i>
</p>
