# 🐱 Catify: AI-Powered Emotion Detection of Cats (Mobile Demo)

Catify is a real-time mobile application that analyzes emotional states of domestic cats using deep learning. This demo repository showcases the capabilities of the final product without exposing the source code.

📱 Built with Flutter and powered by a custom-trained MobileNetV2 model, Catify predicts 8 distinct feline emotions by analyzing facial expressions and body posture.

---

## 🧠 Project Overview

- **Goal:** Detect cats’ emotional states (fear, aggression, curiosity, etc.) from images using deep learning and computer vision.
- **Context:** A fully integrated **AI-powered mobile app** designed for real-time emotion recognition in tabby cats.
- **Target Users:** 👤 Pet owners, 🧪 researchers, 🩺 veterinarians

---

## 🎯 Key Features

- Real-time emotion detection from camera or gallery images
- Multi-label classification (e.g., “curious” + “relaxed”)
- Lightweight and mobile-optimized TensorFlow Lite model
- Emoji-based emotion summary + full probability bar chart
- Intuitive UI/UX for efficient interaction

---

## 📊 Model Highlights

- **Architecture:** MobileNetV2  
- **Training:** Multi-label classification (sigmoid output)  
- **Emotion Classes:** Fear · Stress · Aggression · Relaxation · Contentment · Playfulness · Curiosity · Neutral  
- **Performance:**  
  - 📈 Accuracy: `85.7%`  
  - 📈 Macro F1 Score: `0.89`  
  - 📈 Sample-Averaged F1 Score: `0.92`  

---

## 🧪 Dataset Summary

- ~9,000 initial images, filtered to 463 highly distinctive samples
- Manually labeled via custom Python GUI
- Focused on tabby cats for consistency
- Based on [Crawford’s Cat Dataset (Kaggle)](https://www.kaggle.com/datasets/crawford/cat-dataset)

---

## 📷 Screenshots

| Detection Interface | Result Display |
|---------------------|----------------|
| ![UI 1](https://github.com/user-attachments/assets/8da3cbeb-3bbf-41f0-8d67-2a1286b18cd3) | ![UI 2](https://github.com/user-attachments/assets/420b6c5e-5d86-475f-ae4e-d045efca7842) |

---

## 🛠️ Tech Stack

- **Mobile App:** Flutter · Dart  
- **ML Framework:** TensorFlow · TensorFlow Lite  
- **Model Training:** Python · Keras  
- **Deployment:** Android-ready (.tflite) model

---

## 👨‍💻 Author

**Furkan Gença**  
B.Sc. in Software Engineering, Samsun University  
*Graduation Project, 2025*

---

📄 License: [CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/)
