# Watch vs Ring Image Classifier

This project implements a **deep learning-based image classification model** that can identify whether an image contains a **watch** or a **ring**. The solution uses **TensorFlow/Keras** and **MobileNetV2 transfer learning** for better performance on a small dataset (only 10 images per class).

---

## 📌 Features
- Classifies images as **Watch** or **Ring**.
- Built with **TensorFlow/Keras** and **MobileNetV2** (transfer learning).
- Supports **data augmentation** for small datasets.
- Allows **uploading custom images** for prediction.
- Works on **Google Colab** or locally.

---

## 🛠 How It Works
1. **Dataset**  
   - Two folders: `watch/` and `ring/`, each with ~10 images.
   - Data augmentation applied to improve accuracy with limited samples.

2. **Model**  
   - Transfer learning from MobileNetV2.
   - Global Average Pooling + Dropout + Dense layer for classification.

3. **Training**  
   - Fine-tuned for small datasets.
   - Achieves good accuracy even with 20 images total.

4. **Prediction**  
   - Upload any image (watch or ring), and the model predicts the category with confidence.


