<p align="center">
  <img src="https://raw.githubusercontent.com/Praansu/Praansu/main/assets/banner.svg" alt="Praansu Karmacharya" width="100%"/>
</p>

> I build ML models and the products around them. Things break, I fix them, I ship what works.

## 01 · about me

I'm Praansu. CS student at Islington College, Kathmandu, class of 2028, and a junior AI developer intern at Aviyaan Tech. I work across the whole stack: PyTorch training loops, RAG pipelines, agent tool-calling, and the FastAPI and Next.js layers that ship them.

At Aviyaan Tech I work on ensemble methods for traffic-count estimation and road-damage segmentation. Before that, I taught myself deep learning from scratch and kept building until something worked.

## 02 · featured work

<table border="0" cellpadding="12" cellspacing="0">
  <tr>
    <td valign="top">
      <a href="https://github.com/Praansu/ai-research-agent"><strong>AI Research Agent</strong></a><br/>
      <sub>A custom agent loop, no LangChain. It routes between local docs (ChromaDB) and web search by itself, and streams every tool call live. I once spent two days on a bug where it kept calling the wrong tool; the system prompt was too vague.</sub><br/>
      <sub>Python · FastAPI · ChromaDB · SSE</sub>
    </td>
    <td width="40"></td>
    <td valign="top">
      <a href="https://github.com/Praansu/pdf-chat-rag"><strong>PDF Chat RAG</strong></a><br/>
      <sub>Upload a PDF and ask it questions, with answers that stream token by token. Added document management and delete-docs after re-uploading the same file ten times.</sub><br/>
      <sub>Python · FastAPI · PyMuPDF · ChromaDB</sub>
    </td>
  </tr>
  <tr>
    <td valign="top">
      <a href="https://github.com/Praansu/vehicle-image-classifier"><strong>Vehicle Image Classifier</strong></a><br/>
      <sub>PyTorch ResNet-18 that sorts bus, car, bike and truck at 90% on a 400-image set I labelled myself with a small PyQt tool. Served behind FastAPI, containerized.</sub><br/>
      <sub>PyTorch · ResNet-18 · FastAPI · Docker</sub>
    </td>
    <td width="40"></td>
    <td valign="top">
      <a href="https://github.com/Praansu/eco-verda"><strong>Eco-Verda</strong></a><br/>
      <sub>An eco-products store built to learn Next.js properly: debounced search synced to the URL, blur-up images. I broke checkout twice before the Stripe webhooks finally worked. Payments are not wired yet, that's the known issue.</sub><br/>
      <sub>Next.js · TypeScript · Prisma · Stripe</sub>
    </td>
  </tr>
  <tr>
    <td valign="top">
      <a href="https://github.com/Praansu/ParkX"><strong>ParkX</strong></a><br/>
      <sub>Smart parking across ESP32, FastAPI and a dashboard. A local Ollama chatbot with a Groq fallback, now guardrailed so it only answers parking questions.</sub><br/>
      <sub>ESP32 · FastAPI · Ollama · Groq</sub>
    </td>
    <td width="40"></td>
    <td valign="top">
      <a href="https://github.com/Praansu/health-guard-ml"><strong>Health Guard ML</strong></a><br/>
      <sub>Heart-disease prediction with XGBoost + SHAP so the model explains itself. Still an honest work in progress.</sub><br/>
      <sub>XGBoost · SHAP</sub>
    </td>
  </tr>
</table>

<img src="https://raw.githubusercontent.com/Praansu/Praansu/main/assets/divider.svg" width="100%"/>

## 03 · tech stack

<table border="0" cellpadding="12" cellspacing="0">
  <tr>
    <td valign="top">
      <strong>Languages</strong><br/>
      <img src="https://img.shields.io/badge/Python-1F2328?style=flat-square&logo=python&logoColor=white" alt="Python"/>&nbsp;
      <img src="https://img.shields.io/badge/TypeScript-1F2328?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"/>&nbsp;
      <img src="https://img.shields.io/badge/HTML-1F2328?style=flat-square&logo=html5&logoColor=white" alt="HTML"/>
    </td>
  </tr>
  <tr>
    <td valign="top">
      <strong>AI / ML</strong><br/>
      <img src="https://img.shields.io/badge/PyTorch-1F2328?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch"/>&nbsp;
      <img src="https://img.shields.io/badge/XGBoost-1F2328?style=flat-square" alt="XGBoost"/>&nbsp;
      <img src="https://img.shields.io/badge/SHAP-1F2328?style=flat-square" alt="SHAP"/>&nbsp;
      <img src="https://img.shields.io/badge/ChromaDB-1F2328?style=flat-square" alt="ChromaDB"/>
    </td>
  </tr>
  <tr>
    <td valign="top">
      <strong>Backend &amp; Tools</strong><br/>
      <img src="https://img.shields.io/badge/FastAPI-1F2328?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI"/>&nbsp;
      <img src="https://img.shields.io/badge/Next.js-1F2328?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js"/>&nbsp;
      <img src="https://img.shields.io/badge/Docker-1F2328?style=flat-square&logo=docker&logoColor=white" alt="Docker"/>&nbsp;
      <img src="https://img.shields.io/badge/ESP32-1F2328?style=flat-square" alt="ESP32"/>
    </td>
  </tr>
</table>

<sub>Also used: scikit-learn, OpenCV, Prisma, Streamlit, Flask, SQLite, Ollama, Groq, Java, C++</sub>

<img src="https://raw.githubusercontent.com/Praansu/Praansu/main/assets/divider.svg" width="100%"/>

## 04 · currently exploring

**[small-agent-reliability](https://github.com/Praansu/small-agent-reliability)** · Testing whether 3B-9B open-source models can actually work as agents. 14 tasks; they kept breaking in weird ways.<br/>
**[demand-predictor-ml](https://github.com/Praansu/demand-predictor-ml)** · Time-series forecasting for parking occupancy: synthetic data, lag and rolling features, Linear vs Random Forest vs XGBoost.<br/>
**[nnunet-road-cracks](https://github.com/Praansu/nnunet-road-cracks)** · A one-click nnU-Net v2 package for road-crack segmentation, built so non-technical users can run it.

<img src="https://raw.githubusercontent.com/Praansu/Praansu/main/assets/divider.svg" width="100%"/>

## 05 · activity

15 public repositories · 1 star on ParkX · joined June 2025<br/>
Most recently pushed: small-agent-reliability · demand-predictor-ml · Praansu.github.io

<img src="https://raw.githubusercontent.com/Praansu/Praansu/main/assets/divider.svg" width="100%"/>

## 06 · connect

<a href="mailto:Praansu12@gmail.com"><img src="https://img.shields.io/badge/Gmail-1F2328?style=flat-square&logo=gmail&logoColor=white" alt="Email" height="28"/></a>&nbsp;
<a href="https://np.linkedin.com/in/praansu-karmacharya-694944368/"><img src="https://img.shields.io/badge/LinkedIn-1F2328?style=flat-square" alt="LinkedIn" height="28"/></a>&nbsp;
<a href="https://praansu.github.io"><img src="https://img.shields.io/badge/Portfolio-1F2328?style=flat-square&logo=googlechrome&logoColor=white" alt="Portfolio" height="28"/></a>

<p align="center"><sub>Kathmandu, Nepal · updated November 2026</sub></p>
