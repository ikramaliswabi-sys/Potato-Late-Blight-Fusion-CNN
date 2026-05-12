## 🏆 Best Paper Award – SCI-2026

I am pleased to share that this project received the **Best Paper Award** at the **8th International Conference on Smart Computing and Informatics (SCI-2026)** held in Hanoi, Vietnam.

### 📄 Paper Title
**Detection of Potato Late Blight Using Leaf Images and a CNN-based Fusion Deep Learning Model**

This research presents a fusion deep learning framework combining **EfficientNetB0** and **InceptionV3** with transfer learning techniques for accurate potato leaf disease classification using the PlantVillage dataset.

The project focuses on early detection of Potato Late Blight to support intelligent and efficient agricultural disease monitoring using Artificial Intelligence and Computer Vision.

[📄 View Award Certificate](./Best%20Paper%20ID%20450.pdf)

# Potato Late Blight Detection using Fusion CNN

This repository contains the implementation of a fusion deep learning model for the detection of Potato Late Blight (PLB) using leaf images. The model combines EfficientNetB0 and InceptionV3 architectures with transfer learning to improve classification performance.

---

## 📌 Project Overview

Potato Late Blight (PLB), caused by *Phytophthora infestans*, is one of the most destructive plant diseases affecting global food security. Early detection is essential to reduce crop losses and unnecessary pesticide use.

This project proposes a fusion CNN architecture that integrates:

- EfficientNetB0
- InceptionV3
- Feature concatenation
- Fully connected layers with dropout
- Softmax output layer

The model classifies potato leaf images into:

- Early Blight
- Late Blight
- Healthy

---

## 🧠 Model Architecture

The proposed architecture consists of:

1. Input Layer (224×224 RGB images)
2. Two parallel pretrained CNN branches:
   - EfficientNetB0
   - InceptionV3
3. Global Average Pooling
4. Feature Concatenation
5. Dense layers with Dropout
6. Softmax output layer

Transfer learning is applied with partial layer freezing.

---

## 📊 Dataset

Dataset used:
- PlantVillage Dataset (Publicly Available)

The dataset includes labeled images of:
- Potato___Early_blight
- Potato___Late_blight
- Potato___healthy

Note: The dataset is not included in this repository due to size and licensing considerations.

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/ikramaliswabi-sys/Potato-Late-Blight-Fusion-CNN.git
cd Potato-Late-Blight-Fusion-CNN
```

Install required libraries:

```bash
pip install -r requirements.txt
```

---

## 🚀 How to Run

1. Place the PlantVillage dataset in the appropriate directory.
2. Open the notebook or Python script.
3. Run the training cells sequentially.
4. The model will:
   - Perform data preprocessing
   - Apply augmentation
   - Conduct hyperparameter tuning
   - Train the final fusion model
   - Evaluate performance on the test set

---

## 📈 Evaluation Metrics

The model performance is evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

---

## 🔬 Hyperparameter Tuning

Bayesian Optimization (Keras Tuner) is used to tune:

- Dropout rate
- Dense units
- Learning rate
- Number of frozen layers in each backbone

---

## 📜 Citation

If you use this code in your research, please cite:

Ikram Ali, "Potato Late Blight Detection using Fusion CNN", GitHub Repository, 2026.

Repository link:
https://github.com/ikramaliswabi-sys/Potato-Late-Blight-Fusion-CNN

---

## 📬 Contact

For academic collaboration or inquiries, please contact through GitHub.

