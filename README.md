# Smart_Chest_X-Ray_Analysis# 

🩺 Chest Disease Detection using Deep Learning (R-CNN)


## ✨ Description

The **Chest Disease Detection using Deep Learning (R-CNN)** project automates the detection and classification of chest diseases from **X-ray images** using **Faster R-CNN architecture**. It assists radiologists in diagnosing conditions such as **pneumonia, tuberculosis, and lung cancer**. The project leverages the **NIH ChestX-ray14 dataset**, providing annotated data for robust training and evaluation.

---

## 📌 Objectives

- Develop a **Faster R-CNN-based model** for thoracic pathology detection.
- Evaluate model performance using **precision, recall, F1-score, and accuracy**.
- Apply **data augmentation and transfer learning** to enhance accuracy.
- Provide **interpretable outputs** using bounding box predictions.

---

## 🛠️ Technologies Used

- **Frameworks:** PyTorch, Detectron2
- **Visualization Tools:** Matplotlib, Seaborn
- **Model:** Faster R-CNN with ResNet-50 backbone
- **Dataset:** NIH ChestX-ray14
- **Utilities:** OpenCV, Google Colab

---

## 📂 Dataset

The **NIH ChestX-ray14 dataset** contains over **112,000 annotated chest X-ray images** across **14 disease classes**, including **Atelectasis, Cardiomegaly, and Pneumothorax**. This dataset is widely used for medical image analysis and serves as a benchmark for thoracic disease detection models.

🔗 **Dataset Link:** [NIH ChestX-ray14](https://nihcc.app.box.com/v/ChestXray-NIHCC)

---

## 📈 Results

### **1️⃣ Performance Metrics**

The model achieved strong performance across multiple disease classes:

- **F1-Score:** 91%
- **Accuracy:** 89%
- **Precision:** 88%
- **Recall:** 92%

These metrics validate the model's ability to accurately detect chest diseases while maintaining a balance between false positives and false negatives.

### **2️⃣ Loss Curve**

![image](https://github.com/user-attachments/assets/8438af93-5aa9-4341-a7ed-221ee441cdd2)


The **loss curve** tracks the model's convergence over epochs, demonstrating training stability and generalization performance.

### **3️⃣ Example Predictions with Confidence Scores**

![image](https://github.com/user-attachments/assets/dad6a216-e7ef-4733-976d-70693ca014f3)


Bounding box predictions highlight **regions of interest** in X-ray images with associated confidence scores, showcasing the model’s localization capabilities.

### **4️⃣ Prediction Table**

![image](https://github.com/user-attachments/assets/f6083d83-fde8-4e5a-b3a1-6e7d49da1739)


A tabular representation of sample **X-ray predictions**, including bounding box coordinates, predicted labels, and confidence scores, offering quantitative insights into model decision-making.

---

## 🌟 Future Scope

- **🔄 Real-Time Data:** Integrate APIs for live diagnostics.
- **🧠 Explainable AI:** Enhance interpretability with saliency maps.
- **🎯 Pixel-Level Segmentation:** Implement **Mask R-CNN** for more precise abnormality detection.
- **🌍 Global Dataset Expansion:** Incorporate rare diseases and multi-institutional datasets to improve model generalization.

---


