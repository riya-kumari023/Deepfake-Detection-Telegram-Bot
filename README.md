# Deepfake Detection Telegram Bot 

**Description:**  
AI-powered Telegram bot to detect deepfake content in images, videos, text, and URLs, providing credibility scores to prevent misinformation and defaming content.

## Overview
This project is an AI-based Telegram bot designed to **protect users from fake or manipulated content**. It analyzes multi-modal inputs (text, images, videos, URLs) and assigns a **credibility score** to each input. The system uses **deep learning models, NLP techniques, and computer vision** to identify manipulated content effectively.

## Features
- **Text Analysis**: Detects fake or misleading text content.  
- **Image & Video Detection**: Uses CNN (Xception) + Grad-CAM for deepfake detection.  
- **URL Verification**: Checks the credibility of web links.  
- **Credibility Score**: Provides a score (0–100%) for each content input.  
- **Telegram Integration**: Users can interact directly through Telegram.  

## Tech Stack
- **Language**: Python  
- **Libraries**: TensorFlow, Keras, OpenCV, Hugging Face Transformers  
- **Models**: Xception for deepfake detection, NLP model for text analysis  
- **Deployment**: Telegram Bot API  
- **Visualization**: Grad-CAM for image/video analysis  

## Workflow
```mermaid
flowchart TD
    A[User Upload (Text/Image/Video/URL)] --> B[Telegram Bot API]
    B --> C[Preprocessing]
    C --> D1[NLP Model for Text]
    C --> D2[CNN/Xception for Images]
    C --> D3[Video Frame Extraction + Detection]
    C --> D4[URL Reputation Check]
    D1 --> E[Credibility Score]
    D2 --> E
    D3 --> E
    D4 --> E
    E --> F[Bot Reply with Analysis + Score]

**## Results**

Accuracy: ~90% on benchmark deepfake datasets
Visualization: Grad-CAM heatmaps highlight manipulated regions
Deployment: Fully functional Telegram bot prototype for real-time testing.

**## Disclaimer**

The full source code and dataset are not shared due to size and policy restrictions.
 
