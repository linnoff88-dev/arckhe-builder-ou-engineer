# Builder or Engineer: Get Ready for Your Next AI Role

[![Builder or Engineer: Get Ready for Your Next AI Role](guia/assets/banner-en.jpg)](https://inematds.github.io/builder-ou-engineer/guia/en/)

**🇧🇷 [Português](README.md) · 🇺🇸 [English](README.en.md) · 🇪🇸 [Español](README.es.md)**

## What It Is

Companies that make the most use of AI already distinguish between two entry-level profiles: the **AI Engineer**, who builds models and systems, and the **AI Builder**, who comes from any field and uses AI to solve business problems. iFood pays R$ 5,200 to R$ 7,000 per month to train both profiles through its genAI program, and applications for the 2027 cohort closed on 17/11/2026. The **Builder or Engineer Plan** is a free 12-week plan to get you ready for the next cohort, or any AI role: discover your profile, follow a learning path with free INEMA.CLUB courses, complete a project with before-and-after metrics, and practice every stage of the selection process with AI.

It is not affiliated with iFood and does not guarantee a job: it helps you prepare.

## 📖 User Guide

Full guide: **https://inematds.github.io/builder-ou-engineer/guia/en/**

🎬 Video: in production (it will be added to the guide when published).

## Start by Asking Your AI

Paste this into ChatGPT, Claude, or Gemini:

```
Be my coach to help me get into an AI internship or residency program (like iFood's genAI), using simple language.
1. Ask me one question at a time and give me a test to find out whether I'm more of an AI Builder or an AI Engineer. Also ask what I'm studying and when I graduate.
2. Put together a 12-week plan, about 5 hours per week, following the "Builder or Engineer Plan" at https://inematds.github.io/builder-ou-engineer/guia/en/ and using the free courses mentioned there.
3. Help me choose a proof-of-work project that solves someone's real problem and has a before-and-after metric.
4. When I say "practice", act as the evaluator for each stage of the selection process. At the end of each one, give me a score and tell me what I missed.
Be honest: if I'm weak in something, tell me.
```

## The Reference Program (verified on 22/11/2026)

- 2nd edition of iFood's genAI program: applications open from 27/10 to 17/11/2026, program starts in February 2027.
- Internship: graduation between Jul/2027 and Jan/2029, stipend R$ 5,200. Residency: graduated between Dec/2025 and Dec/2026, stipend R$ 7,000.
- AI Engineer: computer science, software engineering, mathematics, statistics, physics. AI Builder: any educational background, no in-depth coding required.
- Sources: [official announcement](https://institucional.ifood.com.br/releases/programa-gen-ia/) · [careers page](https://carreiras.ifood.com.br/gen-ai/).

---

## The Process, from Start to Finish

Who does what: 🧠 you (with AI by your side) · 🤖 your AI (ChatGPT, Claude, Gemini) · ⚙️ no scripts: the plan is all reading and practice.

| # | Step | Where | Who |
|---|---|---|---|
| 1 | Discover your profile (Builder or Engineer) | prompt above or [guide#perfis](https://inematds.github.io/builder-ou-engineer/guia/en/#perfis) | 🤖 + 🧠 |
| 2 | Weeks 1–2: use AI for 3 tasks and record the time before and after | [PLANO.md](PLANO.md) (in Portuguese) | 🧠 |
| 3 | Weeks 3–6: follow your profile's learning path (free courses) | [PLANO.md](PLANO.md#semana-a-semana) (in Portuguese) | 🧠 |
| 4 | Weeks 7–10: proof-of-work project + 1-page portfolio | [PLANO.md](PLANO.md#semana-a-semana) (in Portuguese) | 🧠 |
| 5 | Weeks 11–12: practice the 6 selection stages | [practice prompts](PLANO.md#pedidos-de-treino-cole-na-sua-ia) (in Portuguese) | 🤖 + 🧠 |
| 6 | Until the next cohort: one project per month | — | 🧠 |

## Technical Setup

There is nothing to install: the project is a static guide (`guia/index.html`, `guia/en/`, `guia/es/`) and a text plan (`PLANO.md`). To view the guide locally:

```bash
git clone https://github.com/inematds/builder-ou-engineer.git
cd builder-ou-engineer && python3 -m http.server 8000   # open http://localhost:8000/guia/
```

Publishing: GitHub Pages via the `.github/workflows/pages.yml` Action (repo root).

## License

MIT. Free on inema.club, directly on the internet.