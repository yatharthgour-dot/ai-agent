# CareerPilot-AI

An AI-powered career guidance platform built with Streamlit and Hugging Face Inference API. The application helps students and professionals plan their careers, assess placement readiness, prepare for interviews, and optimize resumes for Applicant Tracking Systems (ATS).

## Features

### Dashboard

* AI-powered career consultation
* Personalized career guidance
* Interactive question-answer system

### Career Roadmap Generator

* Generate structured career plans
* Skill development roadmap
* Learning progression guidance
* Project recommendations
* Certification suggestions

### Placement Analysis

* Placement readiness assessment
* CGPA-based evaluation
* Skill gap analysis
* Improvement recommendations
* Salary insights

### Interview Preparation

* Generate interview questions
* Technical and behavioral questions
* Expected answers
* Follow-up discussion points

### Resume ATS Analysis

* PDF and TXT resume support
* Resume parsing and text extraction
* ATS score estimation
* Skill matching analysis
* Missing keyword identification
* Resume improvement suggestions

## Tech Stack

* **Frontend:** Streamlit
* **LLM:** Meta Llama 3.1 8B Instruct
* **Inference Provider:** Hugging Face Inference API
* **PDF Processing:** PyPDF
* **Environment Management:** Python Dotenv

## Project Structure

```bash
CareerPilot-AI/
│
├── app.py
├── .env
├── requirements.txt
├── README.md
└── assets/
```

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/CareerPilot-AI.git
cd CareerPilot-AI
```

### 2. Create Virtual Environment

```bash
python -m venv venv
```

Activate the environment:

**Windows**

```bash
venv\Scripts\activate
```

**Linux/Mac**

```bash
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure Environment Variables

Create a `.env` file in the project root:

```env
HF_TOKEN=your_huggingface_api_key
```

## Running the Application

```bash
streamlit run app.py
```

The application will be available at:

```text
http://localhost:8501
```

## Required Dependencies

```txt
streamlit
huggingface_hub
pypdf
python-dotenv
```

## Usage

1. Launch the application.
2. Select a module from the sidebar.
3. Enter your career-related information.
4. Generate AI-powered insights and recommendations.
5. Use the feedback to improve your career strategy and job readiness.

## Screens Included

* Dashboard
* Career Roadmap Generator
* Placement Analysis
* Interview Preparation
* Resume ATS Analyzer

## Future Enhancements

* Job recommendation engine
* Career trend analytics
* LinkedIn profile analysis
* Resume scoring visualization
* Multi-model AI support
* User authentication
* Progress tracking dashboard

## Author

**Yatharth Gour**
