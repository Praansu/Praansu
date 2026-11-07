<p align="center">
  <img src="https://raw.githubusercontent.com/Praansu/Praansu/main/assets/banner.svg" alt="Praansu Karmacharya" width="100%"/>
</p>

> I build ML models and the products around them.<br/>
> Things break. I fix them. I ship what works.

## 01 · about me

I'm Praansu. CS student at Islington College, Kathmandu, class of 2028, and a junior AI developer intern at Aviyaan Tech. I work across the whole stack — PyTorch training loops, RAG pipelines, agent tool-calling, and the FastAPI and Next.js layers that ship them.

At Aviyaan Tech I work on ensemble methods for traffic-count estimation and road-damage segmentation. Before that, I taught myself deep learning from scratch and kept building until something worked.

## 02 · featured work

<table border="0" cellpadding="0" cellspacing="0" width="100%">
  <tr>
    <td valign="top" width="16%">
      <img src="https://raw.githubusercontent.com/Praansu/Praansu/main/assets/project-01.svg" width="52" height="52"/>
    </td>
    <td valign="top" width="66%">
      <a href="https://github.com/Praansu/ai-research-agent"><strong>AI Research Agent</strong></a><br/>
      <sub>A custom agent loop, no LangChain. Routes between local docs (ChromaDB) and web search by itself, streaming every tool call live. Spent two days on a bug where it kept calling the wrong tool — the system prompt was too vague.</sub><br/>
      <sub>Python · FastAPI · ChromaDB · SSE</sub>
    </td>
    <td valign="top" width="18%">
      <sub><a href="https://img.shields.io/badge/ML%2FAgent-1F2328?style=flat-square" alt="ML Agent"><img src="https://img.shields.io/badge/ML/Agent-1F2328?style=flat-square" alt="ML Agent"/></a></sub>
    </td>
  </tr>
  <tr height="16"><td></td></tr>
  <tr>
    <td valign="top" width="16%">
      <img src="https://raw.githubusercontent.com/Praansu/Praansu/main/assets/project-02.svg" width="52" height="52"/>
    </td>
    <td valign="top" width="66%">
      <a href="https://github.com/Praansu/pdf-chat-rag"><strong>PDF Chat RAG</strong></a><br/>
      <sub>Upload a PDF and ask it questions, answers stream token by token. Added document management and delete-docs after re-uploading the same file ten times.</sub><br/>
      <sub>Python · FastAPI · PyMuPDF · ChromaDB</sub>
    </td>
    <td valign="top" width="18%">
      <sub><img src="https://img.shields.io/badge/RAG%2FNLP-1F2328?style=flat-square" alt="RAG NLP"/></sub>
    </td>
  </tr>
  <tr height="16"><td></td></tr>
  <tr>
    <td valign="top" width="16%">
      <img src="https://raw.githubusercontent.com/Praansu/Praansu/main/assets/project-03.svg" width="52" height="52"/>
    </td>
    <td valign="top" width="66%">
      <a href="https://github.com/Praansu/vehicle-image-classifier"><strong>Vehicle Image Classifier</strong></a><br/>
      <sub>PyTorch ResNet-18 sorting bus, car, bike and truck at 90% on a 400-image set I labelled myself with a PyQt tool. Served behind FastAPI, containerized.</sub><br/>
      <sub>PyTorch · ResNet-18 · FastAPI · Docker</sub>
    </td>
    <td valign="top" width="18%">
      <sub><img src="https://img.shields.io/badge/CV%2FPyTorch-1F2328?style=flat-square" alt="CV PyTorch"/></sub>
    </td>
  </tr>
</table>

<table border="0" cellpadding="0" cellspacing="0" width="100%">
  <tr>
    <td valign="top" width="16%">
      <img src="https://raw.githubusercontent.com/Praansu/Praansu/main/assets/project-04.svg" width="52" height="52"/>
    </td>
    <td valign="top" width="66%">
      <a href="https://github.com/Praansu/ParkX"><strong>ParkX</strong></a><br/>
      <sub>Smart parking across ESP32, FastAPI and a dashboard. Local Ollama chatbot with Groq fallback, guardrailed to parking questions only.</sub><br/>
      <sub>ESP32 · FastAPI · Ollama · Groq</sub>
    </td>
    <td valign="top" width="18%">
      <sub><img src="https://img.shields.io/badge/IoT%2FEdge-1F2328?style=flat-square" alt="IoT Edge"/></sub>
    </td>
  </tr>
  <tr height="16"><td></td></tr>
  <tr>
    <td valign="top" width="16%">
      <img src="https://raw.githubusercontent.com/Praansu/Praansu/main/assets/project-05.svg" width="52" height="52"/>
    </td>
    <td valign="top" width="66%">
      <a href="https://github.com/Praansu/eco-verda"><strong>Eco-Verda</strong></a><br/>
      <sub>Eco-products store built to learn Next.js properly: debounced search synced to the URL, blur-up images. Broke checkout twice before Stripe webhooks finally worked.</sub><br/>
      <sub>Next.js · TypeScript · Prisma · Stripe</sub>
    </td>
    <td valign="top" width="18%">
      <sub><img src="https://img.shields.io/badge/Full-stack-1F2328?style=flat-square" alt="Full-stack"/></sub>
    </td>
  </tr>
  <tr height="16"><td></td></tr>
  <tr>
    <td valign="top" width="16%">
      <img src="https://raw.githubusercontent.com/Praansu/Praansu/main/assets/project-06.svg" width="52" height="52"/>
    </td>
    <td valign="top" width="66%">
      <a href="https://github.com/Praansu/health-guard-ml"><strong>Health Guard ML</strong></a><br/>
      <sub>Heart-disease prediction with XGBoost + SHAP so the model explains itself. Still an honest work in progress.</sub><br/>
      <sub>XGBoost · SHAP</sub>
    </td>
    <td valign="top" width="18%">
      <sub><img src="https://img.shields.io/badge/Health%2FML-1F2328?style=flat-square" alt="Health ML"/></sub>
    </td>
  </tr>
</table>

<img src="https://raw.githubusercontent.com/Praansu/Praansu/main/assets/divider.svg" width="100%"/>

## 03 · research & experiments

<table border="0" cellpadding="14" cellspacing="0" width="100%">
  <tr>
    <td valign="top" width="33%">
      <strong style="letter-spacing:0.04em;">small-agent-reliability</strong><br/>
      <sub>Testing whether 3B-9B open-source models can actually work as agents. 14 tasks; they kept breaking in weird ways.</sub><br/>
      <sub>Python · agent tool-calling</sub>
    </td>
    <td valign="top" width="33%">
      <strong style="letter-spacing:0.04em;">demand-predictor-ml</strong><br/>
      <sub>Time-series forecasting for parking occupancy: synthetic data, lag and rolling features, Linear vs Random Forest vs XGBoost.</sub><br/>
      <sub>Python · XGBoost · scikit-learn</sub>
    </td>
    <td valign="top" width="33%">
      <strong style="letter-spacing:0.04em;">nnunet-road-cracks</strong><br/>
      <sub>One-click nnU-Net v2 package for road crack and pavement distress segmentation, built so non-technical users can run it.</sub><br/>
      <sub>Python · nnU-Net · OpenCV</sub>
    </td>
  </tr>
</table>

<sub>I enjoy investigating technical problems, not just building CRUD applications.</sub>

<img src="https://raw.githubusercontent.com/Praansu/Praansu/main/assets/divider.svg" width="100%"/>

## 04 · tech stack

<table border="0" cellpadding="12" cellspacing="0" width="100%">
  <tr>
    <td valign="top" width="25%">
      <strong style="font-size:0.88em; letter-spacing:0.05em;">Languages</strong><br/>
      <img src="https://img.shields.io/badge/Python-1F2328?style=flat-square&logo=python&logoColor=white" alt="Python"/>&nbsp;
      <img src="https://img.shields.io/badge/TypeScript-1F2328?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"/>&nbsp;
      <img src="https://img.shields.io/badge/HTML-1F2328?style=flat-square&logo=html5&logoColor=white" alt="HTML"/>
    </td>
    <td valign="top" width="25%">
      <strong style="font-size:0.88em; letter-spacing:0.05em;">AI / Machine Learning</strong><br/>
      <img src="https://img.shields.io/badge/PyTorch-1F2328?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch"/>&nbsp;
      <img src="https://img.shields.io/badge/XGBoost-1F2328?style=flat-square" alt="XGBoost"/>&nbsp;
      <img src="https://img.shields.io/badge/SHAP-1F2328?style=flat-square" alt="SHAP"/>&nbsp;
      <img src="https://img.shields.io/badge/ChromaDB-1F2328?style=flat-square" alt="ChromaDB"/>
    </td>
    <td valign="top" width="25%">
      <strong style="font-size:0.88em; letter-spacing:0.05em;">Backend &amp; Frameworks</strong><br/>
      <img src="https://img.shields.io/badge/FastAPI-1F2328?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI"/>&nbsp;
      <img src="https://img.shields.io/badge/Next.js-1F2328?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js"/>&nbsp;
      <img src="https://img.shields.io/badge/Docker-1F2328?style=flat-square&logo=docker&logoColor=white" alt="Docker"/>
    </td>
    <td valign="top" width="25%">
      <strong style="font-size:0.88em; letter-spacing:0.05em;">Infrastructure &amp; Tools</strong><br/>
      <img src="https://img.shields.io/badge/ESP32-1F2328?style=flat-square" alt="ESP32"/>&nbsp;
      <img src="https://img.shields.io/badge/Prisma-1F2328?style=flat-square" alt="Prisma"/>&nbsp;
      <img src="https://img.shields.io/badge/SQLite-1F2328?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite"/>&nbsp;
      <img src="https://img.shields.io/badge/Ollama-1F2328?style=flat-square" alt="Ollama"/>
    </td>
  </tr>
</table>

<sub>Also used: scikit-learn, OpenCV, Streamlit, Flask, Java, C++, Groq</sub>

<img src="https://raw.githubusercontent.com/Praansu/Praansu/main/assets/divider.svg" width="100%"/>

## 05 · github activity

15 public repositories · 1 star on ParkX · joined June 2025<br/>
Most recently pushed: small-agent-reliability · demand-predictor-ml · Praansu.github.io

<img src="https://raw.githubusercontent.com/Praansu/Praansu/main/assets/divider.svg" width="100%"/>

## 06 · connect

<a href="mailto:Praansu12@gmail.com"><img src="https://img.shields.io/badge/Gmail-1F2328?style=flat-square&logo=gmail&logoColor=white" alt="Email" height="28"/></a>&nbsp;
<a href="https://np.linkedin.com/in/praansu-karmacharya-694944368/"><img src="https://img.shields.io/badge/LinkedIn-1F2328?style=flat-square" alt="LinkedIn" height="28"/></a>&nbsp;
<a href="https://praansu.github.io"><img src="https://img.shields.io/badge/Portfolio-1F2328?style=flat-square&logo=googlechrome&logoColor=white" alt="Portfolio" height="28"/></a>

<p align="center"><sub>Kathmandu, Nepal · updated November 2026</sub></p>
