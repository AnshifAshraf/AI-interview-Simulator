
# AI Interview Simulator (Resume-Based)

## What is this project about?
This project simulates a realistic technical interview based on your uploaded resume. It extracts your skills, projects, and experience, then generates and presents interview questions tailored to your actual background. The goal is to provide a real interview experience, not just a chatbot.

## How to fork this project
1. Click the **Fork** button at the top right of this repository on GitHub.
2. Choose your GitHub account as the destination.
3. After forking, clone your forked repo to your local machine:
   ```bash
   git clone https://github.com/YOUR-USERNAME/AI-Interview-Simulator.git
   ```
4. Install dependencies and run as described below.

## Features
- Upload your resume (PDF or TXT)
- Extracts your skills, projects, and experience
- Generates realistic, resume-based technical, project, and HR questions
- Presents questions one by one, like a real interview
- Lets you type answers and receive brief feedback

## Tech Stack
- Python
- Streamlit
- PyPDF2 (for PDF parsing)

## How to Run
1. Install dependencies:
   ```bash
   pip install streamlit PyPDF2
   ```
2. Start the app:
   ```bash
   streamlit run app.py
   ```

## File Structure
- app.py — Streamlit UI
- resume_parser.py — Resume parsing logic
- interview_engine.py — Interview question engine

## Note
- All questions are generated based on your actual resume content.
- No generic or irrelevant questions.
- Feedback is basic; you can extend it with OpenAI API for smarter feedback.
