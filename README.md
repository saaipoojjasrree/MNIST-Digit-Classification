# MNIST Handwritten Digit Classification using CNN

## 📌 Project Overview

This project implements a **Convolutional Neural Network (CNN)** using **TensorFlow and Keras** to classify handwritten digits (0–9) from the MNIST dataset. The model is trained to recognize digit images with high accuracy and demonstrates the application of deep learning in image classification.

---

## 🎯 Objective

* Build a CNN model for handwritten digit recognition.
* Train and evaluate the model using the MNIST dataset.
* Visualize model performance and save the trained model for future use.

---

## 📂 Dataset

The project uses the **MNIST Handwritten Digit Dataset**, which contains:

* **60,000** training images
* **10,000** testing images
* Image size: **28 × 28 pixels**
* **10 classes** representing digits **0–9**

---

## 🛠️ Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* Jupyter Notebook
* Visual Studio Code

---

## 🧠 Model Architecture

The CNN model consists of:

* Conv2D Layer (32 filters, ReLU)
* MaxPooling2D Layer
* Conv2D Layer (64 filters, ReLU)
* MaxPooling2D Layer
* Flatten Layer
* Dense Layer (128 neurons, ReLU)
* Output Layer (10 neurons, Softmax)

---

## 📊 Results

* Training Accuracy: **~99.5%**
* Validation Accuracy: **~99%**
* High performance in recognizing handwritten digits.

---

## 📁 Project Structure

```text
Task2_Deep_Learning/
│
├── dataset/
├── notebook/
│   └── mnist_digit_classification.ipynb
├── model/
│   └── mnist_cnn_model.keras
├── report/
│   └── report.docx
├── screenshots/
└── README.md
```

---

## 🚀 How to Run

1. Clone or download the project.
2. Install the required libraries:

```bash
pip install tensorflow matplotlib numpy
```

3. Open the Jupyter Notebook.
4. Run all cells in sequence.
5. Train the CNN model and evaluate its performance.
6. Save the trained model.

---

## 📈 Future Improvements

* Train for more epochs.
* Apply data augmentation techniques.
* Experiment with deeper CNN architectures.
* Deploy the model as a web application.

---

## 👨‍💻 Author

Saai Poojja Srree


Developed as part of an **AI Internship Program** to gain practical experience in **Deep Learning, Computer Vision, and Image Classification** using TensorFlow and Keras.
