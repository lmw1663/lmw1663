# Hi, I'm Minwoo Lee 👋

I'm a developer who **spots everyday problems and builds the tools to fix them**.
I built an iOS app because checking cigarette inventory at my convenience store job was tedious, and I'm now taking a breakup-recovery app from concept to launch.

- Currently building **Reason · 그날 이후 (After That Day)**, a breakup recovery app on React Native + Supabase
- Learning backend architecture (async queues, caching), database security (RLS), and AI feature design
- I work alongside AI tools to ship fast, and I document the reasoning behind every design decision
- Reach me at `a01023931663@gmail.com`

<br>

## 🛠 Tech Stack

**Mobile**
![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)

**Language**
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)

**Backend & DB**
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)

**Tools**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=anthropic&logoColor=white)

<br>

## 🚀 Featured Projects

### 💔 [Reason · After That Day](https://github.com/lmw1663/Reason-afterThatDay)
> A mobile app that helps people make the "get back together or let go" decision **with data instead of impulse**, and supports their recovery afterward

`React Native` `Expo` `TypeScript` `Zustand` `Supabase` `Edge Functions` `OpenAI API`

- **Row Level Security** on every table; all AI calls go through an **Edge Function proxy** so no keys reach the client
- **SSE streaming** for AI responses, push notifications and scheduled jobs via `pg_cron`, cron credentials moved into **Vault**
- Screens, questions, and tone branch across 20 user personas, with a **custom lint rule** that keeps internal persona codes out of the UI
- **Clinically informed design**, including a C-SSRS-based crisis assessment and safety lock
- 249 commits · 40 DB migrations · 12 Edge Functions · 596 unit tests

### 🎤 [devInterview](https://github.com/lmw1663/devInterview)
> Backend for a **technical interview practice platform** where AI grades your answers

`Express` `TypeScript` `Prisma` `PostgreSQL` `Redis` `BullMQ` `Docker`

- Answer grading offloaded to a **BullMQ async queue** (returns 202, then the client polls job status)
- **Redis cache-aside** caching plus security middleware (helmet, rate limiting)
- JWT auth, Swagger API docs, and a Docker Compose dev environment

### 🚬 [CigaretteCounter](https://github.com/lmw1663/cigaretteCounter)
> An iOS app I built to solve the **cigarette inventory checks** I dealt with at my convenience store job

`Swift` `SwiftUI` `Flask` `Firebase`

- Supports 212 brands with auto-generated barcodes
- Automatically reconciles shelf, stockroom, and POS counts, with color-coded discrepancies
- One-handed touch-grid input for fast counting

<br>

## 📂 Other Projects

| Project | Description | Stack |
|---|---|---|
| [tp_game](https://github.com/lmw1663/tp_game) | Single and multiplayer maze game | Android, Java |
| [instaDB](https://github.com/lmw1663/instaDB) | Instagram clone (database course team project) | Java Swing, MySQL |
| [finding_successful_movie](https://github.com/lmw1663/finding_successful_movie) | Box-office success prediction model | Python, AdaBoost, Bagging |
| [Todo_list_app](https://github.com/lmw1663/Todo_list_app) | Dashboard for to-dos, workouts, and sleep | React, Firebase, Netlify |
| [programmers](https://github.com/lmw1663/programmers) | Algorithm problem solutions | Python |

<br>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=lmw1663&show_icons=true&hide_border=true" height="150" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=lmw1663&layout=compact&hide_border=true" height="150" />
</p>
