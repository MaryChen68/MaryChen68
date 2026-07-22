# Hey, I'm Jiamei 👋

**Computer Science & Data Science · web developer · building full-stack, end to end**

I build web applications from the interface down to the database — React and TypeScript on the front,
Node and Java on the back — and I care about writing code that the next person can pick up and understand.

I'm a Computer Science junior at Calvin University.

[![Email](https://img.shields.io/badge/jc264%40calvin.edu-D14836?style=flat&logo=gmail&logoColor=white)](mailto:jc264@calvin.edu)
[![LinkedIn](https://img.shields.io/badge/Jiamei%20Chen-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/REPLACE_ME)
[![GitHub](https://img.shields.io/badge/MaryChen68-181717?style=flat&logo=github&logoColor=white)](https://github.com/MaryChen68)

---

## 🛠 Currently Building

### Thoughtful AI — *[AIToolsLab/writing-tools](https://github.com/AIToolsLab/writing-tools)*

- **Shipped the Google Docs add-in.** I own it end to end: an Apps Script sidebar proxying to our
  backend, a webpack target that serves the Docs bundle from staging/prod instead of inlining it, a
  source picker for local development, and a tag linker that jumps to a word across Docs tabs.
- **Made it safe for AI agents to work in.** pytest over the backend's API routes and log writing,
  Playwright E2E for the editor and the chat/revise/draft flows, cross-OS visual-regression baselines,
  and Vitest + Playwright on every PR. Agents can change this codebase without us worrying it breaks.
- **Put the prompts under test.** A set of test documents plus a way to see what the LLM returns for
  each one, and at what latency — so prompt changes stop being guesswork.

### Reflective mind-mapping — *[AIToolsLab/writing-tools/prototype_mindmap](https://github.com/AIToolsLab/writing-tools/prototype_mindmap)*

- **An assistant that isn't allowed to write for you.** It asks questions and mirrors your own words
  back; a validator rejects any reflection whose content words can't be traced to something you
  actually said.
- **Made the idea measurable.** Three comparable levels of constraint, teacher and writer recap views
  reporting level / AI-acceptance / sub-idea coverage, and a Coach Trace panel that shows a writer what
  the system did on their behalf instead of asking them to trust it.
- **Multilingual, by drawing a boundary.** UI strings now build into 30+ static locale bundles; the
  writer's own text goes down a separate path behind a translation memory. Before, both were going to
  OpenAI on every render, toggle, and language switch.

<!-- TODO: if you're an author on the UIST paper, say so here (and your authorship position). I left it
     out because I can't verify it from the repo. -->

## 🧭 How I Work

- **Read before writing.** Most of the work on an existing codebase is understanding what's already
  there. I'd rather spend an hour reading than an afternoon undoing.
- **Small, reviewable changes.** Commits that do one thing, with a message that says which thing.
- **Understand the tools I use.** Frameworks and AI assistants both speed things up — but I want to be
  able to explain every line I ship, whoever or whatever wrote it first.

<!-- TODO: these are placeholders that fit most students. Swap in your own principles when you have them. -->

## 📂 Selected Public Work

- **[AIToolsLab/writing-tools](https://github.com/AIToolsLab/writing-tools)** — The lab's writing-support
  platform, shipped as **Thoughtful AI**. My work is the Google Docs add-in, the frontend and backend
  test suites, and CI.
- **`prototype_mindmap`** — The UIST reflective mind-mapping prototype. A separate research effort from
  the Thoughtful AI product. <!-- TODO: add the link — same repo under a subdirectory, or its own repo? -->
- **[monopoly-service](https://github.com/MaryChen68/monopoly-service-mary)** — [CS262 team project.
  Describe what the service does and which part you built.]

<!-- TODO: add more as you publish them. -->

## ⚙️ Tech Stack

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)

**Backend & Data**

![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)

**Testing & Build**

![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat&logo=playwright&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat&logo=vitest&logoColor=white)
![Pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat&logo=pytest&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)

**Tools**

![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat&logo=visualstudiocode&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat&logo=postman&logoColor=white)
