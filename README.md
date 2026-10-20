<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c1d,55:2b2050,100:e8834a&height=220&section=header&text=Nazar%20Akanov&fontColor=ffffff&fontSize=64&fontAlignY=36&desc=AI%20%2F%20ML%20Engineer%20%C2%B7%20Kazakhstan&descSize=20&descAlignY=58&animation=fadeIn" alt="Nazar Akanov, AI and ML Engineer from Kazakhstan" width="100%" />
</p>

<p align="center">
  <a href="https://portfolio-alpha-sandy-krad8msap8.vercel.app">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3200&pause=900&color=E8834A&center=true&vCenter=true&width=640&lines=I+build+AI+agents+that+act%2C+not+just+chat;2x+medalist%2C+National+AI+Olympiad;Hackathon+winner+%C2%B7+FLEX+finalist;Web%2C+mobile%2C+and+the+models+behind+them" alt="I build AI agents that act, not just chat. Two-time medalist at the National AI Olympiad. Hackathon winner and FLEX finalist. Web, mobile, and the models behind them." />
  </a>
</p>

<p align="center">
  <a href="https://portfolio-alpha-sandy-krad8msap8.vercel.app"><img src="https://img.shields.io/badge/Portfolio-e8834a?style=for-the-badge&logo=threedotjs&logoColor=white" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/nazar-akanov-7554a92bb/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://t.me/akanovn"><img src="https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram" /></a>
  <a href="https://x.com/AkanovNazar"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X" /></a>
  <a href="https://www.instagram.com/akanov.nazar/"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" /></a>
</p>

I'm Nazar, an AI & ML engineer from Kazakhstan, olympiad medalist, hackathon winner, and FLEX exchange alum. I build AI products end to end: the models and retrieval underneath, the backend that serves them, and the web and mobile apps people actually touch.

My flagship is **[Bariweb](https://bariweb.vercel.app)**, an AI agent that makes any website accessible with two lines of code. It reads the page, pulls context from a vector index of the whole site, and then clicks, navigates and fills in forms for the user from a typed or spoken request in Kazakh, Russian or English.

- **Building:** LLM agents that take real actions, RAG pipelines, voice interfaces
- **Going deeper into:** fine-tuning and evaluation, NLP, computer vision, MLOps
- **Shipping style:** from the model all the way to the CI/CD that deploys it

## Track record

| Achievement | Year |
|---|---|
| 🥉 **Bronze (Absolute 8)**, International AI Olympiad FAIO: 7 countries, 500 teams |2025 |
| 🥇 **Gold**, NIS AI Olympiad (2K+ students) | 2024 |
| 🥈 **Silver**, National Computer Science Olympiad | 2023 |
| 🥉 **Bronze ×2**, National AI Olympiad | 2023, 2024 |
| 🏆 **1st place**, Digitalization Day Hackathon (regional), $1K prize | |
| 🌎 **FLEX Finalist** (<1% acceptance rate), exchange year in Georgia, USA | 2024–2025 |


<br>

<p align="center">
  <a href="https://portfolio-alpha-sandy-krad8msap8.vercel.app">
    <img src="assets/portfolio.jpg" alt="My portfolio site: a low-poly 3D room at night with a glowing desk setup and the name Nazar Akanov in large dot-matrix letters" width="100%" />
  </a>
  <br>
  <sub><b><a href="https://portfolio-alpha-sandy-krad8msap8.vercel.app">Step into my room →</a></b> &nbsp;A scroll-driven 3D portfolio built with React Three Fiber. The camera flies through the scene on an endless loop.</sub>
</p>

## Featured work

<p align="center">
  <a href="https://bariweb.vercel.app"><img src="assets/bariweb.jpg" alt="Bariweb landing page: Make any website accessible with two lines of code, with the install snippet and the accessibility button in the bottom-left corner" width="100%" /></a>
</p>

### [Bariweb](https://github.com/Bariweb-ai): an AI accessibility agent for any website

Two lines of code give a site an accessibility toolbar and an AI agent that operates the page for the user: *"pay my property tax"* and it opens the right section, fills in the form and presses the buttons, waiting for confirmation before anything is paid or submitted. Under the hood, a Playwright crawler maps every interactive element on a customer's site, enriches it with intents and multilingual keywords, and indexes it in **Milvus**. At request time the agent retrieves the right elements and replies with executable actions. It handles Kazakh, Russian and English by voice or text through KazLLM / Alem models, generates `alt` and `aria-label` fixes, traces every run in **Langfuse**, and installs from npm as [`bariweb-widget`](https://www.npmjs.com/package/bariweb-widget).

**My part:** backend and AI agent, the embeddable widget SDK, and DevOps (GitLab → GitHub migration and Vercel CI/CD).<br>
`FastAPI` `LLM agents` `RAG` `Milvus` `RAGFlow` `Playwright` `PostgreSQL` `Lit` `Vercel`<br>
[**Live**](https://bariweb.vercel.app) · [**Organization**](https://github.com/Bariweb-ai) · [**npm**](https://www.npmjs.com/package/bariweb-widget)

<br>

<p align="center">
  <a href="https://github.com/Akanov-Kanta/hackathon_taraz"><img src="assets/sonar.jpg" alt="Four SONAR phone screens: sign-in, AI-assisted report creation, a resident's report tracker, and the volunteer incident queue" width="100%" /></a>
</p>

### [SONAR](https://github.com/Akanov-Kanta/hackathon_taraz): a smart city that watches out for its people

A hackathon build from Taraz, shipped by a team in under two days. One platform with four workspaces: **residents** snap a photo of a missing ramp and **OpenAI Vision** drafts the report, **volunteers** run a live incident queue, the **akimat** validates, dispatches and publishes alerts, and **admins** moderate. Critical reports escalate into emergency incidents automatically, and an SOS button files both in one tap. Behind it, a FastAPI service runs **seven ML models**: an LSTM + XGBoost/CatBoost air-quality forecaster, a GNN-style message-passing + Dijkstra **wheelchair router** over a 597-node accessibility graph, traffic congestion, smart-meter anomaly detection, a crowd-aware recommender, a generative-design VAE and DistilBERT sentiment.

**My part:** the Flutter app's architecture, Supabase wiring, maps, auth and government screens, plus the volunteer role.<br>
`Flutter` `React` `Capacitor` `Supabase` `FastAPI` `PyTorch` `XGBoost` `OpenAI Vision` `Google Maps`<br>
[**Code**](https://github.com/Akanov-Kanta/hackathon_taraz)

<br>

<table>
<tr>
<td width="50%"><a href="https://ink-portfolio-shader.vercel.app"><img src="assets/pf-02-ink-shader.jpg" alt="Ink portfolio, shader variant: a red ink vortex behind the name" width="100%" /></a></td>
<td width="50%"><a href="https://nazar-akanov.vercel.app"><img src="assets/pf-02-ink-hybrid.jpg" alt="Ink portfolio, hybrid variant: project cards wrapped in growing red veins and roses" width="100%" /></a></td>
</tr>
<tr>
<td width="50%"><a href="https://nazarakanov.vercel.app"><img src="assets/pf-03-ronin.jpg" alt="Ronin portfolio: a ronin with a straw hat on a temple roof in front of a giant moon" width="100%" /></a></td>
<td width="50%"><a href="https://dossier-indol-psi.vercel.app"><img src="assets/pf-04-dossier.jpg" alt="Dossier portfolio: glowing hand-drawn spiral eyes on black" width="100%" /></a></td>
</tr>
</table>

### [portfolios](https://github.com/Akanov-Kanta/portfolios): four portfolio sites, four different worlds

Every portfolio I've built, open source in one repo. An **igloo.inc-style endless 3D scroll** through a low-poly dev room, a **red-ink anime edit** built on raw WebGL2 shaders, with a beat-synced soundtrack, a **ukiyo-e ronin short film** on a moonlit roof, and a **grayscale case file** of spiral eyes, ink bursts and a hard black-and-white inversion. Plus five bonus landing pages in the same ukiyo-e style.

`Next.js 16` `React Three Fiber` `raw WebGL2` `GSAP` `Lenis` `Web Audio`<br>
[**3D**](https://portfolio-alpha-sandy-krad8msap8.vercel.app) · [**Ink**](https://nazar-akanov.vercel.app) · [**Ronin**](https://nazarakanov.vercel.app) · [**Dossier**](https://dossier-indol-psi.vercel.app) · [**Code**](https://github.com/Akanov-Kanta/portfolios)

<br>

<table>
<tr>
<td width="35%" align="center"><a href="https://github.com/Akanov-Kanta/Courses"><img src="assets/courses.png" alt="NIScourses student schedule screen on a phone" height="300" /></a></td>
<td width="65%" valign="top">

### [NIScourses](https://github.com/Akanov-Kanta/Courses)

A course-enrollment system for a whole school, with three roles, live seat counters and Excel export. Built by a team of three in 2023, **without any AI coding tools**.

`Flutter` `Firebase Auth` `Realtime Database`

</td>
</tr>
</table>

### More builds

- **[CodeHub](https://github.com/chillit/codeHub)**: a Flutter + Firebase learning platform for Python and C++ that has helped **200+ students across Kazakhstan** prepare for the national computer-science exam. Guided exercises with automatic error checking, hints based on the student's mistakes, roadmaps, progress tracking, and friend leaderboards. *(co-built, 2023–2025)*
- **NeSkuchnoPTR**: a hackathon PWA that collects every cultural, social and public event in Petropavl into one feed. It scrapes local Instagram and Telegram channels to stay current, recommends events with AI based on what each user likes, works offline, sends push notifications, and syncs to Google Calendar. *(Flutter, 2024)*

## Experience

**Software Developer Intern, ANTIKOR** · May–July 2023<br>
Built internal accounting tools and automated reporting workflows, with data validation that cut manual errors.

## Toolkit

**AI & ML**

<img src="https://skillicons.dev/icons?i=py,pytorch,tensorflow,sklearn&theme=dark" alt="Python, PyTorch, TensorFlow, scikit-learn" /><br>
<sub>Hugging Face · LangChain · OpenAI API · Ollama · Milvus · Langfuse · NumPy · pandas</sub>

**Full stack**

<img src="https://skillicons.dev/icons?i=ts,react,nextjs,tailwind,fastapi,flutter,dart,postgres,supabase,firebase&theme=dark" alt="TypeScript, React, Next.js, Tailwind CSS, FastAPI, Flutter, Dart, PostgreSQL, Supabase, Firebase" />

**MLOps & cloud**

<img src="https://skillicons.dev/icons?i=docker,kubernetes,githubactions,vercel,linux&theme=dark" alt="Docker, Kubernetes, GitHub Actions, Vercel, Linux" /><br>
<sub>MLflow · Weights & Biases · DVC · Apache Airflow</sub>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:e8834a,45:2b2050,100:0f0c1d&height=120&section=footer" alt="" width="100%" />
</p>
