# 🎓 Personalized Career Coach - Gen AI Capstone Project
> Final project for the **Google x Kaggle Generative AI Intensive Course 2025**

> Created by **Alin Merchant**

---

## 📌 Overview
Choosing a career is one of the most important - and often most difficult - decisions a student will make. Yet, many students don't have
access to quality career counseling, and generic online quizzes fall short of offering truly personalized guidance.

This project solves that problem using the power of **Generative AI**.

**Personalized Career Coach** is a web-based app that helps students and early professionals:
- Discover meaningful career paths based on their **skills, interests, goals**, or **resume**
- Receive **justified recommendations** (not just labels)
- Explore high-quality **online courses** from *any platform* to upskill and pursue their goals.
- Download a **PDF summary** of their AI-generated career roadmap.

---

## 🧠 Why this Project?
This capstone project demonstrates the practical use of **multi-step prompting**, **document understanding**, **structured output**,
and **real-world task automation**.
From extracting resume content to formatting professional course recommendations, this app is designed to showcase how GENAI can
truly assist people in making life decisions - not just generate text.

---

## ✨ Key Features
| Feature                          | Description |
| --------------------------------|--------------|
| 📝 Resume upload                | Extracts text from PDF/TXT resumes and uses it for recommendation |
| 🎯 Career Matching              | Suggests 2-3 suitable careers and explains why |
| 📚 Course Suggestions           | Pulls relevant courses from any platform (e.g., Coursera, Udemy, LinkedIn, etc) |
| 📥 PDF Export                   | Clean, downloadable summary with clickable course links |

---

## 🧩 Tech Stack
- **Language Model**: OpenAI GPT-3.5 Turbo
- **Frontend/UI**: Gradio
- **Resume Parsing**: PyMuPDF
- **PDF Report**: FPDF
- **Deployement Ready**: Can be launched via Hugging Face Spaces or Streamlit

---

## 🧠 Gen AI Capabilities Demonstrated
- ✅ Few-shot prompting
- ✅ Multi-step agent logic
- ✅ Document understanding (resume text extraction)
- ✅ Structured content generation

---

## 🚀 How to Run Locally
1. Clone this repo:
   ```bash
   git clone https://github.com/MythicBat/Career-Coach-GENAI-Project.git
   cd Career-Coach-GENAI-Project

2. Install dependencies:
   ```bash
   pip install -r requirements.txt

3. Add your OpenAI key:
   ```bash
   set OPENAI_API_KEY="your-openai-key"

4. Run the app:
   ```bash
   python Career-Coach.ipynb

---

## 📄 Example PDF Report
[Download Sample Report](examples/alin_careers_report.pdf)

---

## 📰 Read the Blogpost
Want to learn how this was built step-by-step?

📖 **Read the full blog on Medium -> [LINK HERE](https://medium.com/@alinmerchant5/%EF%B8%8F-from-resume-to-roadmap-building-an-ai-career-coach-076d1a1605b0)**

I cover:
- Why I built the app
- How GPT-3.5 powers career matching
- How resume parsing and PDF exports were implemented

---

## 🙋‍♂️ Author
**Alin Merchant**
- [GitHub](https://github.com/MythicBat)
- [LinkedIn](https://www.linkedin.com/in/alin-merchant-9b2002225)
