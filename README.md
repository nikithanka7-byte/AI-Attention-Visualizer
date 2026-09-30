AI Attention Visualizer

A beginner-friendly AI application that extracts text from study-note images using OCR, converts words into embeddings, and visualizes attention scores using a simple attention mechanism.

 Technologies Used
Python
Streamlit
Tesseract OCR
Sentence Transformers
NumPy
Pillow

Project Flow
Image → OCR → Word Embeddings → Attention → Visualization

 Features
Upload study-note images
Extract text using OCR
Generate word embeddings
Calculate attention scores
Display word attention bars
Identify the highest-attended word

Project Structure
AI-Attention-Visualizer/
├── app.py
├── ocr.py
├── embedding.py
├── attention.py
└── requirements.txt

Installation
pip install -r requirements.txt

Note: Tesseract OCR must be installed separately on Windows.

Application preview
[streamlit-app-2026-09-29-22-37-57.webm](https://github.com/user-attachments/assets/bd40d95b-5c74-4848-a26a-a7d159c01f67)


 Run
streamlit run app.py

 Output

The application displays the extracted text, word attention bars, and the highest-attended word.

 Note

This project is designed as an educational demonstration of OCR, embeddings, and the attention mechanism.
