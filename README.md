# 🐱 Catify: AI-Powered Emotion Detection for Cats (Mobile Demo)

Catify is a real-time mobile application that analyzes the emotional states of domestic cats using deep learning. This demo repository showcases the capabilities of the final product without exposing the source code.

📱 Developed using Flutter & integrated with a custom-trained MobileNetV2 model, Catify can predict 8 distinct feline emotions by analyzing facial expressions and body posture.

> 🚫 **Note:** This is a demonstration repo. Source code is not public. Access can be granted upon request under specific conditions.

---

## 🧠 Project Overview

- **Goal:** Detect cats’ emotional states (fear, aggression, curiosity, etc.) from images using deep learning and computer vision.
- **Scope:** A fully integrated **AI-powered mobile app** for emotion recognition in tabby cats.
- **Target Users:** Researchers, pet owners, and veterinarians interested in behavioral insights.

---

## 🎯 Key Features

- Real-time emotion detection from images (camera or gallery).
- Multi-label classification (e.g., “curious” + “relaxed” simultaneously).
- Lightweight and mobile-optimized TensorFlow Lite model.
- Emoji-based emotion summary and full probability bar chart.
- Intuitive UI/UX for quick interaction.

---

## 📊 Model Highlights

- **Architecture:** MobileNetV2
- **Training Approach:** Multi-label classification with sigmoid outputs.
- **Classes:** Fear, Stress, Aggression, Relaxation, Contentment, Playfulness, Curiosity, Neutral
- **Final Accuracy:**  
  - 📈 Macro F1 Score: `0.89`  
  - 📈 Samples Avg. F1 Score: `0.92`  
  - ⚙️ Inference: ~100ms on mid-range Android devices

---

## 🧪 Dataset Summary

- ~9,000+ initial images, refined to 463 highly distinctive examples
- Manually labeled using a custom-built Python GUI
- Only tabby cats used to ensure consistency
- All images sourced from a public-domain dataset ([Crawford’s Cat Dataset on Kaggle](https://www.kaggle.com/datasets/crawford/cat-dataset))

---

## 📷 Screenshots

![resim](https://github.com/user-attachments/assets/8da3cbeb-3bbf-41f0-8d67-2a1286b18cd3)
![resim](https://github.com/user-attachments/assets/420b6c5e-5d86-475f-ae4e-d045efca7842)


---


## 🛠️ Tech Stack

- **Mobile App:** Flutter, Dart  
- **ML Framework:** TensorFlow + TFLite  
- **Model Training:** Python, Keras, Optuna  
- **Deployment:** Android-ready (.tflite) format

---

## 🔒 About Access

The full source code and dataset are not publicly available to protect intellectual property and data labeling effort. However, the project can be presented in detail during interviews or shared privately upon request.

> 📝 For collaboration or access inquiries, contact via GitHub or LinkedIn.

---

## 👨‍💻 Author

**Furkan Gença**  
B.Sc. in Software Engineering, Samsun University  
*Graduation Project, 2025*

---

📄 License: CC BY-NC-ND 4.0 — See LICENSE file for details.
