<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:16222e,100:1f3a4d&height=230&section=header&text=Bavley%20Hesham&fontSize=60&fontColor=e6edf3&fontAlignY=40&desc=AI%20Engineer%20%7C%20Machine%20Learning%20Engineer%20%7C%20Computer%20Vision&descSize=18&descColor=8fb8d8&descAlignY=62" width="100%" alt="Bavley Hesham"/>

<a href="https://github.com/Bavleyhesham8">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=19&pause=1400&color=58A6FF&center=true&vCenter=true&width=760&lines=Skeleton-based+group+activity+recognition;91.10%25+Top-1+with+only+883K+parameters;Research+models+shipped+behind+FastAPI;RAG+%7C+Multi-Agent+Systems+%7C+LoRA%2FPEFT" alt="Typing animation"/>
</a>

<br/><br/>

<a href="https://www.linkedin.com/in/bavley-hesham-50886a275"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="https://www.kaggle.com/bavleyhesham"><img src="https://img.shields.io/badge/Kaggle-bavleyhesham-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white" alt="Kaggle"/></a>
<a href="mailto:bavleyhesham209@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
<img src="https://img.shields.io/badge/Location-Cairo%2C%20Egypt-30363d?style=for-the-badge" alt="Location"/>
<img src="https://img.shields.io/badge/Status-Open%20to%20work-2ea043?style=for-the-badge" alt="Open to work"/>

</div>

<br/>

## About

I am an **AI and Machine Learning Engineer** specialized in **Computer Vision**. I build end-to-end systems: I design the model, build the data pipeline, and ship it behind a real API and interface. My research focuses on **skeleton-based group activity recognition** using Graph Neural Networks and Transformers, and I also build with **RAG, multi-agent systems, and LoRA/PEFT fine-tuning**.

| | |
|---|---|
| **Education** | B.Sc. Computer Science (AI), Benha University, GPA 3.4/4.0 (2022 to 2026) |
| **Currently** | Programming Tutor at iSchool, and looking for AI / Computer Vision / ML Engineer roles |
| **Recognition** | Codeforces Specialist, GCI World 2026 (University of Tokyo), Aspire Fellow |
| **Focus** | Computer Vision, Graph Neural Networks, Agentic AI, real-time inference |

<br/>

## Results at a Glance

<div align="center">

<img src="https://img.shields.io/badge/Top--1%20Accuracy-91.10%25-1f6feb?style=flat-square" alt="Top-1"/>
<img src="https://img.shields.io/badge/F1%20Score-91.07%25-1f6feb?style=flat-square" alt="F1"/>
<img src="https://img.shields.io/badge/Model%20Size-883K%20params-8957e5?style=flat-square" alt="Params"/>
<img src="https://img.shields.io/badge/Training%20Clips-4%2C830-8957e5?style=flat-square" alt="Clips"/>
<img src="https://img.shields.io/badge/Annotated%20Tasks-2%2C200%2B-2ea043?style=flat-square" alt="Tasks"/>
<img src="https://img.shields.io/badge/Students%20Taught-25%2B-2ea043?style=flat-square" alt="Students"/>
<img src="https://img.shields.io/badge/Course%20Pass%20Rate-%2B30%25-2ea043?style=flat-square" alt="Pass rate"/>

</div>

<br/>

## Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### Group Activity Recognition V2
**VAT-Former** classifies what a volleyball team is doing using only body keypoints, with no raw video frames.

`91.10% Top-1` &nbsp; `91.07% F1` &nbsp; `883K params`

- Watches 12 players at once and identifies 8 team-level activities
- 4,830 clips from 55 match videos, 17-joint YOLO-Pose extraction
- Skeleton GCN, Motion and Context Encoder, Spatial-Temporal Transformer
- 4-stage curriculum learning

`PyTorch` `GNN` `Transformer` `YOLO-Pose`

**[View repository](https://github.com/Bavleyhesham8/Group_Activity_Recognition_V2)**

</td>
<td width="50%" valign="top">

### SmartClass AI
A school attendance and security system: identifies registered students, logs attendance, detects raised hands, and alerts staff when an unknown person enters.

`CUDA-accelerated` &nbsp; `Real-time` &nbsp; `Role-based portals`

- InsightFace, YOLO, and ByteTrack pipeline
- Guided biometric enrollment with live pitch and yaw feedback
- React and FastAPI web layer for admins, teachers, and parents
- Edge sync through SQLite and NPZ bridging

`InsightFace` `YOLO` `FastAPI` `React`

**[View repository](https://github.com/Bavleyhesham8/Smart-classroom)**

</td>
</tr>
<tr>
<td width="50%" valign="top">

### AI-Powered Fitness Coach
A real-time CV backend for a hands-free AI personal trainer: rep counting, form-error detection, and corrective voice feedback.

`FastAPI + WebSockets` &nbsp; `30 FPS`

- Three-layer evaluation: geometric state machines, VAE-based quality rejection, STGCVAE for complex movements
- Voice commands with SpeechBrain and face-lock tracking

`MediaPipe` `PyTorch` `OpenCV` `FastAPI`

**[View repository](https://github.com/Bavleyhesham8/AI-Powered-Fitness-Coach.)**

</td>
<td width="50%" valign="top">

### Pathora: AI Career Assistant
Built during the DEPI Generative and Agentic AI internship. Parses CVs, predicts job fit, generates adaptive exams, evaluates answers with an LLM, and recommends courses to close skill gaps.

`Multi-agent` &nbsp; `LLM evaluation`

`FastAPI` `React` `LangChain` `CrewAI` `RAG`

</td>
</tr>
</table>

<details>
<summary><b>VAT-Former architecture</b></summary>
<br/>

```mermaid
flowchart LR
    A[Volleyball video clip] --> B[YOLO-Pose<br/>17 joints x 12 players]
    B --> C[Skeleton GCN<br/>pose representation]
    C --> D[Motion and Context Encoder<br/>movement dynamics]
    D --> E[Spatial-Temporal Transformer<br/>team interactions]
    E --> F[8 group activities<br/>spike, pass, set, ...]
```

</details>

<br/>

## Technical Skills

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)

</div>

| Area | Tools and Techniques |
|---|---|
| **Computer Vision** | OpenCV, YOLO, YOLO-Pose, MediaPipe, InsightFace, ByteTrack, segmentation, SURF |
| **Deep Learning** | CNNs, LSTMs, VAEs, GANs, GCNs, Transformers, TCNs, LoRA/PEFT |
| **Agentic and LLM** | RAG, LangChain, CrewAI, multi-agent systems, prompt engineering |
| **Data and ML** | EDA, feature engineering, data pipelines, ETL, model evaluation |
| **Engineering** | FastAPI, WebSockets, real-time inference, edge deployment, CUDA |
| **Familiar with** | AWS, Docker, Kubernetes, CI/CD, MLOps basics |

<br/>

## Experience

| Period | Role | Organization | Highlights |
|---|---|---|---|
| 07/2026 to Present | **Programming Tutor** | iSchool | Teaching Python, mBlock, and VEX Robot coding to grade 5 and 6 students |
| 12/2025 to 06/2026 | **Generative and Agentic AI Intern** | Digital Egypt Pioneers Initiative (DEPI) | Built Pathora; covered RAG, multi-agent systems, LoRA/PEFT, and cloud deployment of agents |
| 07/2025 to 08/2025 | **Computer Vision Trainee** | National Telecommunication Institute (NTI) | 120-hour program: image processing, edge detection, segmentation, SURF, YOLO |
| 10/2024 to 08/2025 | **Python and Problem-solving Instructor** | IEEE El-Shorouk Academy | Taught 25+ students, +30% pass rate, mentored 6 project teams |
| 2026 | **AI Data Annotator (Video)** | micro1 | Verified 2,200+ video descriptions with 100% hidden-check accuracy |

<br/>

## Certifications and Honors

| Year | Recognition | Issuer |
|---|---|---|
| 2026 | **GCI World 2026**, 4-month competitive AI and Data Science scholarship | Matsuo-Iwasawa Laboratory, University of Tokyo |
| 2026 | **Machine Learning Diploma** | Get Skilled Academy |
| 2025 | **Aspire Fellow**, selected from a global cohort | Aspire Leaders Program |
| 2025 | **Building LLMs with Prompt Engineering** | NVIDIA |

<br/>

<!--
OPTIONAL: live GitHub stats cards.
The public github-readme-stats instance is often rate-limited and shows errors,
so these are disabled by default. Uncomment only after self-hosting it.

<div align="center">
<img height="170" src="https://YOUR-OWN-INSTANCE/api?username=Bavleyhesham8&show_icons=true&theme=github_dark&hide_border=true"/>
<img height="170" src="https://YOUR-OWN-INSTANCE/api/top-langs/?username=Bavleyhesham8&layout=compact&theme=github_dark&hide_border=true"/>
</div>
-->

<div align="center">

## Let's Build Something

If you are working on computer vision, agentic systems, or ML in production, I would like to hear about it.

<a href="https://www.linkedin.com/in/bavley-hesham-50886a275"><img src="https://img.shields.io/badge/Message%20me%20on%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1f3a4d,50:16222e,100:0d1117&height=110&section=footer" width="100%" alt=""/>

</div>
