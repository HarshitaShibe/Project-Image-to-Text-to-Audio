# Project-Image-to-Text-to-Audio
This project extracts text from images using Tesseract OCR and converts it into speech using Google's Text-to-Speech. It can be used for accessibility, document reading or language learning. Just upload an image and the system reads the text aloud!

```mermaid
flowchart TD
    A[Start] --> B [User provides Image]
    B --> C [Load image using PIL (Python Imaging Library)]
    C --> D [Extract text using pytesseract (OCR)]
    D --> E [Display extracted text in console]
    E --> F [Pass text to gTTS (Google Text-to-Speech)]
    F --> G [Convert to speech and save as MP3]
    G --> H [Play or use output audio file]
    H --> I [End]

