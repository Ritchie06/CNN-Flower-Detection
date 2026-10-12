# 🌸 Flower Image Classification using CNN

A deep learning project that classifies flower images into **five categories** using a Convolutional Neural Network (CNN) built with TensorFlow.

## 📌 About the Project

This project uses image processing and deep learning to identify flower types from images. The CNN learns visual patterns and features to predict the category of each flower.

## 🌼 Flower Categories

- Daisy
- Dandelion
- Roses
- Sunflowers
- Tulips

## 🛠️ Tech Stack

- **Language:** Python
- **Deep Learning:** TensorFlow
- **Model Utilities:** TF-Slim
- **Data Processing:** NumPy
- **Visualization:** Matplotlib
- **Environment:** Google Colab

## 🧠 Model Architecture

The CNN model consists of:

- Five convolutional layers with max-pooling
- Batch normalization
- Fully connected layers
- Dropout for regularization
- Softmax cross-entropy loss for classification
- Adam optimizer for training

## ⚙️ Workflow

1. Download and extract the flower dataset.
2. Parse and preprocess images from TFRecord files.
3. Resize images to 224 × 224 pixels.
4. Apply data augmentation to training images.
5. Train the CNN model for 35 epochs.
6. Evaluate predictions on validation images.
7. Visualize predicted and actual flower categories.

## 📊 Dataset

The project uses the TensorFlow flower dataset, containing images from five flower classes.

**Image size:** 224 × 224 pixels  
**Batch size:** 32  
**Training configuration:** 35 epochs, 100 steps per epoch

## 🚀 Getting Started

Run the project in Google Colab or another compatible Python environment.

Install the required libraries:

```bash
pip install tensorflow tf-slim numpy matplotlib
```

Download the dataset and run the notebook cells in sequence to preprocess the data, train the model, and visualize predictions.

> Note: The provided code uses TensorFlow 1.x compatibility mode and TFRecord files. Environment compatibility may require additional setup.

## 🎯 Key Learnings

- Understanding CNN architecture for image classification
- Image preprocessing and normalization
- Data augmentation techniques
- Model training and validation
- Visualizing predictions and evaluating classification performance

## 👩‍💻 Author

**Ritchie Tanya**

AI Engineer | Machine Learning | Generative AI

Interested in building practical AI solutions and exploring deep learning applications.

---

⭐ If you find this project interesting, feel free to explore the repository!
