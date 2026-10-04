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

My flagship is **[Bariweb](https://github.com/Akanov-Kanta/bariweb)**, an AI agent that makes any website accessible with a single script tag. It reads the page, pulls context from a vector index of the whole site, and then clicks, navigates and fills in forms for the user from a typed or spoken request in Kazakh, Russian or English.

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
  <a href="https://bariweb.vercel.app"><img src="assets/bariweb.png" alt="Bariweb landing page: Make your site inclusive in 1 day" width="100%" /></a>
</p>

### [Bariweb](https://github.com/Akanov-Kanta/bariweb): an AI accessibility agent for any website

One `<script>` tag gives a site an accessibility toolbar and an AI agent that operates the page for the user. A Playwright crawler maps every interactive element on a customer's site, enriches it with intents and multilingual keywords, and indexes it in **Milvus**. At request time the agent retrieves the right elements and replies with executable actions (click, navigate, type). It also takes voice commands, handles Kazakh, Russian and English through KazLLM / Alem models, generates `alt` and `aria-label` fixes, traces every run in **Langfuse**, and installs from npm as [`bariweb-widget`](https://www.npmjs.com/package/bariweb-widget).

**My part:** backend and AI agent, the embeddable widget SDK, and DevOps (GitLab → GitHub migration and Vercel CI/CD).<br>
`FastAPI` `LLM agents` `RAG` `Milvus` `RAGFlow` `Playwright` `PostgreSQL` `Lit` `Vercel`<br>
[**Live**](https://bariweb.vercel.app) · [**Code**](https://github.com/Akanov-Kanta/bariweb) · [**npm**](https://www.npmjs.com/package/bariweb-widget)

<table>
<tr>
<td width="50%" valign="top">

<a href="https://github.com/Akanov-Kanta/Bailanysta"><img src="assets/bailanysta.png" alt="Bailanysta profile page with a post composer and an AI idea button" width="100%" /></a>

### [Bailanysta](https://github.com/Akanov-Kanta/Bailanysta)

A full-stack social network with a **GPT-4 writing assistant** built in. Users post, like and comment, and when they're stuck, one click drafts a post for them.

`Next.js 15` `React 19` `Supabase` `OpenAI` `Framer Motion`

</td>
<td width="50%" valign="top">

<p align="center"><a href="https://github.com/Akanov-Kanta/Courses"><img src="assets/courses.png" alt="NIScourses student schedule screen on a phone" height="300" /></a></p>

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
