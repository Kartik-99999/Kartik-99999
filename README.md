<h1>Kartik Bhardwaj</h1>

I build systems that have to survive contact with the real world — a behavioural
cyber-resilience platform for critical national infrastructure, a multi-tenant school ERP
serving schools on their own subdomains, and a defence-journalism site that researches,
writes and publishes itself every morning.

Mostly **Python** and **TypeScript**, with a bias toward things that run in production and
prove their own claims.

<p>
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
  <img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
  <img alt="Next.js" src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" />
  <img alt="React" src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" />
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img alt="Neo4j" src="https://img.shields.io/badge/Neo4j-4581C3?style=flat-square&logo=neo4j&logoColor=white" />
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img alt="Tailwind" src="https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" />
  <img alt="C++" src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white" />
</p>

📫 [kartikbhardwaj.0705@gmail.com](mailto:kartikbhardwaj.0705@gmail.com)

---

## What I'm building

### 🛡️ [PRAHARÍ](https://github.com/Kartik-99999/prahari) — behavioural cyber resilience for critical infrastructure

Detects attacker *behaviour* instead of signatures, fuses weak signals across a provenance
graph into one ranked attack chain, maps it to MITRE ATT&CK, and orchestrates auditable
autonomous response against a tamper-evident ledger.

- **0.9988 ROC-AUC** on a controlled 21-day APT scenario · **0.845 macro ROC** on held-out
  public CIC-IDS-2017 — both reported separately, because conflating them would be dishonest
- **92.3%** exact MITRE ATT&CK technique attribution with **0 false attributions**
- Containment fires on day 1.7, severing C2 **17 days before** scheduled exfiltration
- Hash-chained audit ledger — the tamper demo catches a privileged row rewrite at the exact entry

`Python` `TypeScript` `Neo4j` `PostgreSQL` `MITRE ATT&CK` `SOAR`
&nbsp;·&nbsp; [Live console](http://3.7.9.1:3000) &nbsp;·&nbsp; [2-min demo](https://drive.google.com/file/d/13jo_jX9gD92pBCs7jl9IvDX5Eh3KyCss/view?usp=sharing)

### 🏫 [School ERP](https://github.com/Kartik-99999/School-Erp) — multi-tenant SaaS · [erpcore.tech](https://erpcore.tech)

One deployment serves many schools, each isolated on its own subdomain with PostgreSQL
row-level security. ~23 API routers covering admissions, attendance, fees, exams and
transport, with a Super-Admin console that onboards new schools from the base domain.

`FastAPI` `SQLAlchemy 2.0 + asyncpg` `Next.js 14` `TypeScript` `Razorpay` `Twilio/WhatsApp`

### 📰 [DefencePost](https://github.com/Kartik-99999/defence_post) — independent Indian defence journalism · [defencepost.live](https://www.defencepost.live)

A live publication plus the automation that keeps it alive. The site is a dependency-free
client-rendered front end on Vercel over a separate content API; around it sits a pipeline
that pulls the last 24h of defence news, writes the article, finds a licensed cover image,
publishes it, and pushes it to Google's index — daily, at zero running cost.

- [`defencepost-automation`](https://github.com/Kartik-99999/defencepost-automation) — RSS/GDELT → Gemini → published article, on GitHub Actions
- [`defencepost-search_automation`](https://github.com/Kartik-99999/defencepost-search_automation) — submits every URL to the Google Indexing API
- [`defencepost-extras`](https://github.com/Kartik-99999/defencepost-extras) — Telegram auto-poster, Drive backups, Google News sitemap

### 🎉 [CelebrationCraft](https://github.com/Kartik-99999/celebrationcraft) — celebration-site generator · [live](https://celebrationcraft.vercel.app)

Personalised birthday and event microsites for ₹100 — 28 templates, a four-step order flow,
Razorpay checkout, and WhatsApp delivery in minutes.

### 🧮 [DSA Web Visualizer](https://github.com/Kartik-99999/dsa)

Linked lists, stacks and queues driven from the browser against a **C++ REST backend**
(cpp-httplib) that mirrors a console DSA menu. Built with Bhavya, Ishika and Rishika.

---

## GitHub

<p>
  <img src="https://streak-stats.demolab.com/?user=Kartik-99999&hide_border=true&background=00000000&ring=58A6FF&fire=58A6FF&currStreakLabel=58A6FF&sideNums=8B949E&sideLabels=8B949E&dates=6E7681&currStreakNum=C9D1D9&stroke=30363D" alt="Contribution streak" />
</p>

<p>
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Kartik-99999&bg_color=00000000&color=8B949E&line=58A6FF&point=C9D1D9&area=true&hide_border=true" alt="Contribution activity" />
</p>
