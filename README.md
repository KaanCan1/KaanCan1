<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=200&color=0:1C1A17,60:8A5F0C,100:E0A93B&text=Kaan%20Can%20Kurt&fontSize=44&fontColor=FFFFFF&animation=fadeIn&fontAlignY=38&desc=Flutter%20%26%20Full%20Stack%20Developer&descAlignY=58&descSize=17"/>

<br/>

<a href="https://kaancankurt.vercel.app"><img src="https://img.shields.io/badge/Portfolio-1C1A17?style=for-the-badge&logo=vercel&logoColor=E0A93B"/></a>
<a href="https://linkedin.com/in/kaan-can-kurt-805990299"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:kaancan368368@gmail.com"><img src="https://img.shields.io/badge/Email-1C1A17?style=for-the-badge&logo=maildotru&logoColor=E0A93B"/></a>

<br/><br/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=22&pause=1200&color=E0A93B&center=true&vCenter=true&width=620&lines=Cross-platform+mobile+apps+with+Flutter;Full-stack+web+products%2C+interface+to+API;Building+with+Claude+%26+MCP;Deterministic+first%2C+LLM+second"/>

</div>

<br/>

## About

I build cross-platform mobile apps with **Flutter** and ship full-stack web products from the interface down to the API. Lately most of my time goes to **Portfolio Tracker** — a self-hosted trading dashboard I use every day, where I own the whole stack: product, UI, Express backend, market-data pipelines and the Claude AI layer.

I care about small dependency counts, systems that fail honestly, and shipping things that actually get used.

```
Location   İzmir, Türkiye
Focus      Flutter · Node.js · PostgreSQL · AI integration
Now        Portfolio Tracker — daily driver, solo build
Open to    New roles and freelance work
```

<br/>

## Tech Stack

<div align="center">

**Mobile & Frontend**

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white) ![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

**Backend & Data**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white) ![Fastify](https://img.shields.io/badge/Fastify-000000?style=for-the-badge&logo=fastify&logoColor=white) ![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white) ![C#](https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=dotnet&logoColor=white) ![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)

**Databases & Infra**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white) ![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

**AI & Tools**

![Claude](https://img.shields.io/badge/Claude_API-D97757?style=for-the-badge&logo=anthropic&logoColor=white) ![MCP](https://img.shields.io/badge/MCP-6C47FF?style=for-the-badge&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white) ![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white) ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white) ![Android Studio](https://img.shields.io/badge/Android_Studio-3DDC84?style=for-the-badge&logo=androidstudio&logoColor=white)

</div>

<br/>

## Featured Project

<div align="center">
  <a href="https://github.com/KaanCan1/portfolio-tracker">
    <img width="88%" src="https://raw.githubusercontent.com/KaanCan1/portfolio-tracker/main/docs/screenshots/overview.png" alt="Portfolio Tracker"/>
  </a>
</div>

<br/>

### 📊 [Portfolio Tracker](https://github.com/KaanCan1/portfolio-tracker)

> Self-hosted stock portfolio & swing-trading discipline dashboard, with a Claude AI layer and an MCP server.

Built end to end as a solo project — product, design, backend, data pipelines and AI integration. Instead of just charting prices it enforces the rules I set for myself: positions without a stop plan get flagged, new entries are blocked when the market regime is bad, and profits trigger a "pull your initial capital out" suggestion.

**What's inside**

- **Radar engine** — one 0–100 score per ticker from momentum, analyst consensus, fundamentals and insider activity, plus breakout/pullback setup detection and a market-regime gate
- **Claude thesis desk** — adversarial bull/bear analysis grounded only in the app's own data, returned as structured JSON (`json_schema`) and cached per symbol
- **Deterministic first, LLM second** — a rule engine grades every trade of the day; Claude only interprets the evidence pack it produces
- **Risk desk** — correlation matrix, 95% VaR, portfolio beta, Monte-Carlo net-worth forecast
- **Guardian** — hourly server-side checks that e-mail alerts for breached stops and concentration limits
- **MCP server** — exposes the whole API to Claude Code / Desktop as 6 tools
- **Zero-framework SPA** — no build step, 3 runtime dependencies total

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Claude](https://img.shields.io/badge/Claude_API-D97757?style=flat-square&logo=anthropic&logoColor=white) ![MCP](https://img.shields.io/badge/MCP-6C47FF?style=flat-square)

<br/>

---

<br/>

## Other Projects

### ☕ [BeanSocial](https://github.com/KaanCan1/beansocial_son)

> A social platform for coffee lovers — share recipes, save favourite brews, discover new coffee. My graduation project.

Flutter client with GetX state management, backed by a custom Node.js/Express API using Prisma, JWT auth and image uploads. Built solo from UI to database schema.

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white) ![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white) ![GetX](https://img.shields.io/badge/GetX-8A2BE2?style=flat-square) ![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white) ![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
