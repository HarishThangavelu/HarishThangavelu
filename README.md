<p align="center">
  <img src="./banner.svg" alt="Harish Thangavelu — ML & AI Engineer" width="100%"/>
</p>

<p align="center">
  <a href="https://harishthangavelu.github.io"><img src="https://img.shields.io/badge/Portfolio-harishthangavelu.github.io-6c63ff?style=flat-square&labelColor=1c1c26" alt="Portfolio"/></a>
  <a href="https://linkedin.com/in/harish-thangavelu"><img src="https://img.shields.io/badge/LinkedIn-harish--thangavelu-0A66C2?style=flat-square&logo=linkedin&logoColor=white&labelColor=1c1c26" alt="LinkedIn"/></a>
  <a href="mailto:harishthangavelu26@gmail.com"><img src="https://img.shields.io/badge/Email-harishthangavelu26%40gmail.com-00b894?style=flat-square&logo=gmail&logoColor=white&labelColor=1c1c26" alt="Email"/></a>
  <img src="https://img.shields.io/badge/Open_to-ML_%2F_CV_roles-8fbfb3?style=flat-square&labelColor=1c1c26" alt="Open to ML and CV roles"/>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Inter&weight=500&size=18&duration=3200&pause=900&color=A7A3D9&center=true&vCenter=true&width=640&height=40&lines=Hybrid+physics+%2B+ML+models+for+orbit+prediction;Computer+vision+pipelines+that+ship+to+production;Backends+and+RAG+systems+with+FastAPI+%2B+PostgreSQL" alt="Typing summary"/>
</p>

I'm an ML engineer based in Erlangen, Germany, studying for an M.Sc. in Electromobility at FAU (AI & Autonomous Driving). I like problems where physics, data and software meet: correcting orbit propagators with learned residuals, automating annotation for industrial computer vision, and building the backends that put these models in front of users.

---

### Recent work

| When | Role | Highlights |
| :--- | :--- | :--- |
| **Apr – Oct 2026** <br/><sub>✅ Completed</sub> | **Project Thesis** · FAPS, FAU Erlangen-Nürnberg <br/><sub>Residual Learning for Satellite Orbit Prediction (Hybrid SGP4 + LSTM)</sub> | Cut 1-hour position RMSE from **0.569 km → 0.098 km (−82.9%)** vs. SGP4 alone; velocity error −90.4%, still −36% at 24 h. Traced long-horizon loss to a ~93-min along-track oscillation via RTN decomposition and spectral analysis. Fully reproducible PyTorch repo with negative results reported openly. |
| **Mar – Aug 2026** <br/><sub>✅ Completed</sub> | **Freelance AI Backend Engineer** · Kaampass (UK) | Built a retrieval pipeline from scratch (chunking, embeddings, similarity search) reaching **91% retrieval accuracy** on real job-matching data. FastAPI backend on PostgreSQL / Supabase, deployed live. |
| **Oct 2025 – Feb 2026** | **Computer Vision Intern** · FranconAI, Erlangen | Automated CVAT annotation for wire-harness diagrams: OCR preprocessing, rotated-box inference (Gliding Vertex / MMRotate) in Docker, and a bandit-style optimizer for class-wise thresholds. **~70% fewer spurious predictions, 3.2× annotation throughput.** |
| **Oct 2026 – now** <br/><sub>🛠️ Building</sub> | **NexOrg ERP** · personal project | Role-based hotel operations platform (React, TypeScript, Node.js, PostgreSQL, Prisma) on AWS with Docker and GitHub Actions CI/CD; race-condition-safe bookings and 150+ automated tests. |

### Selected projects

- 🛰️ **Hybrid orbit prediction (SGP4 + LSTM)**: learns the residual between SGP4 and ESA Swarm-A reference orbits from Space-Track TLEs (TEME → ITRS), with 3D visualisation in CesiumJS.
- 🎙️ **AI voice agent**: inbound call handling with Twilio, n8n, OpenAI and ElevenLabs; summaries go out via WhatsApp and meetings are booked in Google Calendar.
- 🤖 **Autonomous navigation (ROS2 + Gazebo)**: A* planning with LiDAR / SLAM feedback, plus distance thresholds that decide whether to stop, reroute or continue.
- 📦 **Multi-view object dimension estimation**: measures length, width and height of inventory items using a custom-trained detector and Depth Anything V2, with a confidence score per measurement.

---

### Tech stack

<p>
  <img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow,opencv,sklearn&theme=dark" alt="ML stack"/>
  &nbsp;
  <img src="https://skillicons.dev/icons?i=fastapi,django,nodejs,react,ts,postgres,supabase,prisma&theme=dark" alt="Backend stack"/>
  &nbsp;
  <img src="https://skillicons.dev/icons?i=docker,aws,githubactions,linux,git,ros&theme=dark" alt="Infra stack"/>
</p>

<details>
<summary><b>Full skill list</b></summary>
<br/>

| Area | Tools & methods |
| :--- | :--- |
| **Orbital mechanics & space data** | SGP4, TLE processing, Space-Track, ESA Swarm precise orbits, TEME / ITRS / RTN frames, error decomposition, spectral analysis |
| **Time series & ML** | LSTM residual models, multi-horizon forecast evaluation, bandit-style adaptive optimisation, PyTorch, TensorFlow |
| **Computer vision** | OpenMMLab (MMDetection, MMRotate), Gliding Vertex, YOLO, CVAT, OCR, Depth Anything V2, SLAM |
| **Modelling & simulation** | Physics-based simulation, state-space models, numerical integration, surrogate models, Gazebo, CesiumJS |
| **Backend & automation** | REST APIs, FastAPI, Django, React, Docker, n8n, API integration |
| **Cloud & data** | AWS (EC2, SageMaker), containerised deployment, PostgreSQL, Supabase |

</details>

### Education & certifications

- 🎓 **M.Sc. Electromobility**, FAU Erlangen-Nürnberg (2023 – present): AI & Autonomous Driving, Sustainable Mobility & Production Technology
- 🎓 **B.E. Mechanical Engineering**, KGiSL Institute of Technology (2018 – 2022), CGPA 8.2 / 10
- 📜 AWS Essentials (Cognizant) · ROS Certification (The Construct)
- 🌍 English (C1) · German (A2) · Tamil (native)

---

<p align="center">
  <sub>Open to full-time and working-student roles in ML, computer vision and applied AI. Feel free to reach out.</sub>
</p>
