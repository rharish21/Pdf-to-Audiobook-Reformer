# PDF to Audio Converter

A Flask-based web application that converts PDF files into audio using **Text-to-Speech (TTS)** technology. This project is designed to help users listen to the content of PDF files, making it accessible for those who prefer audio over text.

---

## Features

- **PDF Upload**: Users can upload PDF files to the application.
- **Text Extraction**: Extracts text from the uploaded PDF using `PyPDF2`.
- **Text-to-Speech Conversion**: Converts the extracted text into audio using `gTTS` (Google Text-to-Speech).
- **Audio Download**: Allows users to download the generated audio file.

---

## Technologies Used

- **Flask**: Python web framework for building the application.
- **PyPDF2**: Library for extracting text from PDF files.
- **gTTS**: Google Text-to-Speech library for converting text into audio.
- **HTML/CSS**: For the frontend interface.

---

## How to Use

1. Clone the repository:

```bash
   git clone https://github.com/your-username/pdf-to-audio-converter.git
```
2. Navigate to the project directory:

```bash
cd pdf-to-audio-converter
```
3. Install the required dependencies:

```bash
pip install -r requirements.txt
```
4. Run the Flask application:

```bash
python app.py
```
5. Open your browser and visit:

```bash
http://127.0.0.1:5000
```
6. Upload a PDF file and download the generated audio.