<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,12,20&height=200&section=header&text=Jayadeep%20Gowda&fontSize=80&fontColor=fff&animation=twinkling&fontAlignY=35" width="100%"/>

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=22&duration=2800&pause=1200&color=00D9FF&center=true&vCenter=true&width=700&lines=Robotics+%26+AI+Engineer+%40+BIT+Bangalore;IISc+Research+Intern+%E2%80%94+Dept.+of+CDS;Edge+AI+%7C+Deployed+on+%2450+Hardware%2C+Not+Cloud;2.7B+LLM+Running+on+a+Raspberry+Pi" />

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://jayadeepgowda.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/jay7788)
[![Email](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jayadeepgowda24@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-161B22?style=for-the-badge&logo=github&logoColor=white)](https://github.com/jay7-tech)

<img src="https://komarev.com/ghpvc/?username=jay7-tech&label=Profile+Views&color=00D9FF&style=flat-square" />

</div>

---

<div align="center">

```
 ╔══════════════════════════════════════════════════════════════════════╗
 ║                                                                      ║
 ║   INPUT              PROCESSING              OUTPUT                  ║
 ║                                                                      ║
 ║  [Camera] ──►─┐                          ┌─►── [Robot Body]         ║
 ║  [Mic]    ──►─┼──► [YOLOv8 · Whisper] ──►┤                          ║
 ║  [Sensor] ──►─┘           │              └─►── [Voice + Text]       ║
 ║                            ▼                                         ║
 ║                   [Phi-2 · 4-bit · RAG]                              ║
 ║                            │                                         ║
 ║           latency: 600ms · uptime: 98.4% · no cloud                 ║
 ║                   runs on: Raspberry Pi 5                            ║
 ║                                                                      ║
 ╚══════════════════════════════════════════════════════════════════════╝
```

</div>

---

## `whoami`

```yaml
name     : Jayadeep Gowda K B
degree   : B.E. Robotics & AI  —  BIT Bangalore  (CGPA 8.88 / 10)
research : IISc Bangalore · Dept. of Computational & Data Sciences
           └─ 17 ML/DL models benchmarked · 5-fold CV · Intl collab (AGH Univ. Poland)
focus    : Edge AI · Robotics Control · LLM Systems · Computer Vision
rule     : "If it doesn't run on $50 hardware, it isn't deployed."
open_to  : Research · AI/ML · Robotics internships  (2026 – 2027)
```

---

## `git log --oneline --all`

```
● Mar 2026  IISc CDS — 17 models on MXene piezoresistive wristband sensor data
│           21 time/freq-domain features · international collab · AGH Univ. Poland
│
● Jan 2026  Sirena AI — Quadruped · Humanoid · Hexapod full lifecycle
│           custom IK solvers · 12-state FSM · <50ms ZeroMQ latency on ARM
│
● Aug 2025  Frillory — LLM agentic pipeline · 50+ assets automated · −25% overhead
│
● Dec 2025  🥈 GlitchVerse 2k25 Project Expo  →  2nd Place
│
● Feb 2025  Anveshana National Engineering Competition  →  National Finalist
│
● Present   Joint Secretary, ROBO CELL · Core Organizer Ideathon 2025 (600+ participants)
```

---

## `ls ./projects`

<div align="center">

| | Project | What it actually does | Stack | Result |
|:---:|:---|:---|:---|:---:|
| 🤖 | **[MEMO — Neural-OS](https://github.com/jay7-tech/memo)** | Multimodal desktop robot · 6 AI pipelines · fully on-device RPi 5 | YOLOv8 · Whisper · Phi-2 · RAG · FAISS | 🥉 Best Poster |
| 🧠 | **[Cognis](https://github.com/jay7-tech/cognis)** | LLM optimizer via n-gram pattern mining · zero cloud · novel IP | Llama-3 · FAISS · FastAPI | 40–60% query cut |
| 🎥 | **[RILA](https://github.com/jay7-tech/rila)** | Turns YouTube/Reels into searchable geo+semantic memory via Telegram | Llama 3 · PostGIS · ChromaDB · Pydantic | Hybrid retrieval |
| 🛒 | **[YOLOmart](https://github.com/jay7-tech/Yolo_mart-main)** | Vision-guided autonomous shopping cart · 20 FPS · 92% mAP · deployed | ESP32 · YOLOv8 · React Native · Firebase | 🥈 2nd / 150+ teams |

</div>

---

## `cat ./memo/architecture.txt`

```
┌──────────────────────── MEMO Neural-OS ─────────────────────────┐
│                                                                  │
│   Raspberry Pi 5                                                 │
│   ┌─────────────┬──────────────┬────────────────┐               │
│   │   VISION    │    SPEECH    │    LANGUAGE    │               │
│   │  YOLOv8     │   Whisper    │  Phi-2  2.7B   │               │
│   │  FaceNet    │   ASR        │  4-bit GGUF    │               │
│   │             │              │  10–14 tok/s   │               │
│   └──────┬──────┴──────┬───────┴────────┬───────┘               │
│          └─────────────┼────────────────┘                        │
│                        ▼                                         │
│            ┌─── Orchestrator ───┐                                │
│            │  Persistent Memory │ ◄── FAISS · ChromaDB           │
│            │  Event-driven loop │                                │
│            └────────┬───────────┘                                │
│                     ▼                                            │
│            Motor Control · Voice · Display                       │
│                                                                  │
│  E2E Latency: 600ms  │  Uptime: 98.4% (72hr)  │  Zero cloud     │
└──────────────────────────────────────────────────────────────────┘
```

---

## `cat ./stack.json`

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white)
![ROS2](https://img.shields.io/badge/ROS2-22314E?style=flat-square&logo=ros&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-C51A4A?style=flat-square&logo=raspberrypi&logoColor=white)

</div>

```
Edge AI   │  INT8 quant · ONNX · OpenVINO · 4-bit GGUF · ARM deployment
Robotics  │  IK solvers · 12-state FSM · Sim-to-real · PyBullet · ROS2 · Gazebo
LLM Sys   │  RAG · FAISS · ChromaDB · Llama-3 · Phi-2 · Whisper · ZeroMQ
Data/ML   │  CNN · BiLSTM · CNN-LSTM · 5-fold CV · PostGIS · Pydantic
```

---

## `./stats.sh`

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=jay7-tech&show_icons=true&theme=radical&hide_border=true&bg_color=0D1117&title_color=00D9FF&icon_color=00D9FF&text_color=FFFFFF&rank_icon=github" />
<img height="165" src="https://streak-stats.demolab.com/?user=jay7-tech&theme=radical&hide_border=true&background=0D1117&ring=00D9FF&fire=00D9FF&currStreakLabel=00D9FF" />

<img width="70%" src="https://github-readme-activity-graph.vercel.app/graph?username=jay7-tech&custom_title=Contribution+Graph&bg_color=0D1117&color=00D9FF&line=00D9FF&point=FFFFFF&area_color=00D9FF&area=true&hide_border=true" />

</div>

---

<div align="center">

```
Currently exploring  →  Vision-Language-Action models · Safe legged locomotion
Open for             →  Research · AI/ML · Robotics internships
```

[![Reach out](https://img.shields.io/badge/Reach_out-jayadeepgowda24%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jayadeepgowda24@gmail.com)

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,12,20&height=100&section=footer" width="100%"/>
