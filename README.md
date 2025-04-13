# 💬 Dholuo Automatic Speech Recognition (ASR) Project  
*Empowering Low-Resource Language Access with Whisper | NLP + Web App Development*

## 📍 Nairobi, Kenya | Sept 2025 – Ongoing  
---

## 🧠 Overview  
This is an **individual NLP research project** focused on building an **end-to-end Automatic Speech Recognition (ASR) tool** for **Dholuo**, a low-resource language spoken in Kenya. The system is powered by **OpenAI’s Whisper model**, fine-tuned to better understand Dholuo phonetics and vocabulary.

> 🗣️ The project aims to enhance **language accessibility**, **education**, and **digital documentation** for underrepresented African languages.

---

## 🎯 Key Objectives  
- 📥 Collect & preprocess **Dholuo speech data** using Mozilla Common Voice  
- 🧽 Normalize and clean transcription data (tokenization, casing, punctuation)  
- 🔧 Fine-tune **Whisper** via transfer learning for Dholuo-specific ASR  
- 📊 Evaluate model accuracy with **WER** & **CER**  
- 🌐 Deploy a live **Streamlit web app** for transcription  
- 🧪 Provide a **Gradio prototype** for real-time testing

---

## 🛠️ Tech Stack & Tools  
| Task                     | Tools / Frameworks                                          |
|--------------------------|-------------------------------------------------------------|
| Data Collection          | `Mozilla Common Voice`, `Python scripts`                    |
| Preprocessing            | `NLTK`, `NumPy`, `re`, `Whisper-compatible text cleaning`   |
| Model Training           | `Whisper`, `Google Colab`, `PyTorch`, `Transfer Learning`   |
| Prototyping              | `Gradio`, `Streamlit`                                       |
| Evaluation               | `WER`, `CER`, `scikit-learn`, `JiWER`                       |

---

## 📂 Project Structure  
```
dholuo-asr/
│
├── 1. ASR Project: Filtering ASR tsv files/                
├── 2. ASR Project - File Conversion/          
├── 3. ASR Projects - Mapping & Filtering/              
├── 4. ASR Project - Preprocessing/       
├── 5. ASR Project - Training/                    
└── README.md
```

---

## 🔄 Project Phases

### ✅ Phase 1: Data Preparation  
- Sourced Dholuo speech clips from **Mozilla Common Voice**  
- Applied **text normalization**: lowercasing, removing special characters, diacritics  
- Aligned audio-transcript pairs into Whisper format

### 🚧 Phase 2: Model Fine-Tuning *(Ongoing)*  
- Using **Whisper (small/medium)** as base model  
- Applying **transfer learning** to improve recognition of Dholuo phonemes  
- Running on **Google Colab Pro+ GPUs**

### 🔬 Phase 3: Evaluation  
- Metrics:  
  - 🧾 **Word Error Rate (WER)**  
  - 🔠 **Character Error Rate (CER)**  
- Benchmarking model performance on held-out Dholuo test set

### 🌐 Phase 4: Web Deployment  
- ✅ **Gradio prototype** for real-time transcription  
- ⏳ Final **Streamlit app** (in progress)  
  - Upload or record Dholuo audio  
  - Get instant transcription  
  - Simple, mobile-friendly UI

---

## 🌍 Why Dholuo?  
Dholuo is spoken by over **4 million people** in Kenya and parts of Uganda. However, it is **underrepresented in digital tools**. This project seeks to:
- Promote **language preservation**
- Improve **access to technology in native languages**
- Support **education & literacy** in mother tongues

---

## 📸 Demos & Screenshots  
*(Coming Soon)*  
Once the fine-tuned model is deployed, screenshots and demo links will be added here.

---

## 📈 Status  
- ✅ Data collection complete  
- ✅ Preprocessing scripts tested  
- 🚧 Whisper fine-tuning in progress  
- ✅ Gradio prototype ready  
- ⏳ Streamlit deployment in development

---


## 📬 Contact  
📧 Email: [chesia.anyika@gmail.com]  
🌐 [LinkedIn: https://www.linkedin.com/in/chesia-anyika-03a104353/] 

---

## 📝 License  
For educational and research use only.  

---
