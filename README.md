# 📄 Cover Letter Generator Using Gradio

An AI-powered web app that generates a **professional, personalized cover letter** using your **resume and job description** — all within seconds!

Upload your **PDF or Word resume**, optionally **paste the job description**, and instantly download a tailored **cover letter** in both `.docx` and `.pdf` formats.

---

## 🚀 Features

- 🧠 Powered by **OpenAI GPT-4o**
- 📁 Accepts resume files in **PDF** or **DOCX** format
- 📝 Optional input to **paste job description** for personalized targeting
- ⚡ Instant generation — no form-filling required
- 📥 Downloads the cover letter in both **Word (.docx)** and **PDF**
- 🌐 Built with **Gradio** for clean, lightweight web UI
- 🧰 Works entirely in-browser — no backend server required

---

## 📸 Demo

![demo](demo_screenshot.png)

---

## 🧰 Tech Stack

- Python
- OpenAI API (GPT-4o)
- Gradio
- `pdfplumber` for PDF parsing
- `python-docx` for Word generation
- `fpdf` for PDF export

---

## ⚙️ How It Works

1. Upload your **resume** (`.pdf` or `.docx`)
2. Paste the **job description** (optional but recommended)
3. The app extracts your resume content and uses the job description to generate a tailored cover letter
4. Download the cover letter in `.docx` and `.pdf` formats instantly

---

## 🔧 Installation & Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/cover-letter-generator.git
   cd cover-letter-generator

2. Install dependencies:
   ```bash
   pip install gradio openai python-docx pdfplumber fpdf
   
3. Add your OpenAI API Key in the script:
   ```bash
   client = openai.OpenAI(api_key="sk-...")  # Replace with your key
   
4. Run the app:
   ```bash
   python app.py

---

## 📄Sample Output:

Dear Hiring Manager,

I am writing to express my interest in the Data Analyst role at your company. As a Computer Science student with a strong foundation in Data Science, AWS, and Machine Learning, I have worked on multiple real-world projects that demonstrate both technical ability and problem-solving mindset...

Sincerely,  
Dharmendra kumar

## 📬 Contact

Made with ❤️ Dharamendra
📧 Email: dharmendra21sde@gmail.com


## 🪪 License

This project is licensed under the MIT License.

## 🙌 Acknowledgements

- OpenAI

- Gradio
