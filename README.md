<!-- header: no SVG typing, no animation, just text -->
<img width="12" src="https://github.com/Praansu/Praansu/blob/main/assets/banner.png?raw=true" alt="banner" />

## about me

i'm praansu. cs student at islington college, kathmandu. class of 2028.

started with python because my friend showed me how to automate a boring spreadsheet. then i got into pytorch, trained some terrible models, got curious about llms, built a rag system that kept hallucinating, and now i'm here trying to make things that actually work.

i build ml models and the products around them. mostly side projects, some break, some work. this profile is the ones i haven't deleted yet.

**intern** — junior ai developer @ aviayaan tech (mar 2026 — present)
ensemble methods for traffic-count estimation, road-damage segmentation and classification

**student** — bsc (hons) computing with ai @ islington college (2025 — 2028)
self-directed builds in pytorch, rag pipelines, agent tool-calling, full-stack deployment

contact: praansu12@gmail.com

---

## selected work

| project | what it does | stack |
|---|---|---|
| **[ai-research-agent](https://github.com/Praansu/ai-research-agent)** | custom agent loop, no langchain. routes between local docs (chromadb) and web search. streams every tool call live. spent two days debugging why it kept calling the wrong tool — turns out the system prompt was too vague. | python · fastapi · chromadb · sse |
| **[pdf-chat-rag](https://github.com/Praansu/pdf-chat-rag)** | upload a pdf, ask questions. added delete-docs and streaming after i got annoyed re-uploading the same file ten times. answers stream token by token. | python · fastapi · chromadb · pymupdf |
| **[vehicle-image-classifier](https://github.com/Praansu/vehicle-image-classifier)** | pytorch resnet-18, sorts bus/car/bike/truck. 90% on my own 400-image set — labelled all 100-per-class myself with a pyqt tool i made because i was too impatient to do it by hand. served behind fastapi, containerised. | pytorch · resnet-18 · fastapi · docker |
| **[eco-verda](https://github.com/Praansu/eco-verda)** | eco products store to learn next.js properly. blur-up images, debounced search that syncs to the url. broke checkout twice before webhooks finally worked. stripe client exists but isn't wired yet — known issue. | next.js · typescript · prisma · stripe |
| **[parkx](https://github.com/Praansu/ParkX)** | smart parking across esp32 + fastapi + dashboard. my iot rabbit hole. local ollama chatbot with groq fallback. | esp32 · fastapi · ollama |
| **[health-guard-ml](https://github.com/Praansu/health-guard-ml)** | heart disease prediction, xgboost + shap so it explains itself. still a stub with honest todos. | xgboost · shap |

---

## smaller stuff

- **[nnunet-road-cracks](https://github.com/Praansu/nnunet-road-cracks)** — crack-segmentation packaging over nnunet.
- **[demand-predictor-ml](https://github.com/Praansu/demand-predictor-ml)** — parking demand forecasting with xgboost and scikit-learn.
- **[small-agent-reliability](https://github.com/Praansu/small-agent-reliability)** — testing if 3b-9b models can work as agents. 14 tasks. they kept breaking in weird ways.
- **[vehicle-labeling-tool](https://github.com/Praansu/vehicle-labeling-tool)** — tiny pyqt app i made to label training data faster. (archived)

---

## stack

comfortable: python, typescript, pytorch, fastapi, next.js, chromadb, docker
have used: scikit-learn, xgboost, opencv, prisma, streamlit, flask, sqlite, esp32, java, c++

if it's listed, i've shipped something with it. no progress bars.

---

<div align="center">
  <a href="mailto:Praansu12@gmail.com">email</a> ·
  <a href="https://praansu.github.io">portfolio</a> ·
  <a href="https://np.linkedin.com/in/praansu-karmacharya-694944368">linkedin</a>
</div>
