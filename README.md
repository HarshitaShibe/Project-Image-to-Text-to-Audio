# Project-Image-to-Text-to-Audio
This project extracts text from images using Tesseract OCR and converts it into speech using Google's Text-to-Speech. It can be used for accessibility, document reading or language learning. Just upload an image and the system reads the text aloud!

Visual Overview
```mermaid
flowchart TB
    A[Start] --> B[User provides Image]
    B --> C[Load image using PIL]
    C --> D[Extract text using pytesseract]
    D --> E[Display extracted text]
    E --> F[Convert text to speech using gTTS]
    F --> G[Save as MP3 file]
    G --> H[Play or use output audio]
    H --> I[End]

Project Structure
📂 image-to-speech/
├── your-image.jpg
├── main.py
├── output.mp3
└── README.md

Applications
Text reading aid for visually impaired users
Voice-over from scanned documents
Educational tools for language learners
Automated reading for printed materials

```

