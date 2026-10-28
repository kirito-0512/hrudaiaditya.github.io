# Hrudai Aditya Dharmala

[![Portfolio](https://img.shields.io/badge/Portfolio-hrudaiaditya.github.io-00ff88?style=flat&logo=googlechrome&logoColor=black)](https://hrudaiaditya.github.io)
[![DOI: 10.5281/zenodo.23636512](https://zenodo.org/badge/DOI/10.5281/zenodo.23636512.svg)](https://doi.org/10.5281/zenodo.23636512)
[![DOI: 10.1007/978-981-96-7517-3_33](https://img.shields.io/badge/Springer%20LNNS-10.1007%2F978--981--96--7517--3__33-blue)](https://doi.org/10.1007/978-981-96-7517-3_33)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-hrudaia0512-0077b5?logo=linkedin&logoColor=white)](https://linkedin.com/in/hrudaia0512)
[![GitHub](https://img.shields.io/badge/GitHub-kirito--0512-181717?logo=github&logoColor=white)](https://github.com/kirito-0512)

> **AI Engineer & Applied Researcher** specializing in agentic workflows, deterministic LLM verification, and high-performance inference platforms. Forward Deployed AI Engineer at Infosys.

---

## 🔬 Featured Publications & Research

### 1. COVE: A Task-Adaptive, Code-Based Ensemble for Proactive Verification of LLM Outputs
* **Authors:** Anjaney Shrivastava (Infosys), Hrudai Aditya Dharmala (Infosys)
* **Venue / Repository:** Zenodo (Open Access)
* **Publication Date:** October 25, 2026
* **DOI:** [`10.5281/zenodo.23636512`](https://doi.org/10.5281/zenodo.23636512)
* **Zenodo Record:** [zenodo.org/records/23636512](https://zenodo.org/records/23636512)
* **License:** [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)

#### Overview & Abstract
Large Language Models (LLMs) deployed in enterprise and mission-critical workflows often face challenges with structural reliability, schema adherence, and subtle hallucinated content. **COVE** introduces a task-adaptive, code-based ensemble designed to proactively enhance prompts and verify model generations through deterministic post-processing.

```
       ┌────────────────────────────────────────────────────────┐
       │             COVE Verification Ensemble                 │
       ├─────────────────────────┬──────────────────────────────┤
       │   Proactive Phase       │       Evaluation Phase       │
       ├─────────────────────────┼──────────────────────────────┤
       │ • Predictive Output     │ • Semantic Output            │
       │   Correction (POC)      │   Fingerprinting (SOF)       │
       │ • Error Pattern         │ • Cross-Metric Anomaly       │
       │   Memory (EPM)          │   Detection (CMAD)           │
       │ • Output Structure      │ • Task-Adaptive              │
       │   Prediction (OSP)      │   Verification Metrics       │
       └─────────────────────────┴──────────────────────────────┘
```

#### Core Components
1. **Predictive Output Correction (POC):** Dynamically injects targeted guidance into prompts based on domain-specific failure distributions before inference.
2. **Error Pattern Memory (EPM):** Maintains a fast-retrieval cache of historical schema failures and recurring structural anomalies across evaluation rounds.
3. **Semantic Output Fingerprinting (SOF):** Extracts invariant structural and semantic hashes to verify output consistency deterministically without secondary LLM judge latency.
4. **Cross-Metric Anomaly Detection (CMAD):** Ensembles orthogonal verification signals to detect out-of-distribution or hallucinated responses.
5. **Output Structure Prediction (OSP):** Enforces target schema and typing constraints on output payloads.
6. **Task-Adaptive Verification Metrics:** Evaluates task-dependent heuristics calibrated to specific textual or multimodal generation targets.

#### Key Empirical Results
| Metric / Benchmark | Baseline | With COVE | Improvement |
| :--- | :---: | :---: | :---: |
| **Text Accuracy** (11 datasets, 1,020 samples) | 45.2% | **82.1%** | **+36.9% absolute (+81.6% rel)** |
| **Multimodal / Vision Accuracy** (4 datasets, 200 samples) | — | — | **+69.5% relative boost** |
| **Verification Overhead** (Python runtime) | — | **0.26 ms** | Ultra-low deterministic latency |
| **Token Savings on Regeneration Retries** | — | **48% – 96%** | Drastic retry cost curtailment |

#### BibTeX Citation
```bibtex
@article{shrivastava_dharmala_2026_cove,
  author    = {Shrivastava, Anjaney and Dharmala, Hrudai Aditya},
  title     = {COVE: A Task-Adaptive, Code-Based Ensemble for Proactive Verification of LLM Outputs},
  journal   = {Zenodo},
  year      = {2026},
  month     = {10},
  doi       = {10.5281/zenodo.23636512},
  url       = {https://zenodo.org/records/23636512}
}
```

---

### 2. Contextual Visual Question Answering on Remote Sensing Images
* **Authors:** Hrudai Aditya Dharmala et al.
* **Venue:** Springer Lecture Notes in Networks and Systems (LNNS, Vol. 1465, pp. 387–398)
* **Conference:** SmartCom 2025
* **DOI:** [`10.1007/978-981-96-7517-3_33`](https://link.springer.com/chapter/10.1007/978-981-96-7517-3_33)
* **Highlights:**
  * Trained a specialized U-NET architecture on RSVQA benchmarks, outperforming conventional baselines across Hamming distance and F1 score.
  * Enhanced "Presence"-type query precision by **14%** by coupling the vision model as an expert module into an open-source multimodal reasoning system.

---

## 🚀 Key Engineering & Open Source Projects

* **[Agentic OS Assembler](https://hrudaiaditya.github.io/#project):** A 9-service containerized Agent OS platform featuring command-line skill execution, hierarchical episode retrieval, semantic memory paging, and OpenTelemetry / Arize Phoenix evaluation tracing. Recognized at Infosys OSPO CodeCon 2025.
* **Topaz Fabric & Enterprise MCP Registry:** Developed foundational multi-agent orchestration infrastructure and reusable agent skills, driving a **45% increase in MCP enablement** across enterprise deployments.
* **Windows ML & ONNX Runtime GenAI:** Showcased at Microsoft Build; designed on-device invoice extraction using fine-tuned **Phi-4 Mini** quantized via Olive AWQ targeting Snapdragon Hexagon NPUs.
* **LLM Research Hub:** Curated and analyzed dozens of AI/ML preprints with distilled takeaways and automated categorization across Agents, RL, and Model Efficiency.

---

## 🏆 Honors & Recognition

* **Infosys Awards for Excellence 2025-26 (Bronze):** Platforms or Software-Based Solutions or Accelerators, awarded for *Infosys Agentic Foundry* by CEO & MD Salil S. Parekh.
* **Infosys Exuberance Awards 2025:** AI Impact and Automation Excellence Award, presented by Hyderabad STP DC Head.
* **OSPO CodeCon Star 2025:** Won the code contribution category at Infosys CodeCon, recognized by CTO Mohammed Rafee Tarafdar and Head of OSPO Prabhat Kumar.
* **Amazon ML Summer School Apprentice:** Selected apprentice, mentored by Amazon Scientists; graduated with distinction.
* **Google DSC Lead:** 1 of 400 leads nationwide; built a developer community of 500+ peers.
* **IEEE Student Branch Chair:** GRSS & CIS chapters; conducted 3+ national-level technical workshops.
* **Vidyarthi Vigyan Manthan (VVM) National Finalist:** Selected for the National Camp at IIT Delhi (organized by VIBHA, Vigyan Prasar & NCERT).

---

## 📜 Key Certifications

* **Claude Certified Architect – Professional & Foundation** (Anthropic, 2026)
* **Azure AI Engineer Associate** (Microsoft, 2025)
* **Generative AI with LLMs** (DeepLearning.AI, 2024)
* **NVIDIA-Certified Associate: Accelerated Data Science** (NVIDIA, 2025)
* **NPTEL Discipline Star – Gen AI** (SWAYAM / MHRD, 2023)

---

## 🌐 Connect & Links

* 💻 **Website & Interactive Portfolio:** [https://hrudaiaditya.github.io](https://hrudaiaditya.github.io)
* 💼 **LinkedIn:** [linkedin.com/in/hrudaia0512](https://www.linkedin.com/in/hrudaia0512)
* 🐙 **GitHub:** [github.com/kirito-0512](https://github.com/kirito-0512)
* 📄 **Publication (Zenodo):** [doi.org/10.5281/zenodo.23636512](https://doi.org/10.5281/zenodo.23636512)
* 📄 **Publication (Springer):** [doi.org/10.1007/978-981-96-7517-3_33](https://doi.org/10.1007/978-981-96-7517-3_33)
* 📧 **Email:** [adityadharmala6@gmail.com](mailto:adityadharmala6@gmail.com)
