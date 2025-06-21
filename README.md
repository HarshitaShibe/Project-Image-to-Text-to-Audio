# Project-Image-to-Text-to-Audio
This project extracts text from images using Tesseract OCR and converts it into speech using Google's Text-to-Speech. It can be used for accessibility, document reading or language learning. Just upload an image and the system reads the text aloud!

```mermaid
flowchart TD
    A[Start] --> B[User provides Image]
    B --> C[Load image using PIL]
    C --> D[Extract text using pytesseract]
    D --> E[Display extracted text]
    E --> F[Convert text to speech using gTTS]
    F --> G[Save as MP3 file]
    G --> H[Play or use output audio]
    H --> I[End]
```

