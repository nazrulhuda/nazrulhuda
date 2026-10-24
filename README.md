<h1 align="center">Hi, I'm Nazrul Huda Shanto 👋</h1>

<p align="center">
  Software &amp; ML engineer · Researcher · MS in Computer Science, Oklahoma State University (2026)<br/>
  New York City
</p>

<p align="center">
  <a href="mailto:mshanto@okstate.edu"><img src="https://img.shields.io/badge/Email-mshanto%40okstate.edu-333333?style=flat-square" /></a>
  <a href="https://www.linkedin.com/in/mshanto/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white" /></a>
  <a href="https://scholar.google.com/citations?user=N9aZcZYAAAAJ&hl=en"><img src="https://img.shields.io/badge/Google_Scholar-4285F4?style=flat-square&logo=googlescholar&logoColor=white" /></a>
</p>

I build AI and cloud systems and then test carefully whether they actually work. I worked for a year as a software engineer, and I have more than four years of research experience: over two years as a Graduate Research Assistant at Oklahoma State University and over two years as an Undergraduate Research Assistant at BRAC University.


### ⭐ Featured work

- **LLM agent that runs zero-knowledge proof systems** · *Research, first author, with Dr. Paritosh Ramanan, under review at IEEE BigData 2026* · [Demo (1:55)](https://youtu.be/AQkmil7ZKEE) · [Paper](https://github.com/disys-lab/Skeptical-MCP-For-zkSNARKs/blob/main/manuscript/Natural-Language-ZK-Verification-via-Skeptical-MCP-Tools.pdf) · [Code & data](https://github.com/disys-lab/Skeptical-MCP-For-zkSNARKs)
  An LLM agent that lets people request, check, download, and verify zkSNARK proofs in plain language, using 8 custom MCP tools (LangGraph, FastMCP, Flask, Redis, PostgreSQL, Docker). My *skeptical tools* design, 20 server-side design decisions about what the model sends, raised task completion by about **23 points** on each of three open-weight model families (Qwen 3 32B: **70% → 93%**), across 6,000+ query runs. I also contributed new APIs and a verification bug fix that are now merged into the [CoSMeTIC](https://github.com/disys-lab/cosmetic) zkSNARK framework.

- **ML document validation for CliQloan**, a mortgage loan origination system · *Industry, Tirzok, 2023*
  Document classifiers sort and trim borrower documents before AWS Textract extracts key fields for automatic checks: **45× faster** than manual validation (scikit-learn, AWS Lambda, ECR, Amazon MQ, Spring Boot, PostgreSQL).

- **Automatic DDoS defense for cloud service meshes** · *Research, second author, under review at ICOIN 2027* · [Paper](https://drive.google.com/file/d/1KdqIUXU8p5YX9Xib-yazjfmLLQQOJWKe/view?usp=sharing) · [Prototype code](https://github.com/nazrulhuda/AI-Driven-Anomaly-Detector-and-mitigation-as-a-service)
  A Kubernetes and Istio framework that detects attacks with a separate ML model for each service (**94.0–97.8% accuracy**) and moves traffic to backup versions automatically, with no changes to application code. Running the models in parallel made detection **2.27× faster**.

- **Backend of [Janatar Sarkar](https://janatarsarkar.gov.bd/)**, a Bangladesh government portal · *Industry, Tirzok, 2023*
  REST APIs and JWT role management for a portal serving **80,000+ citizens**; optimized MongoDB aggregation pipelines for **40% lower query latency** (Node.js, MongoDB).

- **FwdStar**, a freight marketplace platform · *Technical lead and sole architect, 2026–present*
  Next.js, FastAPI, PostgreSQL/PostGIS, 50+ REST endpoints, row-level locking so a load is never awarded twice, and layered security (JWT/JWKS, CSRF, OTP rate limiting).

### 📄 Selected publications

- **Faster image retrieval over the cloud** · corresponding author, *IEEE Transactions on Cloud Computing* · [Paper](https://ieeexplore.ieee.org/document/9743811)
  Customized progressive JPEG that cut user waiting time by up to 54% and image size by up to 27%.
- **The digital divide in remote Indigenous communities** · fieldwork in 15 mountain villages in Bangladesh; published at ACM COMPASS 2026, with papers under review at ACM CHI 2027 and *Social Sciences & Humanities Open*.



### 🧰 Tech stack

**AI and ML:**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat-square)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

**Data:**
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

**Backend and web:**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)

**Cloud and infrastructure:**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Istio](https://img.shields.io/badge/Istio-466BB0?style=flat-square&logo=istio&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
