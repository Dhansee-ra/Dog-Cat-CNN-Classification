# 🐶🐱 Dog and Cat Image Classification Using CNN

## 📌 Project Overview

This project focuses on developing a **Convolutional Neural Network (CNN)** for binary image classification to identify whether an input image contains a dog or a cat.

The model is built using TensorFlow and Keras with **three convolutional layers** to extract image features and classify images into two categories: Dog and Cat.

## 🎯 Objectives

- Develop a CNN model for image classification.
- Implement exactly three convolutional layers.
- Perform image preprocessing and augmentation.
- Train the model using a Dogs vs Cats dataset.
- Evaluate model performance using accuracy, loss, and a confusion matrix.
- Predict the category of new uploaded images.

## 🛠️ Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## 📂 Dataset

The project uses the Dogs vs Cats filtered dataset.

| Dataset | Cats | Dogs | Total |
|---|---:|---:|---:|
| Training | 1,000 | 1,000 | 2,000 |
| Validation | 500 | 500 | 1,000 |

**Image preprocessing:**
- Image resizing: 150 × 150 pixels
- Pixel normalization: 0–1
- Batch size: 32
- Data augmentation: Rotation, zooming, and horizontal flipping

## 🧠 CNN Architecture

The model consists of three convolutional layers.

| Layer | Configuration |
|---|---|
| Input | 150 × 150 × 3 |
| Conv2D Layer 1 | 32 filters, 3 × 3, ReLU |
| MaxPooling2D | 2 × 2 |
| Conv2D Layer 2 | 64 filters, 3 × 3, ReLU |
| MaxPooling2D | 2 × 2 |
| Conv2D Layer 3 | 128 filters, 3 × 3, ReLU |
| MaxPooling2D | 2 × 2 |
| Flatten | Feature conversion |
| Dense | 128 neurons, ReLU |
| Dropout | 0.5 |
| Output | 1 neuron, Sigmoid |

## ⚙️ Model Configuration

- Optimizer: Adam
- Loss Function: Binary Crossentropy
- Evaluation Metric: Accuracy
- Training Epochs: 15

## 🚀 How to Run the Project

1. Clone this repository:

   ```bash
   git clone https://github.com/YOUR-USERNAME/Dog-Cat-CNN-Classification.git
   ```

2. Open Google Colab.

3. Upload the notebook `Dog_Cat_CNN_Classification.ipynb`.

4. Select GPU runtime if available.

5. Run all notebook cells sequentially.

6. Upload a new dog or cat image to test the model.

## 📊 Model Evaluation

The model is evaluated using:

- Training and validation accuracy.
- Training and validation loss.
- Confusion matrix.
- Precision.
- Recall.
- F1-score.

## 🔍 Prediction

The trained model accepts a new image and predicts whether it belongs to the Dog or Cat category.

The output includes:
- Predicted class.
- Prediction confidence.

## 💾 Saved Model

The trained model is saved in Keras format:

`dog_cat_cnn_model.keras`

## 🔮 Future Enhancements

- Improve classification accuracy through hyperparameter tuning.
- Implement transfer learning using MobileNetV2.
- Develop a web application using Flask.
- Add a user-friendly image upload interface.
- Extend classification to multiple animal categories.

## 👨‍💻 Author

**Dhansheera Sadak**
kit28.24bcs031@gmail.com
Computer Science and Engineering Student

