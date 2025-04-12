
# Brain Tumor Classification Using Deep Learning

This project focuses on building a deep learning model to classify brain tumors from MRI images into four categories: **Glioma**, **Meningioma**, **Pituitary**, and **No Tumor**. The goal was to combine medical imaging with machine learning to assist in early and accurate diagnosis.

---

## 🔍 Overview

I developed this project to deepen my understanding of transfer learning and real-world medical image classification. By leveraging the power of **VGG16**, a well-known CNN architecture, and fine-tuning it on MRI image data, the model achieved high classification accuracy while remaining lightweight and practical.

In addition, I integrated **MongoDB** as a data source for training, showcasing how deep learning workflows can be combined with database-backed image storage.

---

## 📌 Features

- Multi-class classification of brain MRI scans
- Fine-tuned **VGG16** using transfer learning
- Data fetched and managed using **MongoDB**
- High accuracy achieved on clean, preprocessed image data
- Easily extendable to include new data sources or architectures

---

## 🛠️ Installation

Clone the repository:
git clone https://github.com/shivichourey/brain-tumor-classification.git
cd brain-tumor-classification


---

## 🧠 Dataset

- `dataset3/All_images`: Contains MRI images labeled with brain tumor types.  
  [Kaggle Source](https://www.kaggle.com/datasets/adityakomawar/dataset3)

- `datasetno/no_tumor`: Contains MRI images without any tumor.  
  [Kaggle Source](https://www.kaggle.com/datasets/adityakomawar/datasetno)

**Categories:**
- Glioma
- Meningioma
- Pituitary
- No Tumor

---

## 🧱 Model Architecture

The model uses **VGG16** pre-trained on ImageNet. Final layers are replaced with:
- Dense layer with ReLU activation
- Dropout for regularization
- Output layer with softmax activation for four classes

You can view the full model diagram in `Architecture.png`.

---

## 📊 Evaluation

Metrics like accuracy, precision, recall, and confusion matrix are used to evaluate the model. The model was able to distinguish among the four categories with strong generalization on unseen test data.

---

## 💡 Future Improvements

- Replace VGG16 with more modern architectures like ResNet or EfficientNet
- Deploy as a Flask/Streamlit web app
- Integrate automated pipelines using **GitHub Actions**
- Explore segmentation using U-Net for locating tumor regions

---

## 📬 Contact

If you found this project helpful or want to collaborate, feel free to connect:

**Shivi Chourey**  
[LinkedIn](https://www.linkedin.com/in/shivi-chourey)  
[GitHub](https://github.com/shivichourey)  
shivichourey09@gmail.com

---

> *Inspired by open-source ideas, built with a focus on real-world use and technical depth.*

```

---

Would you like me to also add this project to the "Projects" section of your resume with a personalized summary?
