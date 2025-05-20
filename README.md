# Multimodal Language Translation System

A comprehensive Multimodal Translation System designed to handle various translation modes including Speech-to-Speech, Speech-to-Text, Text-to-Speech, and Text-to-Text. This system supports multiple languages with an initial focus on **English**, **Hindi**, and **Telugu**.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Architecture](#architecture)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Evaluation](#Evaluation)
- [Demo](#demo)
- [Future Work](#future-work)

## Overview

This project focuses on developing a seamless **language translation pipeline** that can:
- Convert speech to text
- Translate text between languages
- Convert translated text back to speech
- Amplify and measure audio signal characteristics

It is designed with modularity in mind, making it easy to extend, improve, or adapt for different languages or tasks.

## Features

- **Speech-to-Speech Translation**  
- **Speech-to-Text Translation**  
- **Text-to-Speech Generation**  
- **Text-to-Text Translation**  
- Support for English, Hindi, and Telugu  
- Real-time or file-based translation
- Includes an Amplifier for Input Audio Amplification

## Architecture

Architecture.png

- **Audio Amplification:** Enhances speech signals for better recognition
- **STT Module:** Converts spoken language to text
- **Translation Engine:** Translates text between supported languages
- **TTS Module:** Converts text back to natural-sounding speech

## Technologies Used

- **Python 3.x**
- **Jupyter Notebook**
- **Whisper**
- **HuggingFace Transformers**
- **Torchaudio**, **Torch**, **pydub**, **Librosa**, **soundfile**
- **NumPy**, **Matplotlib**
- **Transformers**
- **scipy**, **sklearn**
- **sentenpiece**

## Usage

### 1. Clone the Repository
```bash
git clone https://github.com/YasmeenShaik-Tech/Multimodal-Language-Translation-System.git
cd Multimodal-Language-Translation-System
```
```bash
### 2. Install Dependencies

pip install -r requirements.txt
```
```bash
### 3. Run the Notebooks

Use Jupyter Lab or Notebook:

jupyter notebook notebooks/MLTS.ipynb
```

## Evaluation 

Accuracy: 83.33%

F1 Score: 0.83

BLEU Score: 88

## Demo

## Future Work

Integrate real-time audio stream translation

Deploy with a user-friendly web interface (Gradio)

Support additional languages

Improve model accuracy with domain-specific fine-tuning

Deploy as a mobile/web app
