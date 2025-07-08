# A-Eye – AI Assistant for the Visually Impaired

A-Eye is an AI-powered application designed to assist visually impaired individuals by converting visual information into meaningful audio descriptions. It performs real-time image captioning, object detection, face recognition, and emotion analysis using advanced deep learning models.

- Understand who is in front of them
- Know what objects are around
- Hear how someone might be feeling
- Ask questions and receive voice responses (using LLM)

## 🔧 Features

- Image captioning using BLIP
- Object detection using YOLOv8
- Face recognition with custom face encoding
- Emotion detection using DeepFace
- Smart combined description generation
- Optional local LLM query support via Ollama
- Flask-based web interface for interaction

## 🛠️ Technologies Used

- Python
- Flask
- Transformers (BLIP)
- YOLOv8 (Ultralytics)
- Face Recognition
- DeepFace
- Pillow
- Ollama (LLaMA 3)
- HTML/CSS/JS

## 📸 Screenshots
Home Page:

![Screenshot_8-7-2025_235713_](https://github.com/user-attachments/assets/1bada81b-822e-4ab2-9164-7d5d8eb97877)

Interaction Pages:

![Screenshot_8-7-2025_235832_](https://github.com/user-attachments/assets/a2f889c1-ad3e-4ae0-a113-42614c851fbe)
![Screenshot_8-7-2025_235745_](https://github.com/user-attachments/assets/d1f403c5-edeb-4533-9e02-e2ee84d7c0fa)

Add Face Page:

![Screenshot_8-7-2025_23595_](https://github.com/user-attachments/assets/0b80a8c9-e8e2-45fa-93ea-604e6a198429)


## 🚀 Getting Started

```bash
git clone https://github.com/shalomxavier/A-Eye.git
cd A-Eye
pip install -r requirements.txt
python app.py
