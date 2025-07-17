# NeuroGen: Emotion to Language System from EEG Signals using Deep Learning

## Project Overview

NeuroGen is an assistive AI system designed to help non-verbal individuals express emotions through brainwave signals (EEG).  
This project classifies EEG signals into emotions, generates natural language sentences based on detected emotions using GPT-2, and synthesizes speech from these sentences.

## Features

- EEG signal preprocessing and normalization  
- Emotion classification using three models:
  - 1D CNN (Teacher model)  
  - EEGNet (EEG-specific baseline)  
  - LSTM (temporal modeling)  
- Knowledge Distillation to train a compact student model  
- Emotion-to-text generation with GPT-2  
- Text-to-speech synthesis using gTTS  
- Comprehensive comparative analysis of model performance  

## Dataset

The project uses the publicly available [EEG Brainwave Dataset: Feeling Emotions](https://www.kaggle.com/datasets/birdy654/eeg-brainwave-dataset-feeling-emotions) from Kaggle.

## Future Work

- Expand the model to support real-time EEG signal streaming for live emotion recognition.  
- Incorporate multimodal data (e.g., ECG, facial expressions) to improve classification accuracy.  
- Fine-tune or train larger language models for more personalized and context-aware text generation.  
- Develop a mobile or embedded deployment for assistive devices using the distilled models.  
- Integrate advanced speech synthesis systems for more natural and expressive voice output.  
- Explore continual learning to adapt the model to new users without forgetting previous knowledge.

## Team

- Akanksha Rai
- Zhanel Ashirbek
- Denny Irfasha
