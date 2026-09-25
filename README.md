<div align="center">

# Daniel Favour Dohou

### Backend Software Engineer · AI Systems · Open Source

**I design for what goes wrong.**

Python · Django · PostgreSQL · Celery · Redis · Docker · AI

`Open to remote roles` · `UTC+1, full overlap with European hours`

[![Portfolio](https://img.shields.io/badge/Portfolio-dohoudanielfavour.me-3B82F6?style=for-the-badge&logo=globe&logoColor=white)](https://dohoudanielfavour.me)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/dohoudanielfavour)
[![X](https://img.shields.io/badge/X_(Twitter)-Follow-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/DohouDaniel10)
[![Blog](https://img.shields.io/badge/Blog-Hashnode-2962FF?style=for-the-badge&logo=hashnode&logoColor=white)](https://dohoudanielfavour.hashnode.dev)

</div>

---

## 👋 Hey, I'm Daniel

Backend Software Engineer working remotely from Lagos, Nigeria (UTC+1), a full working day alongside the EU and UK and a morning alongside US Eastern. I build systems that hold up after the demo is over: the schema, the async pipelines, the failover, and the decisions that only start to matter once real traffic arrives.

- 🌙 I build the backend of **[Lune](https://lunehire.com)**, a hiring platform where talent proves ability through proctored assessments instead of claiming it on a CV. Launched **27 July 2026**, serving **200+ users**
- 📝 Built **[Smart ATS](https://smart-ats.algorithmia-se.com)** to **300+ job seekers** and **150+ CVs reviewed**, then rebuilt it inside Lune as its CV Studio, Resume Screen and skill intelligence layer
- 📍 Founded **[Eventraka](https://eventraka.vercel.app)**, an AI Event Intelligence Platform that finds events instead of waiting for organisers to post them
- 🐧 **Outreachy May 2026** contributor to the **[Fedora Project](https://fedoraproject.org)**, working on Ramalama's RAG pipeline
- 🌍 Founded **[Algorithmia SE](https://www.algorithmia-se.com/)**, an ALX study group grown into a **1,000+ member** open-source engineering community
- 🏆 **ALX SE Superman** · 🥉 **Hackathon 3rd place** with [JechSpace](https://jechspace.app)
- 👥 Managed **4,000+ learners** across 13 cohorts at ALX Nigeria · **8.76 CSAT · 4.53 NPS**

---

## 📊 By the Numbers

<div align="center">

| 4 | 500+ | 1,000+ | 4,000+ | 8.76 | 25 |
|:---:|:---:|:---:|:---:|:---:|:---:|
| Products Live | Users Served | Community Members | Learners Managed | CSAT Score | Builds Shipped |

</div>

---

## 🧠 How I Think About Backends

The interesting part of a backend is rarely the happy path. These are decisions from systems currently in production:

```
Provider failover        4 AI providers behind circuit breakers, with a SEPARATE
                         embedding chain, because vectors from different models
                         are not comparable and silently poison retrieval.

Grounding you can see    RAG failures look identical to successes, so every run
                         is tallied, surfaced in health checks, and scored
                         against its own source chunks.

Boundaries that hold     CV signal may ROUTE, never WEIGHT. No foreign key from
                         assessment history into screening; the verified score
                         is a frozen snapshot, not a live link.

Cancel, then confirm     Downgrades cancel at the provider FIRST and abort with
                         502 if unconfirmed. The old path reported success while
                         the card kept being charged.

Degrade, never 500       Every AI path has a deterministic floor. Providers all
                         down still returns a structured result.
```

---

## 🛠 Tech Stack

<table>
  <tr>
    <td align="right"><b>Languages</b></td>
    <td align="center"><a href="https://www.python.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/python-colored.svg" width="40" height="40" alt="Python" title="Python" /></a></td>
    <td align="center"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/javascript-colored.svg" width="40" height="40" alt="JavaScript" title="JavaScript" /></a></td>
    <td align="center"><a href="https://www.typescriptlang.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/typescript-colored.svg" width="40" height="40" alt="TypeScript" title="TypeScript" /></a></td>
    <td align="center"><a href="https://docs.microsoft.com/en-us/cpp/?view=msvc-170" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/c-colored.svg" width="40" height="40" alt="C" title="C" /></a></td>
    <td align="center"><a href="https://developer.mozilla.org/en-US/docs/Glossary/HTML5" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/html5-colored.svg" width="40" height="40" alt="HTML5" title="HTML5" /></a></td>
    <td align="center"><a href="https://www.w3.org/TR/CSS/#css" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/css3-colored.svg" width="40" height="40" alt="CSS3" title="CSS3" /></a></td>
  </tr>
  <tr>
    <td align="right"><b>Backend</b></td>
    <td align="center"><a href="https://www.djangoproject.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/django-colored.svg" width="40" height="40" alt="Django" title="Django / DRF" /></a></td>
    <td align="center"><a href="https://fastapi.tiangolo.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/fastapi-colored.svg" width="40" height="40" alt="FastAPI" title="FastAPI" /></a></td>
    <td align="center"><a href="https://nodejs.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/nodejs-colored.svg" width="40" height="40" alt="Node.js" title="Node.js" /></a></td>
    <td align="center"><a href="https://expressjs.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original.svg" width="40" height="40" alt="Express" title="Express" /></a></td>
    <td align="center"><img src="https://cdn.simpleicons.org/celery/37814A" width="40" height="40" alt="Celery" title="Celery / Celery Beat" /></td>
    <td align="center"><img src="https://cdn.simpleicons.org/swagger/85EA2D" width="40" height="40" alt="Swagger" title="Swagger / OpenAPI" /></td>
  </tr>
  <tr>
    <td align="right"><b>Data</b></td>
    <td align="center"><a href="https://www.postgresql.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/postgresql-colored.svg" width="40" height="40" alt="PostgreSQL" title="PostgreSQL · pgvector · PostGIS" /></a></td>
    <td align="center"><a href="https://www.mysql.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/mysql-colored.svg" width="40" height="40" alt="MySQL" title="MySQL" /></a></td>
    <td align="center"><a href="https://redis.io/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redis/redis-original.svg" width="40" height="40" alt="Redis" title="Redis" /></a></td>
    <td align="center"><a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/mongodb-colored.svg" width="40" height="40" alt="MongoDB" title="MongoDB" /></a></td>
    <td align="center"><a href="https://supabase.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/supabase-colored.svg" width="40" height="40" alt="Supabase" title="Supabase" /></a></td>
    <td align="center"><img src="https://cdn.simpleicons.org/meilisearch/FF5CAA" width="40" height="40" alt="Meilisearch" title="Meilisearch" /></td>
  </tr>
  <tr>
    <td align="right"><b>AI &amp; ML</b></td>
    <td align="center"><img src="https://cdn.simpleicons.org/googlegemini/4285F4" width="40" height="40" alt="Google Gemini" title="Google Gemini · Vertex AI" /></td>
    <td align="center"><img src="https://cdn.jsdelivr.net/npm/simple-icons@latest/icons/openai.svg" width="40" height="40" alt="OpenAI" title="OpenAI" /></td>
    <td align="center"><img src="https://cdn.simpleicons.org/anthropic/D97706" width="40" height="40" alt="Claude AI" title="Anthropic / Claude" /></td>
    <td align="center"><img src="https://cdn.simpleicons.org/langchain/1C3C3C" width="40" height="40" alt="LangChain" title="LangChain" /></td>
    <td align="center"><img src="https://cdn.simpleicons.org/huggingface/FFD21E" width="40" height="40" alt="Hugging Face" title="Hugging Face" /></td>
  </tr>
  <tr>
    <td align="right"><b>Frontend</b></td>
    <td align="center"><a href="https://reactjs.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/react-colored.svg" width="40" height="40" alt="React" title="React" /></a></td>
    <td align="center"><a href="https://nextjs.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nextjs/nextjs-original.svg" width="40" height="40" alt="Next.js" title="Next.js" /></a></td>
    <td align="center"><a href="https://tailwindcss.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/tailwindcss-colored.svg" width="40" height="40" alt="Tailwind CSS" title="Tailwind CSS" /></a></td>
    <td align="center"><a href="https://vitejs.dev/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/vite-colored.svg" width="40" height="40" alt="Vite" title="Vite" /></a></td>
    <td align="center"><a href="https://www.framer.com/motion/" target="_blank" rel="noreferrer"><img src="https://cdn.simpleicons.org/framer/0055FF" width="40" height="40" alt="Framer Motion" title="Framer Motion" /></a></td>
    <td align="center"><img src="https://cdn.simpleicons.org/shadcnui/000000" width="40" height="40" alt="shadcn/ui" title="shadcn/ui" /></td>
  </tr>
  <tr>
    <td align="right"><b>Infra &amp; Tools</b></td>
    <td align="center"><a href="https://www.docker.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/docker-colored.svg" width="40" height="40" alt="Docker" title="Docker · Compose" /></a></td>
    <td align="center"><a href="https://aws.amazon.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/aws-colored.svg" width="40" height="40" alt="AWS" title="AWS" /></a></td>
    <td align="center"><img src="https://cdn.simpleicons.org/nginx/009639" width="40" height="40" alt="Nginx" title="Nginx" /></td>
    <td align="center"><img src="https://cdn.simpleicons.org/render/000000" width="40" height="40" alt="Render" title="Render" /></td>
    <td align="center"><a href="https://git-scm.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/git-colored.svg" width="40" height="40" alt="Git" title="Git" /></a></td>
    <td align="center"><a href="https://www.linux.org" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/linux-colored.svg" width="40" height="40" alt="Linux" title="Linux" /></a></td>
    <td align="center"><img src="https://cdn.simpleicons.org/pytest/0A9EDC" width="40" height="40" alt="pytest" title="pytest" /></td>
  </tr>
</table>

---

## 🚀 Products

Software with real users behind it.

| Product | What it does | Stack | Status |
|---|---|---|---|
| **[Lune](https://lunehire.com)** | Hiring built on verified evidence instead of CVs. Proctored assessments, portable Skill Passports, a gig marketplace with escrow, and hiring pipelines on one backend. I own the backend architecture | Django · DRF · PostgreSQL · pgvector · Celery · Redis · Gemini · Vertex AI | 🟢 Live |
| **[Smart ATS](https://smart-ats.algorithmia-se.com)** | Started standalone at **300+ job seekers**, now runs inside Lune as CV Studio, Resume Screen and the skill intelligence layer. Three-layer anti-fabrication so an AI CV builder cannot invent your career | Django · Celery · Redis · Gemini · Docker | 🔵 Part of Lune |
| **[Eventraka](https://eventraka.vercel.app)** | AI Event Intelligence Platform. Discovers, deduplicates and enriches events from many sources rather than waiting for organisers to publish | Next.js · Django · FastAPI · PostGIS · Meilisearch · Scrapy | 🟡 Early access |
| **[JechSpace](https://jechspace.app)** | Workspace booking with WebSocket conflict detection and two-way Google Calendar sync. Concurrent bookings resolved server-side with atomic locks. **Hackathon 3rd place** | Django · WebSockets · Google Calendar API · MySQL · AWS | 🟢 Live |

---

## ⚙️ APIs &amp; Backend Services

Where the data model comes first and the failure paths get written before the happy path.

| Service | The interesting part | Stack |
|---|---|---|
| **[Vidannotate](https://github.com/dohoudaniel/vidannotate)** | Turns any video into a timestamped written record. Four resumable stages; Whisper transcribes locally and is fed to the model as **ground truth so it quotes rather than invents** | Python · Gemini · Vertex AI · faster-whisper · ffmpeg |
| **[Telex Monitor](https://github.com/dohoudaniel/mysql-performance-monitor)** | Reports MySQL health into a team's existing chat on a schedule. No extra dashboard nobody opens | FastAPI · MySQL · Webhooks |
| **[RemoSphere](https://remosphere.onrender.com/swagger)** | Job board API with JWT auth, ownership-scoped deletes and public Swagger docs. Built during ALX ProDev Backend | Django · DRF · JWT · Swagger |
| **[Spotter Fuel Route](https://github.com/dohoudaniel/spotter-backend-django)** | US route + cost-optimal fuel stops in **one external API call**. Stations are geocoded offline at import, so runtime is pure NumPy over a corridor | Django · NumPy · SciPy · OSRM |

---

## 🏢 Client Work

Delivered builds averaging **9.1 / 10** on client satisfaction. I owned the backend on every one: data models, algorithms, optimisations, and the calls about what happens when something goes wrong.

| Client | What I built | Live |
|---|---|---|
| **ALX Nigeria Tribe** 🇳🇬 | Community platform for the fitness tribes of the ALX Nigeria network | [↗](https://alx.ng/tribe) |
| **MiraShelf Bookstore** | Independent bookstore catalogue with a staff-managed CMS, no e-commerce overhead | [↗](https://mirashelf.vercel.app) |
| **Acadia Homes** | Real estate CMS with property discovery, filtered search and booking flows | [↗](https://acadiahomesng.vercel.app) |
| **Receipt Generator** | Internal tool for Acadia Homes. Nights and totals derived from the booking, branded PDF in one step | [↗](https://receiptgen4acadia.vercel.app) |
| **OLM Freight and Logistics** | Freight forwarding and customs site backed by a TypeScript quote API with rate limiting, honeypot and duplicate detection, delivered by email | [↗](https://olmfreightlogistics.com) |
| **Amovel Global Logistics** | International air, sea and land freight platform with routed inquiries | [↗](https://www.amovelglobal.com) |
| **Enybel Global Logistics** | Freight forwarding and customs clearing platform | [↗](https://enybelgloballogistics.com) |
| **Osmarom Nigeria Limited** | Corporate platform for an engineering and construction firm, tuned for low bandwidth | [↗](https://osmaromnigerialimited.vercel.app) |

---

## 🧪 Side Projects

Where the reps were earned. Systems design, resource management and problem-solving without breaking the experience.

| Project | What it does | Stack |
|---|---|---|
| **[MeloTech](https://melotech.vercel.app)** | Three interview questions from a job title. One input, one action, no signup. Scope discipline as a feature | Python · React |
| **[VeriFact AI](https://myaipoweredfactchecker.vercel.app)** | Paste text or a screenshot, get an explainable verdict with cited sources before you share | React · Gemini · Search Grounding |
| **[PuzzleRender](https://puzzle-render.vercel.app)** | Custom puzzles rendered to print-ready PDFs with per-user history. ALX Backend Specialization capstone, built with a team | Django · Next.js · MySQL |
| **[FocusSprint](https://myfocussprint.vercel.app)** | A focus timer that treats mental state as a first-class input, not an afterthought | React · TypeScript · Django |
| **[IP Intel Discoverer](https://findmyipinfo.vercel.app)** | IP and domain intelligence without needing a security background, including what your own address reveals | Next.js · TypeScript · Redis |
| **[Precious' Signature](https://precious-signature.vercel.app)** | Storefront for a Lagos home kitchen. Orders route to WhatsApp, where the business already runs | React · TypeScript · Tailwind |
| **[Mira's Cakes &amp; Pastries](https://mirascakesandpastries.vercel.app)** | Made-to-order bakery where the gallery is the product page and every order starts as a conversation | React · TypeScript · Tailwind |

---

## 🐧 Open Source · Outreachy May 2026

Contributed to the **[Fedora Project](https://fedoraproject.org)** during the Outreachy May 2026 cohort, working on **Ramalama's RAG pipeline** and exploring **Docling**, the document processing tool behind it.

Coming from projects I built from scratch, this meant the opposite: arriving at a codebase I did not write, learning its conventions in public, and communicating every step through Matrix and Forgejo where anyone could read it.

I completed the contribution phase and was not selected for the internship. The work itself is permanent, sitting in issue threads and the Fedora record, and a selection outcome does not undo it.

[![View Full Portfolio](https://img.shields.io/badge/Outreachy_Portfolio-dohoudanielfavour.me/outreachy-9333EA?style=flat-square&logo=fedora&logoColor=white)](https://dohoudanielfavour.me/outreachy)

---

## 🌍 Community

**[Algorithmia SE](https://www.algorithmia-se.com/)** started as an ALX SE study group and grew into a **1,000+ member** open-source engineering community that ships real products, Smart ATS among them.

[![Website](https://img.shields.io/badge/Website-algorithmia--se.com-F97316?style=flat-square&logo=globe&logoColor=white)](https://www.algorithmia-se.com/)
[![GitHub](https://img.shields.io/badge/GitHub-Algorithmia--SE-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Algorithmia-SE)
[![X](https://img.shields.io/badge/X-@Algorithmia__SE-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/Algorithmia_SE)
[![YouTube](https://img.shields.io/badge/YouTube-@Algorithmia__SE-FF0000?style=flat-square&logo=youtube&logoColor=white)](https://www.youtube.com/@Algorithmia_SE)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-algorithmiase-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/company/algorithmiase/)

---

## 🏆 Certifications

| Certification | Issuer | Year | Level |
|---|---|---|---|
| Google Africa Developer Scholarship | Google Developers | 2021 | Professional |
| ALX Software Engineering, Backend Specialization | ALX Africa | 2024 | Professional |
| ALX Ventures Founder Academy | ALX Ventures | 2024 | Professional |
| ALX ProDev Backend | ALX Africa | 2025 | Professional |
| ALX AI for Developers 1 | ALX Africa | 2025 | Professional |
| ALX AI for Developers 2 | ALX Africa | 2025 | Advanced |
| ALX Cybersecurity Program | ALX Africa | 2026 | Professional |
| OctoPrep AI, Career Preparation Program | OctoPrep.ai | 2026 | Professional |

---

## ✍️ Technical Writing

- [ALX SE: Landing Your First Job In Tech](https://studentsofalxse.hashnode.dev/alx-se-landing-your-first-job-in-tech)
- [Building A Startup As A Software Engineer, Insights from Julien Barbier](https://studentsofalxse.hashnode.dev/julien-barbier-building-a-startup-as-an-swe)
- [Building Side Projects: The Secret to Long-Term Success in Tech](https://studentsofalxse.hashnode.dev/julien-barbier-alxse-building-side-projects)
- [A Yearlong Odyssey: #365DaysOfSoftwareEngineering](https://dohoudanielfavour.hashnode.dev/a-yearlong-odyssey-365daysofsoftwareengineering)
- [What Happens When You Type 'www.google.com' and Press Enter?](https://medium.com/@dohoudanielfavour/what-happens-when-you-type-www-google-com-in-your-web-browser-and-press-enter-b4ded1b99b90)

---

## 📈 GitHub Stats

<div align="center">
  <img height="180em" src="https://github-readme-stats-eight-theta.vercel.app/api?username=dohoudaniel&show_icons=true&theme=algolia&include_all_commits=true&count_private=true"/>
  <img height="180em" src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=dohoudaniel&layout=compact&langs_count=8&theme=algolia"/>
</div>

<div align="center">
  <img src="https://ghchart.rshah.org/3B82F6/dohoudaniel" width="100%" alt="Daniel Favour Dohou's GitHub contribution graph for the last year"/>
</div>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=dohoudaniel&label=Profile%20Views&style=for-the-badge&color=3B82F6" alt="Profile Views"/>
</div>

---

## 📰 Press &amp; Recognition

- 🏆 **ALX SE Superman**, ALX Africa, 2022 to present
- 📰 **[This Day Live](https://www.thisdaylive.com/2023/11/21/from-a-shy-rookie-to-a-tech-leader-the-story-of-daniel-dohou/)** · *"From A Shy Rookie to A Tech Leader: The Story of Daniel Dohou"*
- 🌟 **[Faces of ALX SE](https://www.facesofalxse.com/p/daniel-dohou-the-community-building)** · *"Daniel Dohou: The Community Building Maestro"*
- 🎬 **[ALX Nigeria #MyALXStory](https://www.instagram.com/reel/DPEO4l-DDXp/)** · *"It's a whole movie!"* is how ALX Nigeria described my journey with them

---

## 🤝 Let's Connect

<div align="center">

[![Portfolio](https://img.shields.io/badge/dohoudanielfavour.me-3B82F6?style=for-the-badge&logo=globe&logoColor=white)](https://dohoudanielfavour.me)
[![X](https://img.shields.io/badge/@DohouDaniel10-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/DohouDaniel10)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/dohoudanielfavour)
[![Hashnode](https://img.shields.io/badge/Blog-2962FF?style=for-the-badge&logo=hashnode&logoColor=white)](https://dohoudanielfavour.hashnode.dev)
[![Gmail](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dohoudanielfavour@gmail.com)

</div>

---

<div align="center">
  <sub>A Beautiful Mind 🌼 · Lagos, Nigeria</sub>
</div>
