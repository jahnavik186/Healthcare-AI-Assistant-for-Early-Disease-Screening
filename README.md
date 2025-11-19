# 🏥 Healthcare Diagnostic Chatbot
### AI-Powered Symptom Checker Using Machine Learning

The **Healthcare Diagnostic Chatbot** is an ML-driven interactive system that predicts potential diseases based on user-reported symptoms. It leverages **Decision Tree classification**, **SVM validation**, and a structured medical knowledge base to provide:

- 🩺 Disease prediction  
- 📊 Symptom severity assessment  
- 📚 Condition descriptions  
- 🛡️ Precaution recommendations  
- 🎤 Optional text-to-speech interaction  

This project is intended for **educational and research purposes**, demonstrating applied machine learning and rule-based reasoning in healthcare.

---

## 🚀 Features

### 🔍 Machine Learning Pipeline
- **Decision Tree Classifier** for primary disease prediction  
- **SVM model** for secondary accuracy validation  
- Automated feature encoding and training from CSV datasets  

### 💬 Symptom Interaction Engine
- Pattern-matching for symptom input  
- Regex-based suggestion of similar symptoms  
- Interactive question flow based on decision-tree traversal  

### 🧠 Severity & Condition Assessment
- Severity scoring using predefined symptom weights  
- Consultation recommendation based on score thresholds  

### 📘 CSV-Driven Medical Knowledge Base
- `symptom_Description.csv` — disease definitions  
- `symptom_precaution.csv` — recommended precautions  
- `symptom_severity.csv` — symptom severity weights  
- `Training.csv` & `Testing.csv` — ML dataset  

### 🔊 Optional Speech Output
- Text-to-speech responses via **pyttsx3**

---

## 📦 Installation

### 1. Clone the Repository
```bash
git clone https://github.com/<your-username>/healthcare-chatbot.git
cd healthcare-chatbot
