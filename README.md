# Advanced Fake Content Detection Telegram Bot 

**Description:**  
AI-powered Telegram bot to detect deepfake and fake content in **text, images, videos, and URLs**, providing real-time credibility scores to prevent misinformation, defaming content, and digital attacks.

---

## Project Overview
AlphBot is a **multi-modal AI system** designed to protect users and organizations from fake or manipulated content. It integrates **state-of-the-art deep learning models, NLP pipelines, and computer vision** to detect misinformation and deliver **credibility insights in real time**.  

The bot is fully deployable on **Telegram**, making it accessible and user-friendly. This project demonstrates skills in **AI model deployment, multi-modal data processing, and automation**, fulfilling typical AI developer job requirements.

---

##  Key Features
- **Text Analysis**: Detects fake/misleading text using NLP models.  
- **Image & Video Detection**: Uses **CNN (Xception) + Grad-CAM** for visual deepfake detection.  
- **URL Verification**: Checks website credibility and potential misinformation.  
- **Credibility Score**: Assigns a trust score (0–100%) for each content input.  
- **Telegram Integration**: Users interact directly with the bot.  
- **Real-Time Results**: Fast processing for immediate feedback.  
- **Modular Design**: Easy to expand for additional platforms or new data types.  

---

## 🛠️ Tech Stack
| Component            | Details |
|----------------------|---------|
| Language             | Python |
| AI/ML Libraries      | TensorFlow, Keras, Hugging Face Transformers, OpenCV |
| Models               | Xception (image/video), NLP model for text |
| Deployment           | Telegram Bot API |
| Visualization        | Grad-CAM for image/video explanation |
| Optional Tools       | ONNX Runtime, Pandas, NumPy |

## Workflow Diagram
flowchart TD
    A[User Input (Text/Image/Video/URL)] --> B[Telegram Bot API]
    B --> C[Preprocessing & Feature Extraction]
    C --> D1[NLP Model for Text]
    C --> D2[CNN/Xception for Images]
    C --> D3[Video Frame Extraction + Detection]
    C --> D4[URL Reputation Check]
    D1 --> E[Credibility Score Calculation]
    D2 --> E
    D3 --> E
    D4 --> E
    E --> F[Bot Reply with Analysis + Score]


## Results

Accuracy: ~90% on benchmark deepfake datasets
Visualization: Grad-CAM heatmaps highlight manipulated regions
Deployment: Fully functional Telegram bot prototype for real-time testing.

## Disclaimer

The full source code and dataset are not shared due to size and policy restrictions.
 
