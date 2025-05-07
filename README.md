# Toxic Content Detector

This project is a simple web application that detects toxic, offensive, or harmful content in English text. It uses the pre-trained `unitary/toxic-bert` model from Hugging Face and is built with Gradio for the web interface.

## 💡 What It Does

- Detects toxic categories like:
  - Toxic
  - Severe Toxic
  - Obscene
  - Threat
  - Insult
  - Identity Hate
- Returns only labels with high confidence
- Shows "Clean" if no toxic content is detected

---

## 🧠 Model Used

- [`unitary/toxic-bert`](https://huggingface.co/unitary/toxic-bert)

---

## 🚀 Live Demo (Optional)

To be added if deployed on Hugging Face Spaces, Streamlit, etc.

---

## 🛠️ Installation

1. Clone this repository or download the files:

```bash
git clone https://github.com/yourusername/toxic-content-detector.git
cd toxic-content-detector
