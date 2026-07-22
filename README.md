# Hey, I'm Jiamei 👋

**Computer Science student · web developer · building full-stack, end to end**

I build web applications from the interface down to the database — React and TypeScript on the front,
Node and Java on the back — and I care about writing code that the next person can pick up and understand.

I'm a Computer Science junior at Calvin University.

[![Email](https://img.shields.io/badge/Email-jc264%40calvin.edu-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:jc264@calvin.edu)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Jiamei%20Chen-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/REPLACE_ME)
[![GitHub](https://img.shields.io/badge/GitHub-MaryChen68-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/MaryChen68)

---

## 🚧 Currently Building

- **Reflective mind-mapping** *(research, [AIToolsLab/writing-tools](https://github.com/AIToolsLab/writing-tools))* —
  An AI writing tool built on an inversion of the usual deal: the assistant is not allowed to write for
  you. It asks questions and mirrors your own words back, and a validator rejects any reflection whose
  content words can't be traced to something you actually said. I built the instrumentation that makes
  the idea measurable — three comparable levels of constraint, plus teacher and writer recap views
  reporting level, AI-acceptance, and sub-idea coverage — and the Coach Trace panel, which shows a
  writer what the system did on their behalf instead of asking them to trust it.

- **Making that prototype multilingual** — Whole-page translation with a fixed writing language,
  detected from the writer's first message, persisted, and always overridable. The interesting part was
  a boundary rather than a feature: interface copy and the writer's own words were both being sent to
  OpenAI on every render, toggle, and language switch. They're separate now — UI strings are generated
  into 30+ static locale bundles at build time, while the writer's text goes through its own path
  behind a translation memory. Same screen, far fewer calls, and the writer's words stop being treated
  as UI.

- **The add-in, in production** *(same repo)* — I own the Google Docs add-on end to end: an Apps Script
  sidebar proxying to our backend, a webpack target for the Docs bundle, serving that bundle from
  staging/prod instead of inlining it (which meant dropping HtmlWebpackPlugin so it would build inside
  the Docker image), a localhost/staging/prod source picker for development, and a tag linker that
  jumps to a word across Docs tabs. Under it is the safety net I put in first: pytest coverage for the
  backend's API routes, username validation, and log writing; Playwright E2E specs for the editor and
  the chat/revise/draft flows against a mock backend; cross-OS visual-regression baselines; and CI that
  runs Vitest and Playwright on every PR — so we can let AI agents work in this codebase without
  worrying about it breaking.

<!-- TODO: if you're an author on the paper, say so here (Nhyira lists co-first author). I left it out
     because I can't verify your authorship position from the repo. -->

## 💭 How I Work

- **Read before writing.** Most of the work on an existing codebase is understanding what's already
  there. I'd rather spend an hour reading than an afternoon undoing.
- **Small, reviewable changes.** Commits that do one thing, with a message that says which thing.
- **Understand the tools I use.** Frameworks and AI assistants both speed things up — but I want to be
  able to explain every line I ship, whoever or whatever wrote it first.

<!-- TODO: these are placeholders that fit most students. Swap in your own principles when you have them. -->

## 📌 Selected Public Work

- **[AIToolsLab/writing-tools](https://github.com/AIToolsLab/writing-tools)** — The lab's writing-support
  platform. My work is in the Google Docs add-on, the frontend and backend test suites and CI, and the
  mind-map research prototype.
- **[monopoly-service](https://github.com/MaryChen68/monopoly-service-mary)** — [CS262 team project.
  Describe what the service does and which part you built.]

<!-- TODO: add more as you publish them. -->

## 🧰 Tech Stack

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Backend & Data**

![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

**Testing & Build**

![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)
![Pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

**Tools**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)

## 📊 GitHub

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=MaryChen68&show_icons=true&include_all_commits=true&hide_border=true&theme=github_dark_dimmed">
  <img alt="Jiamei's GitHub stats" src="https://github-readme-stats.vercel.app/api?username=MaryChen68&show_icons=true&include_all_commits=true&hide_border=true">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=MaryChen68&layout=compact&hide_border=true&theme=github_dark_dimmed">
  <img alt="Top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=MaryChen68&layout=compact&hide_border=true">
</picture>

## 🎓 Beyond Code

[Anything that isn't a repo but is still you — coursework you loved, a job or campus role, a language
you speak, something you make outside a terminal. Two or three sentences is plenty. This is the section
recruiters actually remember.]

<!-- TODO -->
