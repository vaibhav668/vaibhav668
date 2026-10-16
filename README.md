<div align="center">

<img src="./assets/header.svg" width="100%" alt="Vaibhav Pokhriyal - AI Engineer, Biosignal Systems, Agentic AI" />

<a href="https://github.com/vaibhav668">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=19&duration=2800&pause=900&color=E23636&center=true&vCenter=true&width=820&lines=Former+AI+Engineer+Intern+%40+Mind+Masters+AI+Solutions;Former+Research+Intern+%40+IIT+Delhi+Neuro+Computing+Lab;Voice+Agents+%7C+LangGraph+%7C+FastAPI+%7C+PostgreSQL;EEG+%2F+EMG+%2F+EOG+Signal+Processing+for+Healthcare;Now%3A+DSA%2C+CS+Fundamentals+and+SQL+in+depth" alt="Typing intro" />
</a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-B11226?style=for-the-badge&logo=linkedin&logoColor=FFFFFF)](https://www.linkedin.com/in/vaibhav-pokhriyal-a8b08023a/)
[![Email](https://img.shields.io/badge/Email-B11226?style=for-the-badge&logo=gmail&logoColor=FFFFFF)](mailto:vpokhriyal35@gmail.com)
[![Repositories](https://img.shields.io/badge/Repositories-B11226?style=for-the-badge&logo=github&logoColor=FFFFFF)](https://github.com/vaibhav668?tab=repositories)
![Profile Views](https://komarev.com/ghpvc/?username=vaibhav668&style=for-the-badge&color=2B59C3&label=VISITORS)

</div>

<img src="./assets/divider.svg" width="100%" />

## <samp>CH.00 / WHOAMI</samp>

```python
class Vaibhav:
    name       = "Vaibhav Pokhriyal"
    education  = "B.Tech CSE (AI & ML), GBPIET Pauri Garhwal | 2024 - 2028"
    semester   = 5

    experience = {
        "Mind Masters AI Solutions":      "AI Engineer Intern  | Jun - Sep 2026 | Voice AI, agentic systems",
        "IIT Delhi, Neuro Computing Lab": "Research Intern     | Feb - May 2026 | GNNs for EEG seizure detection",
    }

    building   = "Wearable EOG/EMG nurse-call system for patients who are conscious but cannot speak"
    writing    = "Paper: Hybrid Spatiotemporal GNN for EEG-based seizure detection"
    sharpening = ["DSA (300 quality problems)", "DBMS", "OS", "Computer Networks", "SQL / PostgreSQL"]

    open_to    = ["Research collaborations", "Summer 2027 internships"]
```

<img src="./assets/divider.svg" width="100%" />

## <samp>CH.01 / EXPERIENCE</samp>

<table>
<tr>
<td width="50%" valign="top">

<samp>JUN 2026 - SEP 2026 &nbsp;|&nbsp; REMOTE &nbsp;|&nbsp; COMPLETED</samp>

### AI Engineer Intern
**Mind Masters AI Solutions Pvt. Ltd.**

- Built a multilingual voice customer-support agent end to end: telephony, STT / TTS / VAD, knowledge base, booking lookups and authorized tool calling
- Designed agent workflows in LangGraph with MCP tool integration and conversation state management
- FastAPI + PostgreSQL + WebSockets backend for live transcripts, call states, resolution tracking and DTMF feedback, synced with the CRM
- Built an outbound AI cold-calling agent; benchmarked leading STT and TTS models to choose the stack and shipped a demo on the company website
- Built support and enquiry chatbots and integrated voice + chat into the company site and booking platform (auth, CRM, existing backend)

</td>
<td width="50%" valign="top">

<samp>FEB 2026 - MAY 2026 &nbsp;|&nbsp; HYBRID &nbsp;|&nbsp; COMPLETED</samp>

### Research Intern
**Neuro Computing Lab, IIT Delhi** under Prof. Tapan Kumar Gandhi

- Hybrid GAT + BiLSTM framework for epileptic seizure detection on CHB-MIT, in PyTorch and PyTorch Geometric
- EEG pipeline: preprocessing, Pearson-correlation graph construction, feature engineering, temporal sequence modeling
- Focal loss and patient-wise evaluation to handle roughly 1:40 seizure-to-normal imbalance
- Compared against CNN scalogram classification with AlexNet

<samp>ACC 0.84 &nbsp;|&nbsp; MACRO-F1 0.82 &nbsp;|&nbsp; SEIZURE RECALL 0.78 &nbsp;|&nbsp; ROC-AUC 0.914</samp>

Paper in preparation: *Hybrid Spatiotemporal Graph Neural Network Framework for EEG-Based Epileptic Seizure Detection*

</td>
</tr>
</table>

<img src="./assets/divider.svg" width="100%" />

## <samp>CH.02 / BUILDS</samp>

<table>
<tr>
<td>

<samp>STATUS: IN DEVELOPMENT &nbsp;|&nbsp; HACKATHON BUILD</samp>

### Assistive Biosignal Band
A wearable nurse-call system for ICU and paralyzed patients who are conscious but cannot speak.

- Light bands on both wrists (EMG) and one on the forehead (EOG), built on NPG Lite and streaming wirelessly
- Custom command patterns per patient, for example 3 blinks + 2 squeezes calls the nurse, with others for pain, water and more
- Central ward dashboard where on-duty staff see live requests for every patient, with many staff sessions running at once
- Next phase: a multi-channel wrist EMG dataset, labelled per finger, for finger-level gesture classification

`NPG Lite` `EOG` `EMG` `Python` `FastAPI` `WebSockets` `PostgreSQL`

</td>
</tr>
</table>

| Project | What it does | Stack | Code |
|---|---|---|---|
| **EEG Seizure Detection** | Graph-based spatiotemporal model for seizure detection on CHB-MIT | PyTorch Geometric, GAT, BiLSTM, MNE | [![code](https://img.shields.io/badge/VIEW-2B59C3?style=flat-square&logo=github&logoColor=FFFFFF)](https://github.com/vaibhav668/Hybrid-Spatiotemporal-Graph-Neural-Network-Framework-for-EEG-Based-Epileptic-Seizure-Detection) |
| **IntelliGuard AI** | Real-time accident, fight and fire/smoke detection with live alerts, tracking and speed estimation | YOLOv8, ResNet18, OpenCV, FastAPI, Streamlit, Docker | [![code](https://img.shields.io/badge/VIEW-2B59C3?style=flat-square&logo=github&logoColor=FFFFFF)](https://github.com/vaibhav668/INTELLIGUARD-AI) |
| **YouTube AI Assistant** | Chrome extension that answers questions about any video using its transcript (RAG) | LangChain, FAISS, Qwen2.5-7B, MiniLM, FastAPI | [![code](https://img.shields.io/badge/VIEW-2B59C3?style=flat-square&logo=github&logoColor=FFFFFF)](https://github.com/vaibhav668/YT_AI_ASSISTANT_EXTENSION) |
| **BERT Resume Role Classifier** | Classifies resume PDFs into ~25 job roles with per-role error analysis | BERT, PyTorch, Hugging Face, scikit-learn | [![code](https://img.shields.io/badge/VIEW-2B59C3?style=flat-square&logo=github&logoColor=FFFFFF)](https://github.com/vaibhav668/bert-resume-role-classifier) |
| **Hands-free Subway Surfers** | Play the game with body movement through pose landmarks and debounced key mapping | MediaPipe Pose, OpenCV, pynput | [![code](https://img.shields.io/badge/VIEW-2B59C3?style=flat-square&logo=github&logoColor=FFFFFF)](https://github.com/vaibhav668/Subway-Surfer-Handless-Version) |
| **Air Sketch** | Draw in the air with a pinch gesture, no mouse or keyboard | MediaPipe Hands, OpenCV, NumPy | [![code](https://img.shields.io/badge/VIEW-2B59C3?style=flat-square&logo=github&logoColor=FFFFFF)](https://github.com/vaibhav668/SketchWithOpencvCv) |

<img src="./assets/divider.svg" width="100%" />

## <samp>CH.03 / CURRENT FOCUS</samp>

<img src="./assets/status.svg" width="100%" alt="Current focus: DSA, LangGraph, research paper, biosignal band, SQL, CS fundamentals" />

<img src="./assets/divider.svg" width="100%" />

## <samp>CH.04 / TOOLKIT</samp>

**Languages**<br/>
![Python](https://img.shields.io/badge/Python-B11226?style=for-the-badge&logo=python&logoColor=FFFFFF)
![C++](https://img.shields.io/badge/C%2B%2B-B11226?style=for-the-badge&logo=cplusplus&logoColor=FFFFFF)
![JavaScript](https://img.shields.io/badge/JavaScript-B11226?style=for-the-badge&logo=javascript&logoColor=FFFFFF)
![SQL](https://img.shields.io/badge/SQL-B11226?style=for-the-badge&logo=postgresql&logoColor=FFFFFF)
![HTML](https://img.shields.io/badge/HTML-B11226?style=for-the-badge&logo=html5&logoColor=FFFFFF)
![CSS](https://img.shields.io/badge/CSS-B11226?style=for-the-badge&logo=css&logoColor=FFFFFF)

**ML / DL**<br/>
![PyTorch](https://img.shields.io/badge/PyTorch-B11226?style=for-the-badge&logo=pytorch&logoColor=FFFFFF)
![PyTorch Geometric](https://img.shields.io/badge/PyTorch_Geometric-B11226?style=for-the-badge&logo=pyg&logoColor=FFFFFF)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-B11226?style=for-the-badge&logo=huggingface&logoColor=FFFFFF)
![scikit-learn](https://img.shields.io/badge/scikit--learn-B11226?style=for-the-badge&logo=scikitlearn&logoColor=FFFFFF)
![NumPy](https://img.shields.io/badge/NumPy-B11226?style=for-the-badge&logo=numpy&logoColor=FFFFFF)
![Pandas](https://img.shields.io/badge/Pandas-B11226?style=for-the-badge&logo=pandas&logoColor=FFFFFF)

**Agentic AI and Voice**<br/>
![LangChain](https://img.shields.io/badge/LangChain-B11226?style=for-the-badge&logo=langchain&logoColor=FFFFFF)
![LangGraph](https://img.shields.io/badge/LangGraph-B11226?style=for-the-badge&logo=langgraph&logoColor=FFFFFF)
![MCP](https://img.shields.io/badge/MCP-B11226?style=for-the-badge&logo=modelcontextprotocol&logoColor=FFFFFF)
![RAG](https://img.shields.io/badge/RAG-B11226?style=for-the-badge)
![FAISS](https://img.shields.io/badge/FAISS-B11226?style=for-the-badge)
![ChromaDB](https://img.shields.io/badge/ChromaDB-B11226?style=for-the-badge)
![STT / TTS](https://img.shields.io/badge/STT_%2F_TTS-B11226?style=for-the-badge)
![Telephony](https://img.shields.io/badge/Telephony_%2F_IVR-B11226?style=for-the-badge)

**Computer Vision and Signals**<br/>
![OpenCV](https://img.shields.io/badge/OpenCV-B11226?style=for-the-badge&logo=opencv&logoColor=FFFFFF)
![YOLOv8](https://img.shields.io/badge/YOLOv8-B11226?style=for-the-badge)
![MediaPipe](https://img.shields.io/badge/MediaPipe-B11226?style=for-the-badge&logo=mediapipe&logoColor=FFFFFF)
![MNE](https://img.shields.io/badge/MNE-B11226?style=for-the-badge)
![EEG EMG EOG](https://img.shields.io/badge/EEG_%2F_EMG_%2F_EOG-B11226?style=for-the-badge)

**Backend and Deployment**<br/>
![FastAPI](https://img.shields.io/badge/FastAPI-B11226?style=for-the-badge&logo=fastapi&logoColor=FFFFFF)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-B11226?style=for-the-badge&logo=postgresql&logoColor=FFFFFF)
![WebSockets](https://img.shields.io/badge/WebSockets-B11226?style=for-the-badge)
![Django](https://img.shields.io/badge/Django-B11226?style=for-the-badge&logo=django&logoColor=FFFFFF)
![Docker](https://img.shields.io/badge/Docker-B11226?style=for-the-badge&logo=docker&logoColor=FFFFFF)
![Streamlit](https://img.shields.io/badge/Streamlit-B11226?style=for-the-badge&logo=streamlit&logoColor=FFFFFF)
![Render](https://img.shields.io/badge/Render-B11226?style=for-the-badge&logo=render&logoColor=FFFFFF)
![Git](https://img.shields.io/badge/Git-B11226?style=for-the-badge&logo=git&logoColor=FFFFFF)

**Embedded and Robotics**<br/>
![ESP32](https://img.shields.io/badge/ESP32-B11226?style=for-the-badge&logo=espressif&logoColor=FFFFFF)
![Arduino](https://img.shields.io/badge/Arduino-B11226?style=for-the-badge&logo=arduino&logoColor=FFFFFF)
![NPG Lite](https://img.shields.io/badge/NPG_Lite-B11226?style=for-the-badge)

<img src="./assets/divider.svg" width="100%" />

## <samp>CH.05 / ACHIEVEMENTS AND LEADERSHIP</samp>

| | |
|---|---|
| **2nd Runner-Up, Nano Navigator** <br/><samp>COGNIZANCE 2026, IIT ROORKEE</samp> | Autonomous micromouse: ESP32, flood-fill maze solving, VL53L0X time-of-flight sensors, TB6612FNG motor driver |
| **2nd Place, BlindBot Battle** <br/><samp>TRYST 2025, IIT DELHI</samp> | Autonomous soccer robot with sensor-based navigation |
| **Web Master** <br/><samp>IEEE STUDENT BRANCH, GBPIET</samp> | Manage the branch website and technical content |
| **Google Gemini Student Ambassador** | AI education workshops and community outreach |
| **Technical Mentor** <br/><samp>PRASTHANAM ROBOTICS CLUB, GBPIET</samp> | Workshops on computer vision, hardware control, home automation, Git, Tinkercad and drones; mentored junior teams for Cognizance |

<img src="./assets/divider.svg" width="100%" />

## <samp>CH.06 / TELEMETRY</samp>

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=vaibhav668&show_icons=true&hide_border=true&bg_color=0B1230&title_color=E23636&icon_color=5EC8FF&text_color=E8E8F0&ring_color=E23636&rank_icon=github&custom_title=Stats" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=vaibhav668&layout=compact&hide_border=true&bg_color=0B1230&title_color=E23636&text_color=E8E8F0&langs_count=6&custom_title=Languages" />

<img width="80%" src="https://streak-stats.demolab.com?user=vaibhav668&hide_border=true&background=0B1230&ring=E23636&fire=E23636&currStreakNum=FFFFFF&sideNums=FFFFFF&currStreakLabel=5EC8FF&sideLabels=5EC8FF&dates=A8B0D0&stroke=2B59C3" />

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=vaibhav668&bg_color=0B1230&color=E8E8F0&line=E23636&point=5EC8FF&area=true&area_color=2B59C3&hide_border=true&custom_title=Contribution%20Telemetry" />

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/vaibhav668/vaibhav668/output/github-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/vaibhav668/vaibhav668/output/github-snake.svg">
  <img alt="contribution snake" src="https://raw.githubusercontent.com/vaibhav668/vaibhav668/output/github-snake.svg">
</picture>

</div>

<img src="./assets/divider.svg" width="100%" />

## <samp>CH.07 / COMMS</samp>

<div align="center">

Not taking an internship this semester. Open to research collaborations and summer 2027 internships in AI/ML, voice and agentic systems, and healthcare signal processing.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-B11226?style=for-the-badge&logo=linkedin&logoColor=FFFFFF&labelColor=0B1230)](https://www.linkedin.com/in/vaibhav-pokhriyal-a8b08023a/)
[![Email](https://img.shields.io/badge/Email-vpokhriyal35%40gmail.com-B11226?style=for-the-badge&logo=gmail&logoColor=FFFFFF&labelColor=0B1230)](mailto:vpokhriyal35@gmail.com)

<br/>

<img src="./assets/footer.svg" width="100%" alt="From signal to insight. From model to deployment. From idea to impact." />

</div>
