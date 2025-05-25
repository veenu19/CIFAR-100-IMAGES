
# 📚 CIFAR-100 Image Classification

This project performs advanced image classification on the [CIFAR-100 dataset](https://www.cs.toronto.edu/~kriz/cifar.html) using both a **custom Convolutional Neural Network (CNN)** and **Transfer Learning with ResNet50**. It covers data preprocessing, augmentation, model building, training with callbacks, performance evaluation, and detailed analysis.

---

## 🚀 Project Objectives

- Build a custom CNN and evaluate its performance.
- Apply Transfer Learning using a pretrained ResNet50 model.
- Improve model generalization with data augmentation and learning rate scheduling.
- Analyze training and validation performance metrics.
- Interpret model behavior using confusion matrices and per-class analysis.
- Compare performance and suggest future improvements.

---

## 🗂️ Project Structure

```
cifar100-classification/
│
├── notebook.ipynb                # Main Jupyter Notebook
├── report.pdf                    # Final PDF Report (5–8 pages)
├── README.md                     # Project Overview
├── models/                       # Saved model files (if any)
│   ├── custom_cnn.h5
│   └── resnet50_transfer.h5
├── images/                       # Visualization assets
│   ├── sample_augmented.png
│   ├── training_curve.png
│   ├── confusion_matrix.png
└── requirements.txt              # Required Python packages
```

---

## 🧠 Methods Used

- **Data Preprocessing**
  - Normalization, train-validation-test split
- **Data Augmentation**
  - Rotation, flipping, zoom, shift, shear
- **Model Architectures**
  - Custom CNN with Dropout and BatchNorm
  - Transfer Learning with ResNet50 + custom top layers
- **Optimization Techniques**
  - Adam optimizer
  - Learning rate scheduler
  - Early stopping and model checkpointing
- **Evaluation**
  - Accuracy, Precision, Recall, F1-score
  - Confusion matrix
  - Top-1 and Top-5 accuracy

---

## 📊 Results Summary

| Metric               | Custom CNN | ResNet50 (Transfer Learning) |
|----------------------|------------|------------------------------|
| Test Accuracy        | XX.XX%     | **XX.XX%**                   |
| Top-5 Accuracy       | XX.XX%     | **XX.XX%**                   |
| F1 Score (Macro Avg) | XX.XX      | **XX.XX**                    |

✅ ResNet50 significantly outperformed the custom CNN in all metrics.

---

## 📎 Key Visualizations

- ✅ Training and Validation Accuracy/Loss Curves  
- ✅ Sample Augmented Images  
- ✅ Confusion Matrix with Top Misclassified Classes  

---

## 💡 Future Improvements

- Use EfficientNet or Vision Transformers
- Try AutoAugment or MixUp for richer augmentation
- Apply model ensembling for robust predictions
- Add Grad-CAM for explainable AI insights

---

## 📦 Requirements

Install dependencies via:

```bash
pip install -r requirements.txt
```

Recommended Python version: `>=3.8`

---

## 📁 Dataset

The [CIFAR-100 dataset](https://www.cs.toronto.edu/~kriz/cifar.html) consists of 60,000 32×32 color images in 100 classes, with 600 images per class.

- 50,000 training images
- 10,000 test images
- 100 fine-grained labels and 20 coarse categories

---

## 🧑‍💻 Author

VEENU BISHNOI
Email: bishnoiveenu75@gmail.com    
Project Date:25 May 2025
