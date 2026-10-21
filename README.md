<img width="100%" alt="Lucas de Oliveira Pimentel, full-stack Python developer with a back-end focus" src="https://capsule-render.vercel.app/api?type=waving&color=0:0b0e18,55:7a6128,100:c9a84c&height=210&section=header&text=Lucas%20de%20Oliveira%20Pimentel&fontSize=44&fontColor=f2ead0&fontAlignY=36&desc=Full-Stack%20Python%20Developer%20%E2%80%A2%20Back-end%20Focus&descSize=18&descAlignY=56&animation=fadeIn" />

<div align="center">

<img alt="Full-stack Python developer with a back-end focus. I build APIs with FastAPI, PostgreSQL and Redis, and the React front ends that consume them. Open to remote work." src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=21&duration=3200&pause=900&color=C9A84C&center=true&vCenter=true&width=620&height=48&lines=Full-Stack+Python+Developer+%F0%9F%90%8D;Back-end+focus%3A+FastAPI%2C+PostgreSQL+%26+Redis;React+front+ends+that+consume+my+APIs;Open+to+remote+work+%F0%9F%8C%8E" />

<br/>

<a href="https://ilucasoliveira.dev"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-ilucasoliveira.dev-c9a84c?style=for-the-badge&logo=googlechrome&logoColor=white&labelColor=0b0e18" /></a>
<a href="https://www.linkedin.com/in/ilucasoliveira"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-ilucasoliveira-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0b0e18" /></a>
<a href="mailto:lucasoliveirapimentel.dev@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-Get%20in%20touch-ff6a2b?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0b0e18" /></a>
<a href="https://ilucasoliveira.dev/cv-lucas-de-oliveira-en.pdf"><img alt="Résumé (PDF)" src="https://img.shields.io/badge/R%C3%A9sum%C3%A9-PDF-8fc48f?style=for-the-badge&logo=readdotcv&logoColor=white&labelColor=0b0e18" /></a>

</div>

---

## 🧙‍♂️ About me

- 🐍 **Full-stack Python developer with a back-end focus**: I design the APIs and build the **React** front ends that consume them.
- 📍 Based in **Barbacena, MG, Brazil** · 🎓 Computer Science student at **UNA** · 🌎 **open to remote work**.
- 🔐 I like the parts that are easy to get wrong: **authentication**, **caching**, **data integrity** and **CI that blocks bad deploys**.
- 📝 My project READMEs explain *why* things are built the way they are, trade-offs included.
- 📊 Before code, I spent almost 5 years working remotely in **data quality**, where consistent data was the whole job.

---

## 🛠️ Tech stack

<div align="center">

**Back end**<br/>
<img alt="Python, FastAPI, PostgreSQL and Redis" src="https://skillicons.dev/icons?i=py,fastapi,postgres,redis&theme=dark" />

**Front end**<br/>
<img alt="React, TypeScript, JavaScript, Vite, Tailwind CSS and CSS" src="https://skillicons.dev/icons?i=react,ts,js,vite,tailwind,css&theme=dark" />

**Infrastructure and delivery**<br/>
<img alt="Docker, GitHub Actions, Vercel, Supabase and Git" src="https://skillicons.dev/icons?i=docker,githubactions,vercel,supabase,git&theme=dark" />

<sub>Also in the projects below: SQLAlchemy 2.0 · Pydantic v2 · Alembic · httpx · JWT · OAuth2 · Poetry · pytest · Vitest · Playwright · axe-core · Ruff · Render</sub>

</div>

---

## 🚀 Featured projects

<table>
<tr>
<td width="50%" valign="top">

<h3>🎧 MySoundPrint</h3>

Turns your **Spotify listening history** into personal statistics: how concentrated your taste is, which decades your music comes from, what left your rotation and when you listen.

<img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
<img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
<img alt="Redis" src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
<img alt="React" src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
<img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />

<a href="https://mysoundprint.vercel.app/demo"><img alt="Live demo, no account needed" src="https://img.shields.io/badge/%E2%96%B6%20Live%20demo-no%20account%20needed-1DB954?style=for-the-badge" /></a>

<a href="https://github.com/ilucasoliveira/mysoundprint-api">API repo</a> · <a href="https://github.com/ilucasoliveira/mysoundprint-web">Web repo</a> · <a href="https://mysoundprint-api.onrender.com/docs">API docs</a>

<details>
<summary><b>✨ Highlights</b></summary>

- OAuth2 Authorization Code Flow written **by hand**, with the `state` in Redis consumed atomically via `GETDEL`
- Automatic token refresh, per-user Redis cache and a short retry on Spotify `429`
- Hourly GitHub Actions job collects history; duplicates blocked by `ON CONFLICT DO NOTHING`
- CI runs Ruff + pytest and only deploys when the checks pass

</details>

</td>
<td width="50%" valign="top">

<h3>📚 My Own BookShelf</h3>

A **full-stack digital library**: accounts, reading status, quarter-star ratings, notes, favorites, profile photos and book search via Google Books.

<img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
<img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
<img alt="Supabase" src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white" />
<img alt="React" src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
<img alt="Playwright" src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white" />

<a href="https://my-own-bookshelf.vercel.app"><img alt="Live app" src="https://img.shields.io/badge/%E2%96%B6%20Live%20app-try%20as%20visitor-c9a84c?style=for-the-badge" /></a>

<a href="https://github.com/ilucasoliveira/personal-library-api">API repo</a> · <a href="https://github.com/ilucasoliveira/personal-library-frontend">Front-end repo</a> · <a href="https://bookshelf-demo-api.onrender.com/docs">API docs</a>

<details>
<summary><b>✨ Highlights</b></summary>

- Every book query is scoped to the logged-in user; errors carry stable codes
- Visitor mode enforced **by the API**: read-only examples, automatic cleanup
- Design system built from scratch: 4 themes, PT/EN, installable PWA
- CI with pytest, Vitest and Playwright + axe-core accessibility checks

</details>

</td>
</tr>
<tr>
<td width="50%" valign="top">

<h3>📈 Portfolio Tracker API</h3>

Record **buy and sell transactions** and get positions, average cost and profit or loss calculated from that history, with live B3 quotes from brapi.

<img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
<img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
<img alt="Redis" src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
<img alt="JWT" src="https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white" />
<img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />

<a href="https://github.com/ilucasoliveira/portfolio-tracker-api"><img alt="View repository" src="https://img.shields.io/badge/%F0%9F%93%82%20View-repository-7a6128?style=for-the-badge" /></a>

<details>
<summary><b>✨ Highlights</b></summary>

- Stores transactions, never running positions: history is the source of truth
- Money as `NUMERIC` / `Decimal`, never `float`
- Quotes cached per ticker; if the provider is down, the portfolio still answers
- Unit tests + integration tests against an isolated Postgres

</details>

</td>
<td width="50%" valign="top">

<h3>⚡ Pokédex API</h3>

**EBAC final project.** A REST API for Pokémon with paginated CRUD, many-to-many types and **import straight from PokéAPI** by name or number.

<img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
<img alt="Redis" src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
<img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
<img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" />
<img alt="34 tests" src="https://img.shields.io/badge/tests-34-8fc48f?style=flat-square&logo=pytest&logoColor=white" />

<a href="https://pokedex-api-h46x.onrender.com/docs"><img alt="Live API docs" src="https://img.shields.io/badge/%E2%96%B6%20Live-API%20docs-ff6a2b?style=for-the-badge" /></a>

<a href="https://github.com/ilucasoliveira/pokedex-api">Repository</a>

<details>
<summary><b>✨ Highlights</b></summary>

- JWT on write routes; Redis cache on reads, with fallback to the database
- 34 tests covering success and error paths of every endpoint
- Pipeline: tests → Docker build → publish to GHCR → deploy to Render

</details>

</td>
</tr>
</table>

<sub>⏳ The APIs run on Render's free tier, so the first request after some idle time can take up to a minute.</sub>

### 🧩 More on GitHub

| | Project | What it is |
|:-:|---|---|
| 🏰 | [Portfolio](https://github.com/ilucasoliveira/portfolio) + [contact API](https://github.com/ilucasoliveira/portfolio-lucas-api) | Bilingual React site with a FastAPI back end that sends messages through Resend, with rate limiting and a honeypot against spam |
| 🎬 | [Movies API](https://github.com/ilucasoliveira/movies-api) | Async API for tracking watched movies and series, with many-to-many genres and Redis cache-aside |
| 📖 | [Gerenciador de Livros](https://github.com/ilucasoliveira/gerenciador-de-livros-em-python) | EBAC course project that grew module by module: Celery, Kafka, ELK Stack and Kubernetes as study material |
| 🗓️ | [Daily Python Exercises](https://github.com/ilucasoliveira/daily-python-exercises) | One short exercise a day on Python fundamentals and back-end tools |

---

## 💼 Experience

**📊 Data Quality Assistant** · Neogrid (formerly Lett Digital) · Remote · *Oct 2021 – Jun 2026*<br/>
<sub>Freelance until Nov 2022, then hired full-time after Neogrid acquired Lett Digital.</sub>

- 🔎 Reviewed about **1,000 SKUs a day** across the Nestlé, Ambev and PepsiCo catalogs, keeping product data consistent and traceable.
- 🧭 Ran the daily meetings of the **6-person Setup team** and split the ClickUp backlog to balance the workload.
- 🚨 Resolved a critical incident with about **200 Nestlé SKUs** wrongly left unmonitored, coordinating the client, Delivery and Customer Success until it was **fixed the same day**.
- 📝 Documented business rules in Notion and Trello, reducing reliance on individual knowledge and speeding up onboarding.

## 🎓 Education

- 🖥️ **B.Sc. in Computer Science**, UNA · *expected Dec 2027*
- 🐍 **Full Stack Python**, EBAC · *May – Dec 2026, in progress*

<img width="100%" alt="" src="https://capsule-render.vercel.app/api?type=waving&color=0:c9a84c,45:7a6128,100:0b0e18&height=120&section=footer" />
