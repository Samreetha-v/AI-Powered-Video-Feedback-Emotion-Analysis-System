# AI-Powered-Video-Feedback-Emotion-Analysis-System

📌 Overview

This project is an AI-driven feedback system that enhances traditional course evaluation by analyzing both text and video feedback. It combines Natural Language Processing (NLP) for sentiment analysis and Facial Emotion Recognition (FER) for video-based emotion detection, providing educators with deeper insights into student experiences.

By capturing not just what students say but also how they feel, the system offers a holistic view of feedback that goes beyond conventional rating-based surveys.

🎯 Key Features

📊 Text Sentiment Analysis – Uses Hugging Face Transformers (BERT/DistilBERT) to classify feedback as positive, neutral, or negative.

🎥 Facial Emotion Recognition – Detects emotions like happiness, sadness, and neutrality from video feedback using FER + OpenCV.

📈 Data Visualization – Displays insights with bar charts, pie charts, and graphs for easy interpretation.

🌐 User-Friendly Interface – Built with Gradio, and can be integrated with Django/Flask for deployment.

🧑‍🏫 Educator Dashboard – Provides a combined emotional and textual profile of student responses for course improvement.

🧠 Problem Statement

Traditional feedback systems often miss emotional cues, relying only on text ratings. This limits understanding of student satisfaction. Our system addresses this by integrating multimodal AI (text + video) to deliver a more accurate and human-centered feedback system.

⚙️ Tech Stack

Backend / ML: Python, NLP (Transformers), FER, OpenCV

Visualization: Matplotlib, Seaborn

Interface: Gradio (for prototyping), Django (for scalable deployment)

Environment: Jupyter Notebook / Google Colab

🧪 Workflow

Data Collection – Students provide text and video feedback.

Sentiment Analysis – Classify text into positive, neutral, negative.

Emotion Recognition – Detect emotions (happy, sad, neutral) from video frames.

Fusion Layer – Combine text + video insights.

Visualization & Reporting – Generate reports with charts and aggregated insights.

Deployment – Provide educators with a web-based interface (Gradio/Django).

💻 How to Run
# Clone the repository
git clone https://github.com/yourusername/ai-feedback-system.git
cd ai-feedback-system

# Install dependencies
pip install -r requirements.txt

# Run in Jupyter/Colab
jupyter notebook ai_feedback_system.ipynb

# Or launch Django app (if included)
python manage.py runserver

📈 Results

✅ Captures both verbal and non-verbal feedback.

✅ Provides visual insights into student emotions.

✅ Helps educators make data-driven improvements.

📸 Sample Outputs

Sentiment distribution (positive, neutral, negative).

Emotion charts (happy, sad, neutral).

Combined student feedback dashboard.

📜 Future Improvements

Extend emotion categories (anger, surprise, fear).

Add real-time feedback recording via webcam.

Deploy as a full Django web application for institutions.

Ensure data privacy & consent mechanisms for video feedback.

👩‍💻 Authors

Samreetha V
