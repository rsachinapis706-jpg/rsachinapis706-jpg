<div align="center">

# Sachin Rajamanickam

**AI & Data Engineering @ Amrita Vishwa Vidyapeetham** · Coimbatore, India

Building AI systems that hold up under real-world conditions —
physics-informed, safety-governed, and fast enough to run in real time.

[![Google Scholar](https://img.shields.io/badge/Google_Scholar-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white)](https://scholar.google.com/citations?user=VaPYiE8AAAAJ&hl=en)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rsachinapis706@gmail.com)
![Publications](https://img.shields.io/badge/Peer--Reviewed_Publications-4-success?style=for-the-badge)

</div>

---

## About

I work at the boundary between machine learning and physical modelling. Most of my
research starts from the same observation: models that top a benchmark often fail
quietly the moment their inputs degrade, their sensors drift, or their own weights are
corrupted. I build the ones that don't.

That interest runs across four published papers — atmospheric physics for satellite
imagery, self-healing neural architectures, generative models for scarce biosignal data,
and supervisory control for agricultural digital twins.

- 🔬 **Focus:** physics-guided inference · governed learning · digital twins · signal intelligence · robotics
- 🎯 **Currently:** studying how learned control policies transfer when the underlying simulator changes
- 🎓 **Next:** Master's in Artificial Intelligence, research-oriented
- 📫 **Reach me:** [rsachinapis706@gmail.com](mailto:rsachinapis706@gmail.com)

---

## Publications

> Four peer-reviewed papers · first author on three · two in Q1 journals

### Thermo-CR: Real-Time Physics-Based Cloud Shadow Removal
`Scientific Reports` · 2026 · **Q1** · *first author*

Cloud removal driven by atmospheric physics rather than generative inpainting. Fuses live
NASA MODIS/VIIRS acquisitions, Open-Meteo weather fields, and GIS temporal priors, models
the atmosphere as a participating medium via the radiative transfer equation, and estimates
spatially varying transmission maps from humidity and temperature — preserving true
geographic structure instead of hallucinating texture.

### Bio-Evolutionary Neural Networks with Deterministic Foresight and Adaptive Self-Healing
`Neural Computing and Applications` · Vol. 38, art. 553 · 2026 · **Q1** · *first author*

The **AI Brain Engine**: modular neural cells encoded with GeneDNA/GeneRNA, a
reinforcement-guided failure function that adapts learning rate by error sensitivity, and a
Laplace-Demon-inspired foresight module. Tested by deliberately corrupting the network —
weight noise, partial parameter reset, pruning — across three image benchmarks, plus the
CMAPSS turbofan dataset for predictive maintenance. **+9.3% resilience score** after
corruption, with reduced loss volatility and faster convergence than CNN/ResNet baselines.

### Closed-Form Markovian Prototype Learning for One-Shot Classification
`IEEE CONIT` · Belagavi, India · 2026 · *first author* · [doi:10.1109/CONIT69683.2026.11621872](https://doi.org/10.1109/CONIT69683.2026.11621872)

One-shot learning **without gradient descent**. Combines closed-form pseudoinverse learning
(weights computed directly from samples), Hebbian association for instance-level binding,
and Markovian graph propagation for context. Each sample becomes a *pseudonode* with its own
memory state; relationships are directed edges weighted by transition probabilities.

### Hybrid Passive Ankle–Foot Orthosis with Energy Harvesting
`IEEE ICEARS` · 2026 · *co-author*

Passive orthosis delivering elastic torque assistance with integrated electromagnetic energy
harvesting for self-powered sensing. **+3° dorsiflexion**, **12–15% lower plantar pressure**,
and **25–32 mW** generated during walking with no active actuation.

---

## Research Projects

**AgriOS — Governance-Driven Digital Twin for Plant Stress Management**
An OS-inspired digital twin where learning models are advisory only, sitting beneath a
supervisory control layer that can override them. Multi-factor stress estimation,
short-horizon forecasting, and confidence-aware overrides.
→ *Eliminated critical stress exposure, cut peak stress by up to 28%, end-to-end latency under 13 ms.*

**Spectrally Constrained AC-TimeGAN — Dream EEG Analysis**
Auxiliary-classifier TimeGAN for EEG synthesis under severe data scarcity, with PSD and
band-power losses enforcing frequency-domain fidelity. Realism validated spectrally, not
by eye.
→ *Dream-state classification accuracy 77% → 90% at 100% recall.*

**Early Prediction & Source Localisation in Diffusion Cascades**
Optimisation-based framework for predicting cascades under partial observation, using sparse
spectral representations to localise the source.
→ *Effective at observation ratio τ = 0.2; source recovered in the top-10/20 across domains.*

---

## Engineering Projects

| Project | Stack | What it does |
|---|---|---|
| **Hospital Bed Transporter Robot** | ROS2, Gazebo | End-to-end ROS2 workspace — URDF/XACRO modelling, Gazebo simulation, publisher–subscriber motion control |
| **Wi-Fi Signal Strength Mapping** | SDR, Python | Captures live RF samples on SDR hardware, extracts RSSI from raw IQ data, renders spatial coverage/interference heatmaps |
| **Agricultural Virtual OS** | Python | Fuses weather, soil, and crop datasets under rule-based monitoring and decision logic |

---

## Tech

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=flat-square&logo=mathworks&logoColor=white)

**ML & Scientific**
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)

**Robotics & Systems**
![ROS2](https://img.shields.io/badge/ROS2-22314E?style=flat-square&logo=ros&logoColor=white)
![Gazebo](https://img.shields.io/badge/Gazebo-FF6600?style=flat-square&logo=gazebo&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

**Domain**
`Radiative transfer modelling` · `EEG / PSD analysis` · `Signal processing` · `IoT edge deployment` · `Digital twins`

---

<div align="center">

<img height="150" src="https://github-readme-stats.vercel.app/api?username=rsachinapis706-jpg&show_icons=true&hide_border=true&theme=default" alt="GitHub stats" />
<img height="150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=rsachinapis706-jpg&layout=compact&hide_border=true&theme=default" alt="Top languages" />

</div>
