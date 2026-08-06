<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,12,20&height=200&section=header&text=Jayadeep%20Gowda&fontSize=80&fontColor=fff&animation=twinkling&fontAlignY=35" width="100%"/>

<div align="center">

```
╔══════════════════════════════════════════════════════════════════════════╗
║  INPUT LAYER          HIDDEN LAYERS              OUTPUT LAYER            ║
║                                                                          ║
║  [Sensor Data]──►[Signal Processing]──►[Feature Extraction]──►[Deploy]  ║
║  [Video Feed] ──►[YOLOv8 / FaceNet] ──►[Inference Engine]  ──►[Robot]   ║
║  [Audio]      ──►[Whisper ASR]      ──►[LLM / RAG / FAISS] ──►[Action]  ║
║  [Physics Sim]──►[IK Solver / FSM]  ──►[Gait Controller]   ──►[Walk]    ║
║                                                                          ║
║  LATENCY: 55ms │ UPTIME: 98.4% │ PARAMS: 2.7B @ 4-bit │ HW: ARM/RPi    ║
╚══════════════════════════════════════════════════════════════════════════╝
```

**`Robotics · Edge AI · LLM Systems · Computer Vision`**

[![Portfolio](https://img.shields.io/badge/Portfolio-000?style=for-the-badge&logo=vercel&logoColor=white)](https://jayadeepgowda.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/jay7788)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jayadeepgowda24@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-161B22?style=for-the-badge&logo=github&logoColor=white)](https://github.com/jay7-tech)

</div>

---

## SYSTEM IDENTITY

```python
class JayadeepGowda:
    affiliation  = "IISc Bangalore (Research Intern, CDS Dept.) · BIT Bangalore (8.88/10 CGPA)"
    domain       = ["Edge AI Deployment", "Robotics Control", "LLM Systems", "Computer Vision"]
    constraint   = "Production-grade only — tested on $50 hardware, not cloud clusters"
    seeking      = "Research · AI/ML · Robotics Internships"

    def philosophy(self):
        return "Compress → Quantize → Deploy → Validate → Repeat"
```

---

## EXPERIENCE PIPELINE

```
IISc Bangalore ──────────────────────────────────────────── Mar–Jun 2026
│  Research Intern · Dept. of Computational & Data Sciences
│  ├─ End-to-end ML pipelines on MXene piezoresistive wristband sensor data
│  ├─ Benchmarked 17 models (14 classical ML + CNN + BiLSTM + CNN-LSTM)
│  │   via 5-fold stratified cross-validation · 21 time/freq-domain features
│  └─ Collaborated with PostDocs, PhDs · AGH University Poland (international)

Sirena AI Systems ───────────────────────────────────────── Jan–Feb 2026
│  R&D Intern · Automation & Edge AI
│  ├─ Full-lifecycle: physics sim → multi-DOF embedded hardware deployment
│  ├─ Humanoid · Quadruped · Hexapod — custom IK solvers + 12-state FSM
│  └─ YOLOv8 + Whisper + Phi-2 on ARM · ZeroMQ pub-sub · <50ms latency

Frillory Design House ───────────────────────────────────── Jun–Aug 2025
│  AI Automation Engineer
│  └─ LLM prompt orchestration · agentic pipelines · 50+ assets · −25% overhead
```

---

## DEPLOYED SYSTEMS

### [MEMO — Neural-OS](https://github.com/jay7-tech/memo)
> Multimodal autonomous desktop robot agent running entirely on-device

```
Architecture:
  RPi 5 ──► Vision   [YOLOv8 + FaceNet]  ──┐
        ──► Speech   [Whisper ASR]          ├──► Orchestrator ──► Motor Control
        ──► Language [Phi-2 · 4-bit · RAG]──┘         │
                                                  Persistent Memory
                                                  (FAISS + ChromaDB)

  Throughput:  10–14 tokens/sec on-device
  E2E Latency: 600ms
  Quantization: 2.7B params → 4-bit (GGUF)
  Recognition: 3rd Place · Best Poster Presentation
```

---

### [Cognis](https://github.com/jay7-tech/cognis)
> LLM query optimization via n-gram pattern mining — 100% local, zero cloud

```
Pipeline:
  Query ──► n-gram Pattern Miner ──► Cache Lookup ──► [HIT]  sub-200ms
                                                  └──► [MISS] Llama-3 + FAISS

  Query reduction: 40–60%       Stack: Llama-3 · FAISS · FastAPI
  Retrieval:       <200ms       Mode:  Fully air-gapped
```

---

### [RILA — Searchable Video Memory](https://github.com/jay7-tech/rila)
> AI agent that converts YouTube/Instagram reels into structured, queryable knowledge

```
Ingest:   Video URL ──► Caption Extraction + Whisper ASR fallback
Extract:  Llama 3 + Pydantic ──► Structured entities (location, topic, timestamp)
Index:    PostgreSQL/PostGIS (geospatial) + ChromaDB (semantic vectors)
Query:    Telegram bot interface ──► hybrid geo + semantic retrieval
```

---

### [YOLOmart](https://github.com/jay7-tech/Yolo_mart-main)
> Autonomous vision-guided shopping cart · 2nd of 150+ teams nationally

```
ESP32 ──► YOLOv8 @ 20 FPS · 92% mAP ──► Firebase ──► React Native
         8-hour battery · real-time object detection + full-stack deployment
```

---

## STACK

```
Language    │  Python · C++ · SQL
ML / DL     │  PyTorch · TensorFlow · Scikit-learn · Transformers
            │  CNN · BiLSTM · CNN-LSTM · ONNX · OpenVINO · 4-bit Quantization
LLM Systems │  Llama-3 · Phi-2 · Whisper · RAG · FAISS · ChromaDB
Vision      │  YOLOv8 · FaceNet · OpenCV · Edge inference (ARM / RPi)
Robotics    │  ROS2 · Gazebo · Webots · PyBullet · IK · FSM · Sim-to-Real
Infra       │  FastAPI · Docker · PostgreSQL · PostGIS · ZeroMQ · Git · Linux
```

---

## RECOGNITION

| Event | Result | Year |
|---|---|---|
| GlitchVerse 2k25 Project Expo | 🥈 2nd Place | 2025 |
| MEMO Best Poster Presentation | 🥉 3rd Place | 2026 |
| Anveshana National Engineering Competition | National Finalist | 2025 |
| BIT Bangalore · Robotics & AI | 8.88 / 10 CGPA · Top 10% | 2023– |
| ROBO CELL Club | Joint Secretary | — |

---

## CURRENTLY

```
► IISc research wrapped Jun 2026 — benchmarking report in progress
► Exploring:  Vision-Language-Action (VLA) models · Safe legged locomotion
► Open to:    Research · AI/ML · Robotics internships (2026–2027)
```

---

<div align="center">

<img width="48%" src="https://github-readme-stats.vercel.app/api?username=jay7-tech&show_icons=true&theme=radical&hide_border=true&bg_color=0D1117&title_color=00D9FF&icon_color=00D9FF&text_color=FFFFFF" />
<img width="48%" src="https://streak-stats.demolab.com/?user=jay7-tech&theme=radical&hide_border=true&background=0D1117&ring=00D9FF&fire=00D9FF&currStreakLabel=00D9FF" />

</div>

---

<div align="center">

`edge AI` · `robotics` · `llm systems` · `computer vision` · `research`

[jayadeepgowda24@gmail.com](mailto:jayadeepgowda24@gmail.com) · [linkedin.com/in/jay7788](https://linkedin.com/in/jay7788) · [jayadeepgowda.vercel.app](https://jayadeepgowda.vercel.app)

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,12,20&height=100&section=footer" width="100%"/>
