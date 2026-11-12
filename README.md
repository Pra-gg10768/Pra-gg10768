<div align="center">

<img src="./assets/hero.svg" width="100%" alt="Pragnyan Satapathy: ML for Cybersecurity, Explainable AI, Computer Vision" />

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-0f2027?style=for-the-badge&logo=vercel&logoColor=white)](https://pragnyan-satapathy.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pragnyan)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:pragnyansatapathy@gmail.com)
[![Publication](https://img.shields.io/badge/Publication-IJSREM%202025-2c5364?style=for-the-badge)](https://doi.org/10.55041/IJSREM40695)

</div>

<img src="./assets/divider.svg" width="100%" alt="" />

<div align="center">
<img src="./assets/terminal.svg" width="100%" alt="Terminal summary of my work" />
</div>

> [!NOTE]
> **Open to winter 2026–27 internships in Kaohsiung**: AI-based threat detection, security analytics and applied ML. Interested in intrusion / APT detection and security for AI systems.

<img src="./assets/divider.svg" width="100%" alt="" />

## 📈 At a glance

<div align="center">

| **98%+** | **0.955** | **1** | **2** | **20** |
|:---:|:---:|:---:|:---:|:---:|
| detection rate<br/>on CICIDS2017 | AUC on<br/>DFD-Original | peer-reviewed<br/>paper (2025) | research<br/>internships | first-year students<br/>mentored |

</div>

## 🛠️ Toolbox

<div align="center">

<img src="https://skillicons.dev/icons?i=python,java,pytorch,tensorflow,sklearn,opencv,pandas,numpy&perline=8" alt="ML skills" />
<br/>
<img src="https://skillicons.dev/icons?i=flask,mysql,mongodb,git,linux,vscode,postman,latex&perline=8" alt="tools" />
<br/>
<img src="https://skillicons.dev/icons?i=arduino,raspberrypi&perline=8" alt="embedded" />

</div>

<sub>Also: SHAP · Grad-CAM · LIME · Hugging Face Transformers · LoRA/QLoRA · RAG · YOLO · imbalanced-learn · SciPy · Mapbox · Deck.gl</sub>

<img src="./assets/divider.svg" width="100%" alt="" />

## 🚀 Featured projects

<table>
<tr>
<td width="50%" valign="top">

### 🔐 [Network Intrusion Detection](https://github.com/Pra-gg10768/ml-network-intrusion-detection)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-EC6B23?style=flat-square)
![SHAP](https://img.shields.io/badge/SHAP-6e40c9?style=flat-square)

Random Forest + XGBoost ensembles on **CICIDS2017**, with SHAP to show which traffic features drive each prediction.

**98%+ detection rate**

</td>
<td width="50%" valign="top">

### 🕵️ [Physio-Aware Deepfake Detection](https://github.com/Pra-gg10768/physio-aware-deepfake-detection)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![rPPG](https://img.shields.io/badge/rPPG-0f2027?style=flat-square)

Multi-ROI rPPG framework that checks whether a face's pulse signal stays consistent over time and frequency.

**93.6% accuracy · 0.955 AUC**

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 👁️ Real-Time Queue Detection
![YOLO](https://img.shields.io/badge/YOLO-111111?style=flat-square)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)

End-to-end YOLO pipeline for queue and crowd analysis under occlusion, scale variation and lighting changes.

**[Published, IJSREM 2025](https://doi.org/10.55041/IJSREM40695)**

</td>
<td width="50%" valign="top">

### 🚗 GPS + OBD-II Trip Visualization
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Mapbox](https://img.shields.io/badge/Mapbox-000000?style=flat-square&logo=mapbox&logoColor=white)
![Deck.gl](https://img.shields.io/badge/Deck.gl-0f2027?style=flat-square)

Telemetry pipeline with timestamp sync, cleaning, geodesic speed estimation, stop detection and 3D route animation.

**Built at STUST (TEEP)**

</td>
</tr>
</table>

<details>
<summary><b>🔎 How the detection pipelines work (click to expand)</b></summary>

<br/>

**Network intrusion detection**

```mermaid
flowchart LR
    A[CICIDS2017<br/>network flows] --> B[Preprocessing &<br/>feature engineering]
    B --> C[Random Forest +<br/>XGBoost ensemble]
    C --> D{Benign or<br/>malicious?}
    D --> E[SHAP: which traffic<br/>features drove it]
    style D fill:#ff5252,color:#fff
```

**Physio-aware deepfake detection**

```mermaid
flowchart LR
    A[Video] --> B[Face regions<br/>of interest]
    B --> C[rPPG pulse signal<br/>per region]
    C --> D[Temporal + spectral<br/>consistency across regions]
    D --> E{Real or<br/>fake?}
    style E fill:#ff5252,color:#fff
```

</details>

<details>
<summary><b>🎭 Also: video-based facial expression & sign language recognition</b></summary>

<br/>

Models temporal facial movement and combines frame-level visual features with spatio-temporal hand and body-motion analysis to recognize expressions and isolated signs.

</details>

<!-- TODO: add repo links for the YOLO, GPS/OBD-II and sign-language projects once public; add precision/recall/F1/FPR for the NIDS project; check the two diagrams match your real pipelines -->

<img src="./assets/divider.svg" width="100%" alt="" />

## 🧭 Research path

```mermaid
timeline
    title From B.Tech to M.S. research
    2021–2025 : B.Tech CSE, Presidency University (CGPA 8.61)
    Jul–Oct 2024 : Research Intern, IDEAS Lab, ISI Kolkata
    Jan 2025 : Published YOLO queue-detection paper
    Jul–Nov 2025 : TEEP Research Intern, STUST Taiwan
    2026–2028 : M.S. CSE, NSYSU Kaohsiung
```

<details>
<summary><b>What I did in each role</b></summary>

<br/>

- **TEEP Research Intern, STUST (Jul–Nov 2025):** modular GPS/OBD-II telemetry pipeline and interactive 3D spatio-temporal visualization on noisy, misaligned sensor data.
- **Research Intern, ISI Kolkata (Jul–Oct 2024):** Python backend logic and structured data pipelines for the Upatto project; formal training in research methodology and analytics.

</details>

## 🏆 Certifications & achievements

- 🛡️ Fortinet Certified Fundamentals in Cybersecurity (NSE 1 & 2) · IBM Python for Data Science · IBM Machine Learning with Python · MATLAB for Data Processing and Visualization
- 🥇 Winner, Smart India Hackathon (Internal) 2023 · Runner-up, SCIMIT Project Expo 2024 · Top 4, InnovateX Idea Expo, IISc Bengaluru
- 🤝 Student Mentor, Build Club: guided 20 first-year students through IoT projects

<img src="./assets/divider.svg" width="100%" alt="" />

## 📊 GitHub activity

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Pra-gg10768&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true" width="49%" alt="stats" />
<img src="https://streak-stats.demolab.com/?user=Pra-gg10768&theme=tokyonight&hide_border=true" width="49%" alt="streak" />

<!-- Snake appears after you add snake.yml (.github/workflows) and run it once -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Pra-gg10768/Pra-gg10768/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Pra-gg10768/Pra-gg10768/output/github-snake.svg" />
  <img alt="contribution snake" src="https://raw.githubusercontent.com/Pra-gg10768/Pra-gg10768/output/github-snake.svg" />
</picture>

</div>

<img src="./assets/divider.svg" width="100%" alt="" />

<div align="center">

### 📫 Let's connect

I'm looking for research and engineering internships in AI-based security and applied ML.

[![Email](https://img.shields.io/badge/pragnyansatapathy%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:pragnyansatapathy@gmail.com)

</div>
