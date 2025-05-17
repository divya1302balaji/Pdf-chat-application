#  PDF Chat Application

This is a Streamlit-based web application that allows users to **ask questions about the contents of a PDF file** using a transformer-based Question Answering model.

##  Overview

This application:
- Extracts text from PDF documents
- Uses a pre-trained NLP model (`deepset/roberta-base-squad2`) for question answering
- Enables interactive question submission and response directly via a web interface

##  Tech Stack

- **Frontend:** Streamlit
- **Backend:** Hugging Face Transformers
- **PDF Parsing:** PyPDF2
- **Deployment:** Localhost / ngrok (for external sharing)

##  Model Used

- Model: `deepset/roberta-base-squad2`
- Framework: Hugging Face Transformers
- Task: Extractive Question Answering

##  How It Works

1. Upload a `.pdf` file.
2. The app extracts the text from the uploaded file.
3. Enter a question related to the document.
4. The model will provide an answer based on the PDF content.
