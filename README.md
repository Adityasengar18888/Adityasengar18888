<div align="center">

<img src="./assets/hero-dossier.svg" width="100%" alt="Aditya Sengar — The Mentalist inspired developer dossier"/>

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Courier+Prime&weight=700&size=18&duration=2600&pause=800&color=E34B59&center=true&vCenter=true&width=850&lines=OBSERVE.+ANALYSE.+ENGINEER.;AI+%2F+ML+%C2%B7+FULL+STACK+%C2%B7+SYSTEMS;THE+TRUTH+IS+IN+THE+DETAILS." alt="Animated introduction"/>

<br/>

<img src="https://img.shields.io/badge/CASE%20FILE-AS--18888-9B1426?style=for-the-badge&labelColor=09090D"/>
<img src="https://img.shields.io/badge/STATUS-BUILDING%20IN%20PROGRESS-9B1426?style=for-the-badge&labelColor=09090D"/>
<img src="https://img.shields.io/badge/LOCATION-INDIA-9B1426?style=for-the-badge&labelColor=09090D"/>

<br/><br/>

<a href="https://github.com/Adityasengar18888"><img src="https://img.shields.io/badge/GITHUB-OPEN%20CASE-181717?style=for-the-badge&logo=github"/></a>
<a href="https://www.linkedin.com/in/aditya-sengar-62427730a/"><img src="https://img.shields.io/badge/LINKEDIN-CONNECT-0A66C2?style=for-the-badge&logo=linkedin"/></a>
<a href="https://leetcode.com/"><img src="https://img.shields.io/badge/LEETCODE-190%2B%20SOLVED-FFA116?style=for-the-badge&logo=leetcode&logoColor=black"/></a>

</div>

---

<div align="center">

## 🔴 THE RED JOHN FILE

*“The details are always there. You just have to know where to look.”*

**SUBJECT:** Aditya Sengar  
**ROLE:** Computer Science Undergraduate · Software Developer · AI/ML Explorer  
**INSTITUTION:** Jaypee Institute of Information Technology (JIIT)

</div>

I'm a Computer Science undergraduate interested in building software that is technically sound, useful and thoughtfully engineered. My work spans **applied AI, full-stack development, machine learning, data science and systems engineering**.

I like understanding what happens behind the interface: how a retrieval pipeline finds evidence, how a neural network learns, how a scheduler allocates CPU time, and how a real-time application keeps multiple clients synchronized.

**My approach:** Observe the problem → identify the pattern → engineer the solution → verify the result.

<div align="center">

<img src="https://img.shields.io/badge/01-OBSERVE-65101D?style=flat-square"/>
<img src="https://img.shields.io/badge/02-ANALYSE-7D1726?style=flat-square"/>
<img src="https://img.shields.io/badge/03-ENGINEER-A52535?style=flat-square"/>
<img src="https://img.shields.io/badge/04-VERIFY-C33B4A?style=flat-square"/>

</div>

---

## 📌 CASE DASHBOARD — BY THE NUMBERS

<div align="center">

<img src="https://img.shields.io/badge/24-PUBLIC%20REPOSITORIES-8B1526?style=for-the-badge&labelColor=101014"/>
<img src="https://img.shields.io/badge/190%2B-LEETCODE%20PROBLEMS-8B1526?style=for-the-badge&labelColor=101014"/>
<img src="https://img.shields.io/badge/9-NEURAL%20MODEL%20FAMILIES-8B1526?style=for-the-badge&labelColor=101014"/>

<img src="https://img.shields.io/badge/5-CPU%20SCHEDULING%20ALGORITHMS-8B1526?style=for-the-badge&labelColor=101014"/>
<img src="https://img.shields.io/badge/1%20MB-TCP%20PAYLOAD%20LIMIT-8B1526?style=for-the-badge&labelColor=101014"/>
<img src="https://img.shields.io/badge/6%20WEEKS-INDUSTRIAL%20TRAINING-8B1526?style=for-the-badge&labelColor=101014"/>

</div>

<sub>Repository count is based on the public profile listing. Other figures describe documented project scope or milestones; they are not third-party performance benchmarks.</sub>

---

## 🧩 THE SKILL WALL

<div align="center">

<img src="https://skillicons.dev/icons?i=python,cpp,java,js,ts,react,nextjs,nodejs,express,fastapi,flask,html,css,tailwind,mysql,postgres,git,github,docker,linux,vite,threejs&perline=11" alt="Programming languages, frameworks and tools"/>

<br/><br/>

<img src="https://img.shields.io/badge/AI%20%26%20ML-PyTorch%20%7C%20Scikit--learn%20%7C%20Transformers-171014?style=for-the-badge&labelColor=741626"/>
<img src="https://img.shields.io/badge/GEN%20AI-Gemini%20%7C%20RAG%20%7C%20Embeddings-171014?style=for-the-badge&labelColor=741626"/>
<img src="https://img.shields.io/badge/DATA-Pandas%20%7C%20NumPy%20%7C%20SQL-171014?style=for-the-badge&labelColor=741626"/>

</div>

<details>
<summary><b>🔍 Technical evidence — expand the skill inventory</b></summary>

**Programming & CS:** Python, C++, Java, JavaScript, TypeScript, data structures and algorithms, OOP, complexity analysis.

**Frontend:** React, Next.js, Vite, Tailwind CSS, responsive UI, state management.

**Backend:** Node.js, Express, FastAPI, Flask, REST APIs, WebSockets, TCP socket programming.

**AI / ML:** NumPy, Pandas, Scikit-learn, PyTorch, Hugging Face Transformers, NLP, embeddings, RAG, computer vision, YOLO, model evaluation.

**Data & infrastructure:** MySQL, PostgreSQL, SQLite, Prisma, Redis, Git, GitHub, Docker, Linux, Vercel, Netlify, Render, Cloudinary.

**3D & visualization:** Three.js, globe.gl, MapLibre GL, Recharts, Plotly.

</details>

---

# 🗃️ THE FIVE FEATURED CASES

*Five selected builds. Five different engineering investigations.*

## 01 / WikiRAG
<sub>CASE CLASSIFICATION · GENERATIVE AI / RETRIEVAL SYSTEMS</sub>

<img src="./assets/project-wikirag.svg" width="100%" alt="3D vector knowledge retrieval and semantic search illustration"/>

**A Wikipedia question-answering system that retrieves relevant information and produces grounded answers with citations.**

- Text chunking, embedding generation and semantic retrieval.
- ChromaDB vector storage and similarity search.
- Gemini-powered response generation.
- FastAPI backend with streaming answers.
- Source citations for traceable responses.

**Pipeline**

```mermaid
flowchart LR
    A[User Query] --> B[FastAPI]
    B --> C[Query Embedding]
    C --> D[(ChromaDB)]
    D --> E[Retrieved Context]
    E --> F[Gemini]
    F --> G[Answer + Citations]
    style D fill:#48101b,stroke:#d94b5c,color:#fff
    style F fill:#48101b,stroke:#d94b5c,color:#fff
```

<sub>STACK</sub> Python · FastAPI · Gemini · ChromaDB · Embeddings · RAG

🔗 [Explore WikiRAG](https://github.com/Adityasengar18888/WikiRAG)

---

## 02 / Model Zoo
<sub>CASE CLASSIFICATION · DEEP LEARNING / NEURAL COMPUTATION</sub>

<img src="./assets/project-modelzoo.svg" width="100%" alt="Three-dimensional neural network architecture illustration"/>

**A neural-network experimentation platform focused on understanding model architectures and the mechanics of learning.**

<sub>9 MODEL FAMILIES DOCUMENTED</sub>

<div align="center">

<img src="https://img.shields.io/badge/01-DENSE%20NN-741626?style=flat-square"/>
<img src="https://img.shields.io/badge/02-CNN-741626?style=flat-square"/>
<img src="https://img.shields.io/badge/03-RNN-741626?style=flat-square"/>
<img src="https://img.shields.io/badge/04-LSTM-741626?style=flat-square"/>
<img src="https://img.shields.io/badge/05-TRANSFORMER-741626?style=flat-square"/>
<img src="https://img.shields.io/badge/06-AG%20NEWS-741626?style=flat-square"/>
<img src="https://img.shields.io/badge/07-GCN-741626?style=flat-square"/>
<img src="https://img.shields.io/badge/08-RESNET-741626?style=flat-square"/>
<img src="https://img.shields.io/badge/09-GAN-741626?style=flat-square"/>

</div>

- NumPy-based automatic differentiation and tensor operations.
- Forward propagation and backpropagation.
- Model training, evaluation and optimization.
- Experiments spanning MNIST, CIFAR-10, IMDB, AG News, Cora and Tiny Shakespeare.
- FastAPI-powered model exploration interface.

<sub>STACK</sub> Python · NumPy · FastAPI · Neural Networks · CNN · RNN · LSTM · Transformers · GAN · GCN

🔗 [Explore Model Zoo](https://github.com/Adityasengar18888/Model-Zoo)

---

## 03 / VGARSS 2.0
<sub>CASE CLASSIFICATION · OPERATING SYSTEMS / NETWORKING / COLLABORATION</sub>

<img src="./assets/project-vgarss.svg" width="100%" alt="Isometric process scheduling and real-time networking illustration"/>

**Virtual Group Asynchronous Real-Time Resource Synchronization & Scheduling System.**

A multi-user collaboration platform combining task coordination, real-time communication and interactive operating-system simulations.

**Operating systems laboratory**
- FCFS, SJF, SRTF, Round Robin and Priority scheduling with aging.
- Five-state process lifecycle visualization.
- Mutex and semaphore synchronization.
- Deadlock detection using wait-for graph cycle detection.
- Gantt charts and scheduling metrics.

**Networking laboratory**
- Authenticated WebSocket communication.
- Real-time presence and message synchronization.
- Offline message catch-up, heartbeat and latency monitoring.
- Concurrent TCP server with paired-client message forwarding.
- Four-byte big-endian length-prefixed message framing.
- Configured payload protection up to **1 MB**.

<div align="center">

<img src="https://img.shields.io/badge/5-SCHEDULING%20ALGORITHMS-741626?style=for-the-badge"/>
<img src="https://img.shields.io/badge/5-PROCESS%20STATES-741626?style=for-the-badge"/>
<img src="https://img.shields.io/badge/1%20MB-PAYLOAD%20LIMIT-741626?style=for-the-badge"/>

</div>

<sub>STACK</sub> Python · FastAPI · React · TypeScript · WebSockets · TCP · SQLite · PostgreSQL

🔗 [Explore VGARSS](https://github.com/Adityasengar18888/VGARSS) · 🌐 [Live Demo](https://vgarss.vercel.app)

---

## 04 / Smart Parking & Traffic Monitoring
<sub>CASE CLASSIFICATION · COMPUTER VISION / REAL-TIME AUTOMATION</sub>

<img src="./assets/project-parking.svg" width="100%" alt="Isometric AI smart parking camera and vehicle tracking illustration"/>

**A computer-vision system for vehicle detection, parking occupancy, number-plate recognition and traffic monitoring.**

- YOLOv8 vehicle detection.
- DeepSORT tracking with persistent object IDs.
- EasyOCR number-plate recognition.
- OpenCV parking-space occupancy detection.
- Line-based speed estimation and violation logging.
- Duration-based parking billing and PDF receipts.
- Live dashboard and CSV reporting.

```mermaid
flowchart TD
    A[Camera Feed] --> B[YOLOv8 Detection]
    B --> C[DeepSORT Tracking]
    C --> D[Vehicle Identity]
    C --> E[Parking Occupancy]
    C --> F[Speed Estimation]
    D --> G[Flask + Socket.IO]
    E --> G
    F --> G
    G --> H[Dashboard / Reports / Billing]
    style B fill:#48101b,stroke:#d94b5c,color:#fff
    style C fill:#48101b,stroke:#d94b5c,color:#fff
```

<sub>STACK</sub> Python · OpenCV · YOLOv8 · DeepSORT · EasyOCR · Flask · Socket.IO · ReportLab

🔗 [Explore Smart Parking](https://github.com/Adityasengar18888/Smart-Parking-and-Traffic-Monitoring-System)

---

## 05 / MIKMOK
<sub>CASE CLASSIFICATION · FULL-STACK / SOCIAL PRODUCT ENGINEERING</sub>

<img src="./assets/project-mikmok.svg" width="100%" alt="Three-dimensional mobile short-video social platform illustration"/>

**A short-form video social platform built around creator interactions, media uploads and content discovery.**

- Vertical short-video feed.
- Clerk authentication and user authorization.
- Cloudinary video upload and media storage.
- Likes, comments, shares and creator follows.
- Search across users, videos and hashtags.
- Notifications and PostgreSQL-backed application data.
- Responsive Next.js interface.

**Application architecture**

```mermaid
flowchart LR
    A[Next.js / TypeScript] --> B[Express API]
    B --> C[(PostgreSQL)]
    B --> D[Cloudinary]
    E[Clerk Auth] --> A
    F[Prisma ORM] --> C
    style C fill:#48101b,stroke:#d94b5c,color:#fff
    style D fill:#48101b,stroke:#d94b5c,color:#fff
```

<sub>STACK</sub> Next.js · React · TypeScript · Tailwind CSS · Clerk · Express · Prisma · PostgreSQL · Cloudinary · Zustand · React Query

🌐 [Live Project](https://mikmok-nu.vercel.app) · 🔗 [Source Code](https://github.com/Adityasengar18888/MIKMOK)

---

## 🧪 BEYOND THE FIVE — RESEARCH & EXPERIMENTS

The featured projects are the primary portfolio. Other technical explorations include:

- **ResonanceStorm:** Three.js, WebXR, multiplayer synchronization and a custom Verlet-based physics simulation.
- **ApxForge:** Black–Scholes option pricing, Greeks, payoff visualization and quantitative analytics.
- **Glassdoor Review Summarizer:** DistilBART summarization, DistilBERT sentiment analysis and FastAPI.
- **TerraScope:** 3D globe, MapLibre GL, geographic exploration and itinerary planning.
- **Business Entity Resolution:** Record linkage, normalization, candidate generation and matching.

[Browse all public repositories →](https://github.com/Adityasengar18888?tab=repositories)

---

# 🎓 EDUCATION & CREDENTIALS

<div align="center">

<img src="https://img.shields.io/badge/EDUCATION-JIIT%20%7C%20B.TECH%20CSE-741626?style=for-the-badge"/>
<img src="https://img.shields.io/badge/FOCUS-COMPUTER%20SCIENCE-741626?style=for-the-badge"/>

</div>

**Jaypee Institute of Information Technology (JIIT)**  
B.Tech — Computer Science and Engineering · 2024–Present

**Professional training**
- AppDrive Technologies Pvt. Ltd. — Industrial training, 6 weeks (June–July 2026).
- Labmentix — AI/ML internship experience.

### Certification vault

<div align="center">

<img src="https://img.shields.io/badge/GOOGLE-ADVANCED%20DATA%20ANALYTICS-4285F4?style=for-the-badge&logo=google"/>
<img src="https://img.shields.io/badge/IBM-MACHINE%20LEARNING%20WITH%20PYTHON-052FAD?style=for-the-badge&logo=ibm"/>
<img src="https://img.shields.io/badge/DEEPL EARNING.AI-APPLIED%20STATISTICS-8B1526?style=for-the-badge"/>

</div>

**Google**
- Google Advanced Data Analytics Professional Certificate.
- The Nuts and Bolts of Machine Learning.
- Foundations of Data Science.
- Go Beyond the Numbers: Translate Data into Insights.
- Regression Analysis: Simplify Complex Data Relationships.
- The Power of Statistics.

**IBM**
- Machine Learning with Python.

**DeepLearning.AI**
- Applied Statistics for Data Analytics.
- Data Analytics Foundations.

**HackerRank**
- Frontend Developer (React).

**Hackathons & participation**
- Chronomind — Certificate of Participation.
- BLACKBOX.AI — Offline Round.
- Innovate 3.0 — Final Round.
- HackwithIndia — Vibe Hack 2.0.

<a href="https://www.linkedin.com/in/aditya-sengar-62427730a/"><img src="https://img.shields.io/badge/VIEW%20LINKEDIN%20CREDENTIALS-OPEN%20PROFILE-8B1526?style=for-the-badge&logo=linkedin"/></a>

---

# ⚔️ THE TRAINING ROOM — PROBLEM SOLVING

<div align="center">

<img src="https://leetcard.jacoblin.cool/Adityasengar18888?theme=dark&font=Baloo&ext=heatmap" width="90%" alt="LeetCode problem solving activity"/>

</div>

**Areas of practice:** Arrays · Hashing · Linked Lists · Trees · Graphs · Dynamic Programming · Greedy · Binary Search · Sliding Window · Complexity Analysis.

---

# 📈 THE EVIDENCE WALL — LIVE GITHUB DATA

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Adityasengar18888&show_icons=true&hide_border=true&bg_color=0B0B10&title_color=E34B59&icon_color=E34B59&text_color=E8E0E5&ring_color=9B1426&include_all_commits=true" width="49%" alt="GitHub statistics"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Adityasengar18888&layout=compact&hide_border=true&bg_color=0B0B10&title_color=E34B59&text_color=E8E0E5&langs_count=8" width="49%" alt="Most used languages"/>

<br/><br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Adityasengar18888&hide_border=true&background=0B0B10&ring=E34B59&fire=FF6978&currStreakLabel=E8E0E5&sideLabels=E8E0E5&currStreakNum=FFFFFF&sideNums=FFFFFF&dates=999999" width="85%" alt="GitHub contribution streak"/>

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Adityasengar18888&bg_color=0B0B10&color=E8E0E5&line=E34B59&point=FFFFFF&area=true&hide_border=true" width="98%" alt="GitHub activity graph"/>

</div>

## 🧊 3D CONTRIBUTION CHAMBER

<div align="center">

<img src="./profile-3d-contrib/profile-custom-red.svg" width="98%" alt="3D GitHub contribution calendar in a crimson and black theme"/>

<br/>

<img src="https://github-profile-trophy.vercel.app/?username=Adityasengar18888&theme=darkhub&no-frame=true&no-bg=true&margin-w=8&column=7" width="98%" alt="GitHub achievement trophies"/>

</div>

<sub>The 3D contribution graphic is generated by the profile repository's scheduled GitHub Actions workflow. Run the workflow once from the Actions tab to generate the first image.</sub>

---

# 🕵️ CURRENT INVESTIGATION

<div align="center">

<img src="https://img.shields.io/badge/01-APPLIED%20AI-741626?style=for-the-badge"/>
<img src="https://img.shields.io/badge/02-FULL%20STACK-741626?style=for-the-badge"/>
<img src="https://img.shields.io/badge/03-ROBOTICS%20%26%20RL-741626?style=for-the-badge"/>
<img src="https://img.shields.io/badge/04-SYSTEMS%20ENGINEERING-741626?style=for-the-badge"/>
<img src="https://img.shields.io/badge/05-DATA%20SCIENCE-741626?style=for-the-badge"/>

</div>

---

# 📡 ESTABLISH CONTACT

<div align="center">

<a href="https://github.com/Adityasengar18888"><img src="https://img.shields.io/badge/GITHUB-ADITYASENGAR18888-181717?style=for-the-badge&logo=github"/></a>
<a href="https://www.linkedin.com/in/aditya-sengar-62427730a/"><img src="https://img.shields.io/badge/LINKEDIN-ADITYA%20SENGAR-0A66C2?style=for-the-badge&logo=linkedin"/></a>

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=venom&height=170&color=0:08090D,50:570D1B,100:08090D&text=THE%20GAME%20IS%20NEVER%20OVER.&fontColor=F4E9EC&fontSize=25&animation=fadeIn" width="100%" alt="Cinematic red and black closing banner"/>

**OBSERVE. THINK. BUILD. REPEAT.**

<sub>CASE FILE AS-18888 · THE MENTALIST EDITION · LAST UPDATED NOVEMBER 2026</sub>

</div>
