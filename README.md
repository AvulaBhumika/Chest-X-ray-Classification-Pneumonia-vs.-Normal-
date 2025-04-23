# 🩻 Chest X-ray Classification: Pneumonia vs. Normal (Deep Learning with Grad-CAM)

![image](https://github.com/user-attachments/assets/5cd956c2-191f-4a68-9c04-e1d7e4ca4e49)


A deep learning project built to classify chest X-ray images into **PNEUMONIA** or **NORMAL** classes. The solution leverages a **Convolutional Neural Network (CNN)** architecture for classification and uses **Grad-CAM** for model explainability. This project showcases how AI can support medical diagnostics with high accuracy and transparency.

---

## 📂 Dataset Structure

Dataset used: [Kaggle Pneumonia Dataset](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)

```
chest_xray/
├── train/
│   ├── NORMAL/
│   └── PNEUMONIA/
├── val/
│   ├── NORMAL/
│   └── PNEUMONIA/
└── test/
    ├── NORMAL/
    └── PNEUMONIA/
```

- Each subfolder contains raw chest X-ray images in `.jpeg` format.

---

## ⚙️ Stack & Frameworks

- **Python 3.8+**
- **Torch**
- **torchvision** for image handling
- **Matplotlib** for visualizations
- **Scikit-learn** for evaluation metrics
- **Grad-CAM** for model interpretability

---

## 🚀 Features

- 📈 High-accuracy CNN-based image classification
- ✅ Precision, Recall, F1-Score based performance evaluation
- 🧠 Grad-CAM integration for visual explanation of model decisions
- 📊 Support for dynamic batch validation from folders
- 🧪 Tested on validation images from both classes for real-world verification

---

## ✅ Model Performance (Validation Set)

| Metric      | NORMAL | PNEUMONIA | Avg |
|-------------|--------|-----------|-----|
| Precision   | 1.00   | 0.89      | 0.94 |
| Recall      | 0.88   | 1.00      | 0.94 |
| F1-Score    | 0.93   | 0.94      | 0.94 |
| **Accuracy**|        |           | **0.94** |

> Final model shows high generalization with minimal false positives/negatives.

---

## 📸 Metrics Output

![image](https://github.com/user-attachments/assets/92324a5d-919b-44fe-91e1-157aa72bb78a)

![image](https://github.com/user-attachments/assets/68d87c99-8778-44fd-a803-563fe182d4d9)


> Grad-CAM helps visualize the lung regions the model is focusing on during prediction — boosting interpretability and trust in predictions.

---

## 📈 Possible Enhancements

- ✅ Add GUI using Flask or Streamlit for drag-drop predictions
- ✅ Deploy model on Hugging Face Spaces or AWS SageMaker
- ✅ Incorporate mobile support (TF Lite)
- ✅ Explore ensemble or transformer-based backbones (e.g., ViT)


---

## 💡 Real-World Impact

> This model can assist radiologists in preliminary screening for pneumonia using chest X-rays, potentially accelerating diagnosis and treatment.


---

⭐ If you find this project helpful, give it a star and share it with others!

