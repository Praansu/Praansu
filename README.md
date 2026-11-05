<img src="https://raw.githubusercontent.com/Praansu/Praansu/main/assets/banner.png" alt="praansu karmacharya" width="100%"/>

<div style="max-width: 720px; margin: 0 auto;">

## about me

i'm praansu. cs student at islington college, kathmandu (class of 2028) and junior ai developer intern at aviayaan tech.

i build ml models and the products around them — pytorch, rag pipelines, agent tool-calling, fastapi, next.js. things break, i fix them, i ship what works.

interning at aviayaan tech on ensemble methods for traffic-count estimation and road-damage segmentation. before that i taught myself deep learning from scratch and kept building until something worked.

<hr style="border: none; border-top: 1px solid #e2e4e7; margin: 24px 0;"/>

## now

currently building ensemble methods for traffic-count estimation at aviayaan tech. open to freelance rag + agent work.

<hr style="border: none; border-top: 1px solid #e2e4e7; margin: 24px 0;"/>

## contact

<div style="display: flex; gap: 10px; align-items: center; flex-wrap: wrap; margin-bottom: 24px;">
  <a href="mailto:Praansu12@gmail.com"><img src="https://img.shields.io/badge/contact-email-d14836?style=for-the-badge&logo=gmail&logoColor=white" alt="email" height="28"/></a>
  <a href="https://np.linkedin.com/in/praansu-karmacharya-694944368/"><img src="https://img.shields.io/badge/linkedin-connect-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white" alt="linkedin" height="28"/></a>
  <a href="https://praansu.github.io"><img src="https://img.shields.io/badge/portfolio-visit-ff7139?style=for-the-badge&logo=googlechrome&logoColor=white" alt="portfolio" height="28"/></a>
</div>

## experience

<table style="width: 100%; border-collapse: separate; border-spacing: 0 12px;">
  <tr style="vertical-align: top;">
    <td style="width: 200px; font-weight: 600; color: #1a1a2e;">junior ai developer (intern)</td>
    <td>aviayaan tech · mar 2026 — present · ensemble methods for traffic-count estimation, road-damage segmentation and classification.</td>
  </tr>
  <tr style="vertical-align: top;">
    <td style="width: 200px; font-weight: 600; color: #1a1a2e;">independent builder</td>
    <td>personal projects · 2024 — present · rag loops, agent harnesses, vision models, full-stack demo storefront. available for freelance rag + agent work.</td>
  </tr>
  <tr style="vertical-align: top;">
    <td style="width: 200px; font-weight: 600; color: #1a1a2e;">bsc (hons) computing with ai</td>
    <td>islington college, kathmandu · 2025 — 2028 · coursework and self-directed builds in pytorch, rag pipelines, agent tool-calling, full-stack deployment.</td>
  </tr>
</table>

<hr style="border: none; border-top: 1px solid #e2e4e7; margin: 24px 0;"/>

## selected work

<table style="width: 100%; border-collapse: separate; border-spacing: 0 16px;">
  <tr>
    <th style="text-align: left; font-weight: 600; color: #1a1a2e; padding-bottom: 8px; border-bottom: 1px solid #e2e4e7;">project</th>
    <th style="text-align: left; font-weight: 600; color: #1a1a2e; padding-bottom: 8px; border-bottom: 1px solid #e2e4e7;">what it does</th>
    <th style="text-align: left; font-weight: 600; color: #1a1a2e; padding-bottom: 8px; border-bottom: 1px solid #e2e4e7;">stack</th>
  </tr>
  <tr style="vertical-align: top;">
    <td style="width: 150px;"><strong>[ai-research-agent](https://github.com/Praansu/ai-research-agent)</strong></td>
    <td>custom agent loop, no langchain. routes between local docs (chromadb) and web search, streams every tool call live. fixed a two-day bug where it kept calling the wrong tool — system prompt was too vague.</td>
    <td>python · fastapi · chromadb · sse</td>
  </tr>
  <tr style="vertical-align: top;">
    <td style="width: 150px;"><strong>[pdf-chat-rag](https://github.com/Praansu/pdf-chat-rag)</strong></td>
    <td>upload a pdf, ask questions. added delete-docs and streaming after re-uploading the same file ten times. answers stream token by token.</td>
    <td>python · fastapi · chromadb · pymupdf</td>
  </tr>
  <tr style="vertical-align: top;">
    <td style="width: 150px;"><strong>[vehicle-image-classifier](https://github.com/Praansu/vehicle-image-classifier)</strong></td>
    <td>pytorch resnet-18, sorts bus/car/bike/truck. 90% on my own 400-image set — labelled every image myself with a pyqt tool i made. served behind fastapi, containerised.</td>
    <td>pytorch · resnet-18 · fastapi · docker</td>
  </tr>
  <tr style="vertical-align: top;">
    <td style="width: 150px;"><strong>[eco-verda](https://github.com/Praansu/eco-verda)</strong></td>
    <td>eco products store to learn next.js properly. blur-up images, debounced search that syncs to the url. broke checkout twice before webhooks finally worked. stripe not wired yet — known issue.</td>
    <td>next.js · typescript · prisma · stripe</td>
  </tr>
  <tr style="vertical-align: top;">
    <td style="width: 150px;"><strong>[parkx](https://github.com/Praansu/ParkX)</strong></td>
    <td>smart parking across esp32 + fastapi + dashboard. local ollama chatbot with groq fallback, guardrailed to parking questions only.</td>
    <td>esp32 · fastapi · ollama</td>
  </tr>
  <tr style="vertical-align: top;">
    <td style="width: 150px;"><strong>[health-guard-ml](https://github.com/Praansu/health-guard-ml)</strong></td>
    <td>heart disease prediction, xgboost + shap so it explains itself. still a stub with honest todos.</td>
    <td>xgboost · shap</td>
  </tr>
</table>

<hr style="border: none; border-top: 1px solid #e2e4e7; margin: 24px 0;"/>

## smaller stuff

<ul style="list-style: none; padding: 0;">
  <li style="margin-bottom: 8px;">nnunet-road-cracks — crack-segmentation packaging over nnunet.</li>
  <li style="margin-bottom: 8px;">demand-predictor-ml — parking demand forecasting with xgboost and scikit-learn.</li>
  <li style="margin-bottom: 8px;">small-agent-reliability — testing if 3b-9b models can work as agents. 14 tasks. they kept breaking in weird ways.</li>
  <li style="margin-bottom: 8px;">vehicle-labeling-tool — tiny pyqt app i made to label training data faster. (archived)</li>
</ul>

<hr style="border: none; border-top: 1px solid #e2e4e7; margin: 24px 0;"/>

## stack

<div style="display: flex; flex-wrap: wrap; gap: 8px; margin-bottom: 12px;">
  <span style="background: #eef1f5; color: #1a1a2e; padding: 5px 10px; border-radius: 6px; font-size: 0.85em; border: 1px solid #cbd5e0;">python</span>
  <span style="background: #eef1f5; color: #1a1a2e; padding: 5px 10px; border-radius: 6px; font-size: 0.85em; border: 1px solid #cbd5e0;">typescript</span>
  <span style="background: #eef1f5; color: #1a1a2e; padding: 5px 10px; border-radius: 6px; font-size: 0.85em; border: 1px solid #cbd5e0;">pytorch</span>
  <span style="background: #eef1f5; color: #1a1a2e; padding: 5px 10px; border-radius: 6px; font-size: 0.85em; border: 1px solid #cbd5e0;">fastapi</span>
  <span style="background: #eef1f5; color: #1a1a2e; padding: 5px 10px; border-radius: 6px; font-size: 0.85em; border: 1px solid #cbd5e0;">next.js</span>
  <span style="background: #eef1f5; color: #1a1a2e; padding: 5px 10px; border-radius: 6px; font-size: 0.85em; border: 1px solid #cbd5e0;">chromadb</span>
  <span style="background: #eef1f5; color: #1a1a2e; padding: 5px 10px; border-radius: 6px; font-size: 0.85em; border: 1px solid #cbd5e0;">docker</span>
</div>

have used: scikit-learn, xgboost, opencv, prisma, streamlit, flask, sqlite, esp32, java, c++

if it's listed, i've shipped something with it.

</div>

---

<div style="max-width: 720px; margin: 0 auto; text-align: center;">
  <a href="mailto:Praansu12@gmail.com">email</a> ·
  <a href="https://praansu.github.io">portfolio</a> ·
  <a href="https://np.linkedin.com/in/praansu-karmacharya-694944368">linkedin</a>
</div>
