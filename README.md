# 🛡️ SecureAI Guardrail & LLM Defense Lab

An enterprise-grade, full-stack AI security framework and interactive web dashboard built to protect Large Language Models (LLMs) and neural networks against modern threat vectors. This application bridges high-performance backend routing with an intuitive, real-time security interface.

---

## 🚀 Key Features

* **LLM Prompt Injection & Jailbreak Defense:** Real-time semantic and regex-based multi-layer validation engine designed to intercept system-prompt overrides, malicious overrides, and data exfiltration payloads before they reach the core LLM pipeline.
* **Adversarial Machine Learning Lab:** Evaluates deep learning robustness (using PyTorch/ResNet50) under Fast Gradient Sign Method (FGSM) perturbation attacks, visualizing confidence degradation and classification shifts dynamically.
* **FastAPI Microservice Simulator:** Interactive API testing environment modeling programmatic JSON requests, route health tracking, token sanitization metrics, and sub-20ms response latencies.
* **Interactive Threat Telemetry:** Live security metrics tracking total scanned inputs, blocked adversarial vectors, system health, and threat confidence scores.

---

## 🛠️ Tech Stack

* **Backend & API:** Python, FastAPI, Pydantic, Uvicorn
* **Machine Learning / AI:** PyTorch, Torchvision, Scikit-Learn
* **Frontend & Dashboard:** Streamlit (Custom responsive layout with dark-mode styling)
* **Utilities:** Pandas, Matplotlib, Requests, Loguru

---

## 📂 Project Structure

```text
secure-ai-guardrail-lab/
│
├── app.py                  # Main Streamlit dashboard interface & simulation logic
├── requirements.txt        # Project dependencies
├── models/                 # AI model weights and security rule definitions
├── utils/                  # Regex scanners, text sanitizers, and helper functions
└── README.md               # Project documentation
