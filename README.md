# Mini-Project: Image-to-Speech

This project utilizes Python to convert text extracted from images into spoken audio. Leveraging Optical Character Recognition (OCR) through pytesseract and text-to-speech (TTS) capabilities via the gtts library, this script automates the process of reading text from images and converting this text into natural-sounding speech, saved as an MP3 file. This tool can be particularly useful for accessibility purposes, aiding in reading text from various images for those who require auditory assistance.

## Features

- **Text Extraction**: Utilizes pytesseract to perform OCR on images, extracting visible text.
- **Speech Generation**: Converts the extracted text into natural-sounding speech using gtts (Google Text-to-Speech).
- **MP3 Output**: Saves the generated speech as an MP3 file for easy playback on various devices.

## Prerequisites

Before running this script, ensure you have the following installed:
- Python
- pytesseract
- Pillow (PIL Fork)
- pygame (optional for playback in the script)
- gtts

### Installation Guide

1. **Python**: Download and install Python from [python.org](https://www.python.org/downloads/).

2. **Libraries**: Install the required Python libraries using pip:

```bash
pip install pytesseract Pillow gtts pygame
