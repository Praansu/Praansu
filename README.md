# Praansu Karmacharya

ML/AI engineer in Kathmandu. I build retrieval systems, agent loops and vision models, then write down what broke and why.

Currently finishing a BSc in Computer Science at Islington College, freelancing on retrieval pipelines and model deployment, and running a reliability study on small open-weight models used as tool-calling agents.

## Selected work

**[ai-research-agent](https://github.com/Praansu/ai-research-agent)** - Upload a PDF, Markdown or text file and ask questions about it. The agent picks whether to search your documents, search the web, or both, and streams every tool call to the browser as it happens instead of hiding the loop behind a framework. The whole loop is about 120 lines of plain Python.
`Python` `FastAPI` `ChromaDB` `SSE`

**[small-agent-reliability](https://github.com/Praansu/small-agent-reliability)** - Nine open-weight models between 1B and 9B, scored as tool-using agents across 31 capability tasks and 14 reliability tasks. Accuracy, consistency, robustness, failure recovery and refusal behaviour are scored separately rather than collapsed into one leaderboard. Runs locally on quantized weights through Ollama, so the study reproduces on a laptop.
`Python` `Ollama` `pandas` `LaTeX`

**[pdf-chat-rag](https://github.com/Praansu/pdf-chat-rag)** - Document Q&A with real CRUD. Deleting a document removes its vectors, its file and its database row in one operation, which is the part most demos skip. Answers stream token by token over SSE.
`Python` `FastAPI` `ChromaDB` `PyMuPDF` `sentence-transformers`

**[vehicle-image-classifier](https://github.com/Praansu/vehicle-image-classifier)** - ResNet-18 transfer learning on 400 images across four classes. Evaluation reports a confusion matrix and per-class accuracy next to the headline number, because a single aggregate hides a model that is good at one class and guessing at another. Served behind FastAPI and containerised.
`PyTorch` `ResNet-18` `FastAPI` `Docker`

**[nnunet-road-cracks](https://github.com/Praansu/nnunet-road-cracks)** - nnU-Net pipeline for road crack and pavement distress segmentation, packaged so a survey engineer can run it without a Python environment or a command line.
`nnU-Net` `PyTorch` `Python packaging`

**[EcoVerda](https://github.com/Praansu/eco-verda)** - Storefront for sustainable products with a live Stripe checkout. Static export, so nothing runs at request time that could have run at build time. [Live](https://praansu.github.io/eco-verda/)
`Next.js` `TypeScript` `Prisma` `Stripe`

**[ParkX](https://github.com/Praansu/ParkX)** - Smart parking across three layers: ESP32 sensor firmware, a FastAPI backend, and a dashboard that reflects bay state over WebSockets instead of polling.
`ESP32` `FastAPI` `WebSockets`

## What I work with

**Comfortable:** Python, FastAPI, RAG pipelines, ChromaDB, prompt and tool design, PyTorch, scikit-learn, pandas, Docker, Git and GitHub Actions, SQLite, REST APIs

**Used on real projects:** Next.js, TypeScript, React, Tailwind, PostgreSQL, Prisma, Stripe, XGBoost, OpenCV, ESP32, WebSockets, Linux and shell

**Studying now:** CUDA and GPU profiling, GGUF quantisation, MLOps and experiment tracking, distributed training

## Elsewhere

[Portfolio](https://praansu.github.io) | [LinkedIn](https://www.linkedin.com/in/praansu-karmacharya-694944368/) | praansu12@gmail.com

---

Open to ML/AI engineering roles, remote or in Kathmandu.
