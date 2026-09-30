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

<img width="1344" height="622" alt="01" src="https://github.com/user-attachments/assets/86fb40bd-385c-4030-92c4-2ded968949fb" />
<img width="1356" height="611" alt="02" src="https://github.com/user-attachments/assets/69487d5e-9e99-4272-a1a8-b238393bc9a4" />
<img width="1337" height="598" alt="03" src="https://github.com/user-attachments/assets/4399b89d-4ac3-4b81-9c74-bb68f8b54f10" />
<img width="1365" height="605" alt="04" src="https://github.com/user-attachments/assets/b7c21615-7e16-4330-9a29-4ecb4480012d" />







 Run
streamlit run app.py

 Output

The application displays the extracted text, word attention bars, and the highest-attended word.

 Note

This project is designed as an educational demonstration of OCR, embeddings, and the attention mechanism.
