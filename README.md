<h1>Kartik Bhardwaj</h1>

I build systems that have to survive contact with the real world — a behavioural
cyber-resilience platform for critical national infrastructure, a multi-tenant school ERP
serving schools on their own subdomains, and a defence-journalism site that researches,
writes and publishes itself every morning.

Mostly **Python** and **TypeScript** — FastAPI, Next.js, PostgreSQL, Neo4j — with a bias
toward things that run in production and prove their own claims.

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
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=Kartik-99999&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&theme=transparent" alt="GitHub stats" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Kartik-99999&layout=compact&hide_border=true&langs_count=6&theme=transparent" alt="Top languages" />
</p>
