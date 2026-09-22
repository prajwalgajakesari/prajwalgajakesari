<!-- ─────────────────────────────  HEADER  ───────────────────────────── -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:1e1b4b,50:4c1d95,100:312e81&height=190&text=Prajwal%20P&fontSize=56&fontColor=ffffff&fontAlignY=40&desc=Data%20platforms%20%C2%B7%20Apple-native%20apps%20%C2%B7%20AI%20tooling&descSize=18&descAlignY=62&animation=fadeIn" alt="Prajwal P" width="100%" />
</div>

<div align="center">

**Engineer who ships small, focused tools. Usually because I wanted them to exist and they didn't.**

<a href="#-featured-projects">Projects</a>&nbsp;&nbsp;·&nbsp;&nbsp;<a href="#-toolbox">Toolbox</a>&nbsp;&nbsp;·&nbsp;&nbsp;<a href="#-activity">Activity</a>&nbsp;&nbsp;·&nbsp;&nbsp;<a href="#-get-in-touch">Contact</a>

</div>

<br/>

<!-- ─────────────────────────────  ABOUT  ───────────────────────────── -->
<table>
<tr>
<td width="58%" valign="top">

### 👋 About

I work at the intersection of **data platforms**, **Apple-native apps**, and **AI tooling**.

Most of what I build starts as a personal itch: a way to hand an AI coding session to a teammate through git, a disk cleaner that tells you what is *safe* to delete, a slash command so Claude Code can play music, a converter that turns a Google Maps route into a GPX file for a long ride. I like tools that do one job well, ship with a clear README, and respect the user's data.

Day to day that means SwiftUI on macOS and iOS, TypeScript and Python on the server, and Trino, Azure Data Lake and Purview on the data side.

</td>
<td width="42%" valign="top">

### 🔭 Currently

- 🍎 Writing **SwiftUI** apps for macOS and iOS
- 🤖 Building **MCP servers** and **Claude Code plugins** so assistants can act, not just answer
- 🗄️ Running data platforms on **Trino**, **ADLS Gen2** and **Purview**
- 📚 Studying **Forward Deployed Engineering** and publishing the roadmap
- 🏍️ Riding, and building software for riders

</td>
</tr>
</table>

<br/>

<!-- ─────────────────────────────  PROJECTS  ───────────────────────────── -->
## 🚀 Featured projects

<table>
<tr>
<td colspan="2" valign="top">

### [🔄 agent-sessions](https://github.com/prajwalgajakesari/agent-sessions)

Share coding-agent sessions with your team through the git repo you already work in. One push turns a **Claude Code**, **Codex CLI** or **OpenCode** session into a redacted transcript plus a handoff summary under `.claude/sessions/`; a teammate on any agent pulls it straight into their own chat. Secrets and query results never leave the machine, and the commit is built on a temporary index so your working tree is untouched. Ships three ways: a Claude Code plugin, an Agent Skills skill that Codex, OpenCode, Gemini CLI, Cursor and Copilot all read, and a CLI on PyPI.

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" /> <img src="https://img.shields.io/pypi/v/agent-sessions-cli?style=flat-square&color=6366f1&label=pypi" alt="PyPI" /> <img src="https://img.shields.io/github/actions/workflow/status/prajwalgajakesari/agent-sessions/ci.yml?style=flat-square&label=ci" alt="CI" /> <img src="https://img.shields.io/badge/Claude%20Code-D97757?style=flat-square&logo=anthropic&logoColor=white" alt="Claude Code" /> <img src="https://img.shields.io/badge/Codex%20CLI-000000?style=flat-square&logo=openai&logoColor=white" alt="Codex CLI" /> <img src="https://img.shields.io/badge/OpenCode-6366f1?style=flat-square" alt="OpenCode" /> <img src="https://img.shields.io/github/stars/prajwalgajakesari/agent-sessions?style=flat-square&color=6366f1&label=stars" alt="Stars" />

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [🧭 DiskLens](https://github.com/prajwalgajakesari/disklens)

Native macOS disk-space visualizer and cleaner with a Liquid Glass UI. A free, open-source alternative to CleanMyMac's Space Lens, with safety colour-coding so you never delete the wrong thing.

<img src="https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white" alt="Swift" /> <img src="https://img.shields.io/badge/SwiftUI-0A84FF?style=flat-square&logo=apple&logoColor=white" alt="SwiftUI" /> <img src="https://img.shields.io/github/stars/prajwalgajakesari/disklens?style=flat-square&color=6366f1&label=stars" alt="Stars" />

</td>
<td width="50%" valign="top">

### [📰 The Vault, AI Edition](https://github.com/prajwalgajakesari/the-vault-ai)

A daily AI intelligence brief, researched and published automatically every morning: 15 to 20 stories across models, research, business and policy, with a styled HTML edition and structured JSON.

<img src="https://img.shields.io/badge/Markdown-000000?style=flat-square&logo=markdown&logoColor=white" alt="Markdown" /> <img src="https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML" /> <img src="https://img.shields.io/badge/updated-daily-6366f1?style=flat-square" alt="Updated daily" />

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [🎵 claude-music](https://github.com/prajwalgajakesari/claude-music)

A `/music` slash command for Claude Code. Play, pause, skip and search Apple Music, or tune into Claude FM, without leaving the terminal.

<img src="https://img.shields.io/badge/Shell-4EAA25?style=flat-square&logo=gnubash&logoColor=white" alt="Shell" /> <img src="https://img.shields.io/badge/AppleScript-000000?style=flat-square&logo=apple&logoColor=white" alt="AppleScript" /> <img src="https://img.shields.io/badge/Claude%20Code-D97757?style=flat-square&logo=anthropic&logoColor=white" alt="Claude Code" />

</td>
<td width="50%" valign="top">

### [🗺️ gmaps2gpx](https://github.com/prajwalgajakesari/gmaps2gpx)

Convert Google Maps direction URLs to GPX files, as a <a href="https://gmaps2gpx.vercel.app">web app</a> or a CLI on PyPI. Handles shortened links, dragged routes and alternatives, plus a motorcycle routing mode.

<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" /> <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" /> <img src="https://img.shields.io/pypi/v/gmaps2gpx?style=flat-square&color=6366f1&label=pypi" alt="PyPI" />

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [🔗 Azure Purview MCP](https://github.com/prajwalgajakesari/Azure_Purview_MCP)

A Model Context Protocol server that lets an AI assistant search, read and update Azure Purview data-catalog metadata, including table and column descriptions.

<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" /> <img src="https://img.shields.io/badge/MCP-000000?style=flat-square&logo=modelcontextprotocol&logoColor=white" alt="MCP" /> <img src="https://img.shields.io/badge/Azure-0078D4?style=flat-square&logoColor=white" alt="Azure" />

</td>
<td width="50%" valign="top">

### [🎓 FDE Roadmap](https://github.com/prajwalgajakesari/fde-roadmap)

A free six-week self-study path to Forward Deployed Engineering, distilled from paid programmes down to the judgment and frameworks AI can't replace.

<img src="https://img.shields.io/badge/6%20weeks-6366f1?style=flat-square" alt="6 weeks" /> <img src="https://img.shields.io/badge/cost-free-22c55e?style=flat-square" alt="Free" /> <img src="https://img.shields.io/badge/13%20artifacts-f59e0b?style=flat-square" alt="13 artifacts" />

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [🛠️ DataForge](https://github.com/prajwalgajakesari/dataforge)

AI-assisted data modeling from the terminal. Profile a PostgreSQL schema, detect normalization violations from 1NF to BCNF, design a star schema, and generate a dbt project that passes validation. Ships as a Claude Code skill and plugin.

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" /> <img src="https://img.shields.io/badge/dbt-FF694B?style=flat-square&logoColor=white" alt="dbt" /> <img src="https://img.shields.io/badge/Claude%20Code-D97757?style=flat-square&logo=anthropic&logoColor=white" alt="Claude Code" />

</td>
<td width="50%" valign="top">

### [⚡ Trino 474 + ADLS Gen2](https://github.com/prajwalgajakesari/trino-474-docker-adls-setup)

Docker Compose setup for Trino 474 with a Hive file metastore and native Azure Data Lake Gen2 support, with example SQL for external schemas and tables.

<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" /> <img src="https://img.shields.io/badge/Trino-DD00A1?style=flat-square&logo=trino&logoColor=white" alt="Trino" /> <img src="https://img.shields.io/badge/Azure-0078D4?style=flat-square&logoColor=white" alt="Azure" />

</td>
</tr>
</table>

<p align="right"><sub><a href="https://github.com/prajwalgajakesari?tab=repositories&type=source">All repositories →</a></sub></p>

<br/>

<!-- ─────────────────────────────  TOOLBOX  ───────────────────────────── -->
## 🧰 Toolbox

<table>
<tr>
<td><b>Languages</b></td>
<td>
<img src="https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white" alt="Swift" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white" alt="Dart" />
<img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white" alt="Kotlin" />
<img src="https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white" alt="SQL" />
<img src="https://img.shields.io/badge/Shell-4EAA25?style=flat-square&logo=gnubash&logoColor=white" alt="Shell" />
</td>
</tr>
<tr>
<td><b>Apple</b></td>
<td>
<img src="https://img.shields.io/badge/SwiftUI-0A84FF?style=flat-square&logo=apple&logoColor=white" alt="SwiftUI" />
<img src="https://img.shields.io/badge/macOS-000000?style=flat-square&logo=apple&logoColor=white" alt="macOS" />
<img src="https://img.shields.io/badge/iOS-000000?style=flat-square&logo=apple&logoColor=white" alt="iOS" />
<img src="https://img.shields.io/badge/Xcode-147EFB?style=flat-square&logo=xcode&logoColor=white" alt="Xcode" />
<img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white" alt="Flutter" />
</td>
</tr>
<tr>
<td><b>Data &amp; Cloud</b></td>
<td>
<img src="https://img.shields.io/badge/Trino-DD00A1?style=flat-square&logo=trino&logoColor=white" alt="Trino" />
<img src="https://img.shields.io/badge/Azure-0078D4?style=flat-square&logoColor=white" alt="Azure" />
<img src="https://img.shields.io/badge/ADLS%20Gen2-0078D4?style=flat-square&logoColor=white" alt="ADLS Gen2" />
<img src="https://img.shields.io/badge/Purview-0078D4?style=flat-square&logoColor=white" alt="Purview" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
<img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" alt="Vercel" />
</td>
</tr>
<tr>
<td><b>AI &amp; Agents</b></td>
<td>
<img src="https://img.shields.io/badge/Claude%20Code-D97757?style=flat-square&logo=anthropic&logoColor=white" alt="Claude Code" />
<img src="https://img.shields.io/badge/Model%20Context%20Protocol-000000?style=flat-square&logo=modelcontextprotocol&logoColor=white" alt="MCP" />
<img src="https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white" alt="Gemini" />
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
<img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" />
<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
</td>
</tr>
</table>

<br/>

<!-- ─────────────────────────────  ACTIVITY  ───────────────────────────── -->
## 📊 Activity

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=prajwalgajakesari&theme=github_dark" />
    <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=prajwalgajakesari&theme=github" alt="Contribution overview" />
  </picture>
  <br/><br/>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=prajwalgajakesari&theme=github-dark-blue&hide_border=true" />
    <img src="https://streak-stats.demolab.com?user=prajwalgajakesari&theme=default&hide_border=true" alt="Contribution streak" />
  </picture>
</div>

<p align="center"><sub>Most of my commits land in private product repositories; the counts above include them.</sub></p>

<br/>

<!-- ─────────────────────────────  CONTACT  ───────────────────────────── -->
## 📫 Get in touch

The easiest way to reach me is to open an issue on any of my repositories, or follow along here on GitHub.

<p>
  <a href="https://github.com/prajwalgajakesari"><img src="https://img.shields.io/badge/GitHub-@prajwalgajakesari-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" /></a>
  <a href="https://github.com/prajwalgajakesari?tab=followers"><img src="https://img.shields.io/github/followers/prajwalgajakesari?style=flat-square&color=6366f1&logo=github&logoColor=white&label=followers" alt="Followers" /></a>
</p>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:312e81,50:4c1d95,100:1e1b4b&height=6" alt="" width="100%" />
</div>
