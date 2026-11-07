
# 🎀 Apply Wisely

### AI-Powered Job Application Assistant

Apply Wisely is an AI-powered web application that helps job seekers understand how well their CV matches a job advertisement.

Upload your CV, paste a job description and receive an AI-generated analysis with a match score, skills assessment and personalized recommendations.

## ✨ Features

- 📄 CV upload and PDF text extraction
- 🤖 AI-powered CV and job description analysis
- 📊 Overall job compatibility score
- 📈 Category-based skills evaluation
- ✅ Identification of relevant strengths
- 🔍 Skills gap analysis
- 💡 Personalized CV improvement recommendations
- 🇬🇧 English and German language support
- 📥 Downloadable analysis report

## 🛠️ Technologies

| Technology | Purpose |
|---|---|
| Python | Application logic |
| Streamlit | Web application interface |
| Google Gemini API | AI-powered analysis |
| PyPDF | PDF text extraction |
| Pandas | Data handling |
| Plotly | Data visualization |

## 🚀 Run Locally

Clone the repository:

```bash
git clone https://github.com/elamadar/apply-wisely.git
```

Navigate to the project:

```bash
cd apply-wisely
```

Create a virtual environment:

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Create a `.env` file containing:

```env
GEMINI_API_KEY=your_api_key_here
GEMINI_MODEL=your_model_name
```

Run the application:

```bash
streamlit run app.py
```

## 🔐 Privacy and Responsible Use

CV text and job descriptions are sent to Google's Gemini API for analysis.

API keys should be stored securely and must never be committed to GitHub.

Use anonymized CVs when testing with the public application.

The generated match score is an AI-based estimate and should not be interpreted as a prediction of recruitment outcomes.

## 🎯 Project Goal

Apply Wisely was developed as a portfolio project to explore practical AI integration, Python application development, document processing, API communication and data visualization.

**Built with Python, Streamlit and Google Gemini.**
