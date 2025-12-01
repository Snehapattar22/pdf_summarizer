# AI PDF Summarizer & Quiz Generator

An AI-powered PDF Summarizer built with Python, Streamlit, and GPT-3.5, designed to help users quickly understand long documents and generate quizzes for revision.

## Features
1. PDF Summarization (Python + GPT-3.5)
Upload any PDF file.
Extracts text using Python libraries.
Sends processed text to GPT-3.5 for clean, structured summarization.
Handles large PDFs by chunking and batching text.

2. Automatic Quiz Generation
Creates MCQs, True/False, or short questions.
Quiz content is fully based on the uploaded document.
Useful for revision, study, and self-assessment.

3. Streamlit Frontend
Clean and interactive UI.
Simple drag-and-drop PDF upload.
Real-time summary and quiz generation display.
Mobile-friendly interface.

## Tech Stack
Python

## Used for:
- PDF text extraction
- Preprocessing (cleaning, splitting, chunking)
- Interacting with the GPT-3.5 model
- Quiz prompt generation

Integrating backend logic with Streamlit

## Libraries Used
streamlit
openai
PyPDF2 or pdfplumber
tiktoken (optional for token counting)
dotenv

## Installation
1. Clone the repository
   git clone https://github.com/Snehapattar22/pdf_summarizer.git
   cd pdf-summarizer

2. Install dependencies
   pip install -r requirements.txt

3. Add your API Key
   Create a .env file:

OPENAI_API_KEY=your_api_key

4. Run the App
   streamlit run app.py
