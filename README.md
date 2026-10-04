# 🎭 Speech Emotion Detection

## 📌 Objective

The objective of this project is to analyze speech audio and predict the emotion expressed by the speaker.

The system uses a pretrained speech emotion recognition model to classify emotions such as:

- Happy
- Sad
- Angry
- Neutral

## 🛠️ Technologies Used

- Python
- Hugging Face Transformers
- HuBERT
- PyTorch
- Librosa
- SoundFile
- Gradio
- Google Colab

## 🧠 Model

This project uses:

`superb/hubert-base-superb-er`

The model is based on HuBERT and is fine-tuned for speech emotion recognition.

## 🔄 Workflow

Speech Audio
↓
Audio Processing
↓
HuBERT Model
↓
Feature Extraction
↓
Emotion Classification
↓
Confidence Score
↓
Gradio Interface

## ✨ Features

- Upload speech recordings
- Detect emotions from speech
- Display confidence scores
- Show multiple emotion predictions
- Interactive Gradio interface
- Uses a pretrained deep learning model

## 🧪 Example

### Input

A speech recording expressing happiness.

### Output

```text
Emotion: Happy
Confidence: 82%
