# Sentimental-analysis-
# Decoding Emotions through Sentiment Analysis of Social Media Conversations

A multimodal sentiment analysis system that decodes user emotions from social media posts using text, emojis, images, and GIFs. This project combines state-of-the-art natural language processing (NLP) and computer vision models to classify sentiments as Positive, Negative, or Neutral.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [How to Run](#how-to-run)
- [Model Details](#model-details)
- [Dataset](#dataset)
- [Demo](#demo)
- [Screenshots](#screenshots)
- [Contributors](#contributors)
- [License](#license)

---

## Introduction
This project explores how social media content can be analyzed to determine user emotions. It integrates multiple data formats (text, images, emojis, GIFs) and uses deep learning to interpret emotional context in posts, tweets, and comments.

## Features
- Custom-trained BERT model for text sentiment classification
- CNN (ResNet50) model for image-based emotion detection
- Emoji sentiment mapping based on Unicode emotion tags
- GIF-to-frame extraction and analysis for sentiment cues
- Gradio-based web interface with dragon-themed UI

## Technologies Used
- Python 3.10+
- PyTorch / TensorFlow / Keras
- Transformers (HuggingFace)
- OpenCV, PIL
- Gradio
- Pandas, NumPy, Scikit-learn
- Google Colab (deployment)

## Project Structure
