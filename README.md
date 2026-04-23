# Whisper Bengali ASR Fine-Tuning with LoRA

This repository contains Jupyter notebooks and code for fine‑tuning [OpenAI Whisper](https://huggingface.co/openai/whisper-small) on Bengali (`bn`) speech recognition tasks.  
We leverage Hugging Face datasets, transformers, and LoRA (Low‑Rank Adaptation) to efficiently adapt Whisper for Bengali Automatic Speech Recognition (ASR).

---

## 📂 Repository Structure

- `notebooks/` → Jupyter notebooks for training, evaluation, and experimentation  
- `data/` → Optional folder for local audio/text datasets  
- `outputs/` → Model checkpoints, logs, and evaluation results  
- `README.md` → Documentation  

---

## 🚀 Getting Started

### Prerequisites
- Python 3.9+  
- CUDA‑enabled GPU (recommended for training)  
- Jupyter Notebook or JupyterLab  

### Installation
Clone the repository and install dependencies:

```bash
git clone https://github.com/ashik360/Bengali_ASR_FT.git
cd whisper-bengali-asr
pip install -r requirements.txt
