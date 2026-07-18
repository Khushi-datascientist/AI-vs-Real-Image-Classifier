# 🖼️ AI vs Real Image Classifier

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-Deep%20Learning-orange)
![CNN](https://img.shields.io/badge/Model-CNN-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

A Deep Learning project that classifies images as **AI-generated** or **Real** using a **Convolutional Neural Network (CNN)** built with **TensorFlow/Keras**.

This project demonstrates the complete workflow of an image classification pipeline including:

- Image preprocessing
- Dataset creation
- CNN model building
- Model training
- Performance evaluation
- Image prediction using a trained model

> **Note:** The dataset used in this project was created manually by collecting AI-generated and real images from publicly available sources and organizing them into separate folders for training.

---

# 📌 Overview

Artificial Intelligence has made it increasingly difficult to distinguish AI-generated images from real photographs or artwork. This project demonstrates how a Convolutional Neural Network (CNN) can learn visual patterns from labeled images and classify whether an input image is AI-generated or real.

The project was developed as a Deep Learning practice project using TensorFlow/Keras and focuses on understanding the complete image classification workflow rather than building a production-ready detection system.

---

# 🎯 Problem Statement

Given an input image, build a CNN model capable of predicting whether the image belongs to one of the following classes:

- 🟢 Real Image
- 🔴 AI-Generated Image

The model learns visual features from training images and performs binary image classification using TensorFlow.


---

# ✨ Features

- 🖼️ Binary image classification (AI-generated vs Real)
- 🧠 Convolutional Neural Network (CNN) built using TensorFlow/Keras
- 📂 Image loading directly from folder structure
- 🔄 Automatic image preprocessing and normalization
- 📊 Training, validation, and testing pipeline
- 📈 Model performance evaluation using Accuracy, Precision, and Recall
- 💾 Save and reload the trained deep learning model
- 🔍 Predict whether a new image is AI-generated or real
- 📉 TensorBoard support for monitoring the training process

---

---

# 🛠️ Tech Stack

| Category | Technology |
|----------|------------|
| Programming Language | Python |
| Deep Learning Framework | TensorFlow / Keras |
| Model | Convolutional Neural Network (CNN) |
| Image Processing | TensorFlow Image Dataset API |
| Data Handling | NumPy |
| Visualization | Matplotlib |
| Development Environment | Jupyter Notebook |
| Logging | TensorBoard |


# 📂 Dataset

This project uses a **custom image dataset** created by manually collecting images from publicly available sources.

The dataset consists of two classes:

- 🟢 **Real Images**
- 🔴 **AI-Generated Images**

The images were organized into separate folders and loaded using TensorFlow's `image_dataset_from_directory()` API for training, validation, and testing.

> **Note:** The dataset is not included in this repository due to copyright and storage limitations.


---

# 🔄 Project Workflow

```text
                Dataset
                   │
                   ▼
         Image Preprocessing
                   │
                   ▼
     image_dataset_from_directory()
                   │
                   ▼
        Train / Validation Split
                   │
                   ▼
            CNN Model Training
                   │
                   ▼
          Model Evaluation
                   │
                   ▼
        Save Trained Model (.keras)
                   │
                   ▼
        Predict New Image Class
```

---

# 🧠 Model Architecture

The project uses a **Convolutional Neural Network (CNN)** developed with TensorFlow/Keras for binary image classification.

The overall pipeline consists of:

- Convolutional layers for feature extraction
- Activation functions (ReLU)
- Pooling layers for dimensionality reduction
- Flatten layer to convert feature maps into vectors
- Dense (Fully Connected) layers for learning
- Output layer for binary classification (AI-generated vs Real)

The model is trained using TensorFlow's deep learning framework and evaluated on unseen images to measure its classification performance.


---

# ⚙️ Installation & Usage

## 1. Clone the Repository

```bash
git clone https://github.com/<YOUR_GITHUB_USERNAME>/AI-vs-Real-Image-Classifier.git
```

## 2. Navigate to the Project Folder

```bash
cd AI-vs-Real-Image-Classifier
```

## 3. Install Required Libraries

```bash
pip install -r requirements.txt
```

## 4. Open the Notebook

Launch Jupyter Notebook and open:

```text
Ai and real image prediction.ipynb
```

## 5. Run the Notebook

Execute the notebook cells in order to:

- Load the dataset
- Preprocess images
- Train the CNN model
- Evaluate the model
- Save the trained model
- Predict new images


---

# 📊 Results

The CNN model was successfully trained to classify images into two categories:

- 🟢 Real Images
- 🔴 AI-Generated Images

The project demonstrates the complete deep learning workflow, including:

- Image preprocessing
- Model training
- Model evaluation
- Prediction on unseen images

The trained model is capable of learning visual patterns from the dataset and performing binary image classification on new input images.


---

# 🚀 Future Improvements

The project can be enhanced with the following improvements:

- Implement Transfer Learning using pre-trained models such as ResNet50, EfficientNet, or MobileNet.
- Increase the size and diversity of the dataset for better generalization.
- Develop a web application using Streamlit or Flask for real-time image prediction.
- Deploy the trained model on cloud platforms such as Hugging Face Spaces, Render, or Streamlit Community Cloud.
- Add Explainable AI (XAI) techniques such as Grad-CAM to visualize the model's decision-making process.
- Perform hyperparameter tuning to further improve model performance.
- Extend the classifier to support multiple categories instead of binary classification.


---

# 📄 License

This project is licensed under the **MIT License**.

You are free to use, modify, and distribute this project for educational and research purposes.


---

# 🙏 Acknowledgements

This project was developed as part of my Deep Learning learning journey. I would like to acknowledge:

- TensorFlow/Keras for providing an excellent deep learning framework.
- The open-source Python community for the libraries used in this project.
- Publicly available image sources that were used to create the custom dataset.


---

# 👩‍💻 Author

**Khushi R**

🎓 B.Tech in Artificial Intelligence & Data Science

🔗 GitHub: https://github.com/<YOUR_GITHUB_USERNAME>

💼 LinkedIn: https://www.linkedin.com/in/<YOUR_LINKEDIN_USERNAME>/
