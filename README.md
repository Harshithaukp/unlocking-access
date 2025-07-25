# Voice4Welfare – Hackathon MVP Submission

**Colab Notebook:** [View in Colab](https://colab.research.google.com/drive/1n4T4s7HiUmdA8D-FlWOBe0_fmt-9itIf?usp=sharing )  
**Team Name:** Infinityloopers  
**Category:** AI + Voice Accessibility | Government Scheme Discovery

---
** website **
<img width="1902" height="845" alt="image" src="https://github.com/user-attachments/assets/781da3ee-df20-46da-9bff-f79fa7f5620f" />


---

## 🧠 Problem Statement

Millions of underprivileged or non-literate citizens struggle to access welfare schemes due to language, literacy, and technical barriers. Voice4Welfare aims to bridge that gap by offering a **voice-based welfare discovery platform**, accessible even via basic mobile phones using IVR and AI.

---

## 💡 Solution Overview

**Voice4Welfare** allows users to:
- Speak in their **native language**
- Get **automatic transcription** (via Whisper)
- Understand intent using **NLU (Rasa + LLM)**
- Match to relevant **welfare schemes**
- Hear responses back via **TTS**
- Receive **SMS fallback** if needed

---

##  Features Implemented

- **Voice Input** via Whisper
-  **Multilingual NLU** using Rasa + Llama 3 (via LangChain)
-  Scheme matching pipeline (rule-based + semantic similarity)
-  **Voice Output** using Coqui/Google TTS
-  Flask backend for local testing
- **IVR-compatible** for future phone integration
- SMS fallback system (future-ready)

---


## 🛠️ Tech Stack

| Component        | Technology Used            |
|------------------|----------------------------|
| ASR (Speech-to-Text) | OpenAI Whisper (via API) |
| NLU              | Rasa + Llama 3 (LangChain) |
| Backend          | Python Flask + Colab       |
| TTS (Text-to-Speech) | Coqui / gTTS            |
| Interface        | IVR-ready, Colab demo      |

---

## ✅ Feature Checklist

- [x] Voice-based query input
- [x] Intent recognition (multilingual)
- [x] Welfare scheme response engine
- [x] Text-to-speech voice output
- [x] SMS fallback (optional)
- [x] Flask backend (MVP level)

---

## 📦 How to Run

> This project is prototyped in Colab. You can run the full demo here:  
👉 [Open Colab Notebook](https://colab.research.google.com/drive/1n4T4s7HiUmdA8D-FlWOBe0_fmt-9itIf?usp=sharing)

---

## 🔒 Limitations

- Not yet integrated with a full IVR gateway
- SMS API is mocked/not live
- Some features require GPU (Whisper large models)

---

## 👥 Team Members

- Harshitha u k pawar
- shrinidhi g c n

---

## 📬 Contact

For any questions, please reach out to:  
📧 harshiukp@gmail.com 
📞 +91-9902655840

---

_This project was submitted as part of the Hack-A-Tone MVP Round._

