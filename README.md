<picture>
  <source media="(prefers-color-scheme: dark)" srcset="header-dark.svg">
  <img src="header-light.svg" alt="Praansu Karmacharya, ML/AI engineering, Kathmandu">
</picture>

<div align="center">

# Praansu Karmacharya

**Junior AI Developer · CS undergrad · Kathmandu, Nepal**

![Open to work](https://img.shields.io/badge/OPEN_TO_WORK-yes-FF4D00?style=for-the-badge)
![Aviyaan Tech](https://img.shields.io/badge/AVIYAAN_TECH-6_MONTHS_EXP-1E40AF?style=for-the-badge)
![Freelance](https://img.shields.io/badge/FREELANCE-available-24292f?style=for-the-badge)

</div>

ML/AI engineer in Kathmandu. I build retrieval systems, agent loops and vision models, then write down what broke and why.

Currently finishing a BSc in Computer Science at Islington College, freelancing on retrieval pipelines and model deployment, and running a reliability study on small open-weight models used as tool-calling agents. Previously a Junior AI Developer at Aviyaan Tech — six months of production AI work. I like work I can point at and say: that runs because of me.

---

## Experience

**Junior AI Developer** — Aviyaan Tech · *6 months experience*
Built and tested AI features for production web projects, working with Python ML tooling and LLM APIs alongside senior developers. First time seeing how AI code survives contact with real clients.

**Freelance AI/ML Engineer** — Self-employed · *2024 — present*
RAG pipelines, custom agent loops, ML model deployment, and full-stack AI products for clients. The work on this page mostly comes from here.

**BSc Computing student** — Islington College, Kathmandu · *2023 — present*
Bachelor of Computer Science. Focus on ML, AI, and full-stack development.

---

## Selected work

**[ai-research-agent](https://github.com/Praansu/ai-research-agent)**
Upload a PDF, Markdown or text file and ask questions about it. The agent picks whether to search your documents, search the web, or both, and streams every tool call to the browser as it happens instead of hiding the loop behind a framework. The whole loop is about 120 lines of plain Python.
`Python` `FastAPI` `ChromaDB` `SSE`

**[small-agent-reliability](https://github.com/Praansu/small-agent-reliability)**
Nine open-weight models between 1B and 9B, scored as tool-using agents across 31 capability tasks and 14 reliability tasks. Accuracy, consistency, robustness, failure recovery and refusal behaviour are scored separately rather than collapsed into one leaderboard. Runs locally on quantized weights through Ollama, so the study reproduces on a laptop.
`Python` `Ollama` `pandas` `LaTeX`

**[pdf-chat-rag](https://github.com/Praansu/pdf-chat-rag)**
Document Q&A with real CRUD. Deleting a document removes its vectors, its file and its database row in one operation, which is the part most demos skip. Answers stream token by token over SSE.
`Python` `FastAPI` `ChromaDB` `PyMuPDF` `sentence-transformers`

**[vehicle-image-classifier](https://github.com/Praansu/vehicle-image-classifier)**
ResNet-18 transfer learning on 400 images across four classes. Evaluation reports a confusion matrix and per-class accuracy next to the headline number, because a single aggregate hides a model that is good at one class and guessing at another. Served behind FastAPI and containerised.
`PyTorch` `ResNet-18` `FastAPI` `Docker`

**[nnunet-road-cracks](https://github.com/Praansu/nnunet-road-cracks)**
nnU-Net pipeline for road crack and pavement distress segmentation, packaged so a survey engineer can run it without a Python environment or a command line.
`nnU-Net` `PyTorch` `Python packaging`

**[EcoVerda](https://github.com/Praansu/eco-verda)**
Full-stack storefront for sustainable products: cart persistence, credentials auth, orders and reviews on Next.js 16 + Prisma/SQLite. The Stripe client exists but isn't wired into checkout yet — tracked as a known issue in the repo. [Live](https://praansu.github.io/eco-verda/)
`Next.js` `TypeScript` `Prisma` `Stripe`

**[ParkX](https://github.com/Praansu/ParkX)**
Smart parking across three layers: ESP32 sensor firmware, a FastAPI backend, and a dashboard that polls bay state every 2 seconds. Includes bookings, anomaly alerts, and a chatbot with local-Ollama-first, Groq-fallback answering.
`ESP32` `FastAPI` `Ollama`

<details>
<summary><b>More repos — experiments, coursework, and old tools (9)</b></summary>
<br>

- **[demand-predictor-ml](https://github.com/Praansu/demand-predictor-ml)** — parking demand forecasting experiments with XGBoost and scikit-learn.
- **[health-guard-ml](https://github.com/Praansu/health-guard-ml)** — early-stage health-risk classifier; still a stub with honest TODOs in the README.
- **[career-stability](https://github.com/Praansu/career-stability)** — data exploration on job-stability survey data.
- **[ai-doc-summarizer](https://github.com/Praansu/ai-doc-summarizer)** — abstractive summarization API experiment *(archived)*.
- **[qgis-batch-extraction](https://github.com/Praansu/qgis-batch-extraction)** — QGIS batch-processing scripts for geospatial layers *(archived)*.
- **[vehicle-labeling-tool](https://github.com/Praansu/vehicle-labeling-tool)** — tiny Tkinter app built to label the vehicle classifier's training set *(archived)*.
- **[todo-list-cli](https://github.com/Praansu/todo-list-cli)** — my first Python CLI project *(archived)*.
- **[js-calculator](https://github.com/Praansu/js-calculator)** — weekend JavaScript calculator.
- **[MyProjects](https://github.com/Praansu/MyProjects)** — old scratch repo of first experiments *(archived)*.

</details>

---

## What I work with

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=py,pytorch,fastapi,ts,nextjs,react,tailwind,postgres,prisma,docker,linux,git&theme=dark">
  <img src="https://skillicons.dev/icons?i=py,pytorch,fastapi,ts,nextjs,react,tailwind,postgres,prisma,docker,linux,git&theme=light" alt="Languages and tools I use">
</picture>

**Comfortable**
Python, FastAPI, RAG pipelines, ChromaDB, prompt and tool design, PyTorch, scikit-learn, pandas, Docker, Git and GitHub Actions, SQLite, REST APIs

**Used on real projects**
Next.js, TypeScript, React, Tailwind, PostgreSQL, Prisma, Stripe, XGBoost, OpenCV, ESP32, REST polling, Linux and shell

**Studying now**
CUDA and GPU profiling, GGUF quantisation, MLOps and experiment tracking, distributed training

---

## Stats

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=Praansu&show_icons=true&theme=github_dark&hide_border=true&bg_color=00000000">
  <img src="https://github-readme-stats.vercel.app/api?username=Praansu&show_icons=true&theme=default&hide_border=true" alt="Praansu's GitHub stats">
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=Praansu&layout=compact&theme=github_dark&hide_border=true&bg_color=00000000">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Praansu&layout=compact&theme=default&hide_border=true" alt="Praansu's most used languages">
</picture>

---

[Portfolio](https://praansu.github.io) | [LinkedIn](https://www.linkedin.com/in/praansu-karmacharya-694944368/) | Praansu12@gmail.com

Open to ML/AI engineering roles, remote or in Kathmandu.

![Profile views](https://komarev.com/ghpvc/?username=Praansu&color=FF4D00&style=flat-square&label=views)
