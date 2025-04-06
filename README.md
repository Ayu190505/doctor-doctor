# 🩺🧠 Doctor Doctor

**Doctor Doctor** is a smart diagnostic web application built at **HackHarvard 2024** that collects patient data through interactive interfaces and performs multi-modal diagnosis using machine learning and AI. It combines audio analysis, image recognition, and OpenAI-powered language processing to generate accurate and actionable health reports.

---

## 🖥️ Demo

Explore the key interfaces of **Doctor Doctor** below:

### 🔐 Login Page

<p float="left">
  <img width="392" alt="Screenshot 2025-04-06 at 5 43 51 PM" src="https://github.com/user-attachments/assets/e26a978f-6169-4d9e-bf54-5280fbd25bbc" />
</p>

---

### 🧑‍⚕️ Patient Profile

<p float="left">
  <img width="552" alt="Screenshot 2025-03-18 at 7 26 22 AM" src="https://github.com/user-attachments/assets/d5ae4a09-ca0b-424a-ba83-4f403e562073" />
  <img width="495" alt="Screenshot 2025-04-06 at 5 44 15 PM" src="https://github.com/user-attachments/assets/c1434c02-c6e8-4f2d-bdbb-fd47166dbb0a" />
</p>

---

### 🧬 ML Questionnaire (Audio + Visual Input)

<p float="left">
  <img width="261" alt="Screenshot 2025-03-17 at 11 35 47 PM" src="https://github.com/user-attachments/assets/44bd9432-4a54-4438-bbf1-acfed3f00b99" />
  <img width="421" alt="Screenshot 2025-04-06 at 5 46 46 PM" src="https://github.com/user-attachments/assets/7ab523bc-7a44-4ebf-a7c6-a18c07cff5cc" />
</p>

---

### 📝 Diagnostic PDF Report

<p float="left">
  <img width="823" alt="Screenshot 2025-04-06 at 5 45 40 PM" src="https://github.com/user-attachments/assets/b7aa8d9c-1c8f-4a9d-8d25-39bc1487744d" />
</p>

---

## 💡 Inspiration

The inspiration for **Doctor Doctor** was to explore the intersection of AI and healthcare accessibility. With just 36 hours at **HackHarvard**, we aimed to build a platform that could collect medical input from users — such as cough sounds, visual skin symptoms, and subjective descriptions — and synthesize it into meaningful diagnostic reports using machine learning and language models.

---

## 🛠️ Features

- 🔒 **Secure Login:** Access to personal health dashboard.
- 📄 **Dynamic Profile:** View past diagnoses and appointment history.
- 🧠 **ML-Driven Questionnaire:** 
  - Audio analysis of coughs using **Librosa** and **Pydub**
  - Image classification using **Torchvision** for burns, rashes, blisters, etc.
- 🧬 **AI Diagnosis Generator:** Uses **OpenAI API** to synthesize symptoms, questionnaire data, and patient history.
- 📥 **PDF Report Generation:** Exports a summary with insights and recommendations.

---

## 🧱 Tech Stack

- **Frontend:** React.js, CSS
- **Backend:** Flask (Python)
- **Machine Learning:** Torchvision, Librosa, Pydub
- **AI Integration:** OpenAI GPT API
- **Authentication/Storage:** Flask sessions + Local caching with JSON
- **Diagnostic Report:** jsPDF API
- **Version Control:** Git

---

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- Node.js (v16+)
- OpenAI API Key

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/doctor-doctor.git
   cd doctor-doctor
   python app.py
   npm run dev
