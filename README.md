```

  ___  ___  ___  ___   _   _   _____  _____ _   _ _____ 
 / _ \ |  \/  | / _ \ | \ | | /  ___||  _  | \ | |_   _|
/ /_\ \| .  . |/ /_\ \|  \| | \ `--. | | | |  \| | | |  
|  _  || |\/| ||  _  || . ` |  `--. \| | | | . ` | | |  
| | | || |  | || | | || |\  | /\__/ /\ \_/ / |\  |_| |_ 
\_| |_/\_|  |_/\_| |_/\_| \_/ \____/  \___/\_| \_/\___/ 

```

<div align="center">

<p align="center">
  <a href="https://github.com/amangit1314">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=2800&pause=1000&color=58A6FF&center=true&vCenter=true&width=650&lines=AI+Engineer+%E2%80%94+Agents%2C+RAG%2C+Tool-Calling+LLMs;Node.js+%2F+NestJS+%7C+Python+%2F+FastAPI;Shipping+production+systems%2C+not+demos." alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/AI%20Engineering-58A6FF?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Backend%20Systems-3FB950?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/RAG%20%26%20Agents-F778BA?style=for-the-badge"/>
</p>

<p align="center">
  <a href="mailto:risingdeveloper14@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white"/></a>
  <a href="https://linkedin.com/in/aman-soni1"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white"/></a>
  <a href="https://next-level-portfolio.vercel.app"><img src="https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=vercel&logoColor=white"/></a>
  <a href="https://twitter.com/soni07_aman"><img src="https://img.shields.io/badge/X-000000?style=flat-square&logo=x&logoColor=white"/></a>
</p>

</div>

<!--
The name banner above is plain ASCII art in a code fence — not an image, not a service
call. It renders identically everywhere, forever, with nothing to go down. The badges
below it (img.shields.io) and the typing line (readme-typing-svg) are the two services
that have proven reliably fast/stable across every test today — everything that was
flaky (capsule-render's cold starts, github-readme-stats's 503s, ghchart's fixed white
background) has been removed rather than patched again.
-->

---

## About

> Full-stack engineer moving deliberately into AI engineering — not "adding AI to CRUD apps," but building the systems underneath it: tool-calling agents, retrieval pipelines, and the backend infrastructure that makes them reliable in production.
>
> I design the architecture and decisions; I use LLMs to help implement them — same discipline I bring to any other engineering tool.

---

## Featured Projects

### 🔍 [repo-rag](https://github.com/amangit1314/repo-rag) — Tool-calling RAG agent over my own GitHub profile
A chat agent that answers questions like *"has Aman used Kafka?"* or *"is CareerSpire finished?"* in synthesized prose with citations — grounded in real repo content, not stale README claims.

**The interesting decision:** most personal-profile RAG demos batch-embed every repo upfront and do plain vector search. At the scale of one GitHub account, that's wasted work — most repos never get asked about. Instead the LLM decides what to explore at query time via tool calls, caches what it reads, and falls back across model tiers on failure.
`Python` `FastAPI` `Tool-calling agents` `Model routing` `MCP`

### 📡 Pulse — AI-powered local events discovery
Ranked feed built on embeddings over event descriptions and user interaction signals — not a filtered list. The differentiator is the ranking model, not the CRUD around it.
`Embeddings` `Ranking` `Node.js`

### 🎤 CareerSpire (Mocky) — AI mock interview platform
Production-oriented interview practice platform: AI-generated questions and feedback, in-browser code execution, JWT auth with refresh tokens, rate limiting, 1000+ curated question bank.
`Next.js` `Prisma` `Supabase` `LLM feedback loops`

### 🏗️ Eden — AI system-design diagram generator
Generates architecture diagrams from natural-language prompts or a GitHub repo — landing page and design system live, dashboard/generation pipeline in progress.
`Next.js` `Tailwind` `LLM-driven generation`

### 🎓 Coursewave — Full-stack LMS
Course marketplace with instructor/student dashboards, Stripe payments, and Supabase-backed auth — the backend-engineering fundamentals underneath the AI-first projects above.
`Next.js` `Express` `Prisma` `Stripe`

---

## Stack

**AI Engineering**
LLM tool-calling · RAG pipelines · Agent design · Prompt engineering · Model routing/fallback · MCP

<p align="left">
  <img src="https://skillicons.dev/icons?i=nodejs,nestjs,express,fastapi,python,typescript"/>
</p>

**Databases**

<p align="left">
  <img src="https://skillicons.dev/icons?i=postgres,mysql,dynamodb,redis,prisma"/>
</p>

**Frontend**

<p align="left">
  <img src="https://skillicons.dev/icons?i=nextjs,react,tailwind"/>
</p>

**Cloud & Infra**

<p align="left">
  <img src="https://skillicons.dev/icons?i=aws,gcp,docker,kubernetes,githubactions,vercel"/>
</p>

---

## GitHub Activity

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=amangit1314&theme=react-dark&hide_border=true" width="100%"/>
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=amangit1314&theme=github-dark-blue&hide_border=true" alt="GitHub streak stats"/>
</div>

<!--
Dropped from this section, and why:
- github-readme-stats (the stats + top-langs cards): public instance is hard-503ing right
  now — a known, long-running overload issue with the free shared Vercel deployment, not
  fixable by changing the URL. Only real fix is self-hosting your own copy, which is a
  "manually deploy something" step you said you want to avoid, so it's left out entirely.
- ghchart contribution heatmap: it only renders on a fixed white background — no dark
  theme option exists in the service. That's what caused the white/blue box clashing
  against the dark cards above it. Removed rather than fought.
- Contribution snake (Platane/snk): a real, personalized one requires you to add a
  GitHub Actions workflow to your profile repo and let it run on a schedule — exactly
  the kind of manual setup/deploy step you said you don't want. The activity graph and
  streak stats above already show real, live contribution data with zero setup, so the
  snake is dropped rather than handed to you as another chore.
-->

---

## Currently Learning

Multi-agent systems · LangGraph · Model Context Protocol · Kubernetes · AI observability & evals

---

<div align="center">

**risingdeveloper14@gmail.com** · [LinkedIn](https://linkedin.com/in/aman-soni1) · [Portfolio](https://next-level-portfolio.vercel.app)

</div>
