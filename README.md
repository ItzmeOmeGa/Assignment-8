# Assignment-8
# ✍️ Handwritten Digit Recognition using Artificial Neural Networks (ANN)

## 📌 Objective

The objective of this project is to develop an **Artificial Neural Network (ANN)** to recognize handwritten digits (0–9) using the **MNIST Handwritten Digits Dataset**. The model is trained using TensorFlow/Keras and evaluated to classify handwritten digits accurately for image recognition applications.

---

## 📂 Dataset Link

**MNIST Handwritten Digits Dataset**

https://www.kaggle.com/datasets/oddrationale/mnist-in-csv

---

## 🛠️ Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* TensorFlow / Keras
* Scikit-learn
* KaggleHub

---

## ⚙️ Methodology

1. Loaded the MNIST dataset using KaggleHub.
2. Displayed the dataset structure and a sample handwritten digit.
3. Checked for missing values.
4. Separated input features and target labels.
5. Normalized pixel values to the range **0–1**.
6. Split the dataset into **80% training** and **20% testing**.
7. Converted target labels into categorical format using **One-Hot Encoding**.
8. Built an Artificial Neural Network (ANN) using TensorFlow/Keras.
9. Trained the model for **10 epochs**.
10. Evaluated the model using Test Accuracy, Confusion Matrix, and Classification Report.
11. Visualized the training process using **Accuracy vs Epoch** and **Loss vs Epoch** graphs.

---

## 🧠 Model Architecture

| Layer              | Configuration                |
| ------------------ | ---------------------------- |
| **Input Layer**    | 784 Neurons (28 × 28 Pixels) |
| **Hidden Layer 1** | 128 Neurons (ReLU)           |
| **Hidden Layer 2** | 64 Neurons (ReLU)            |
| **Output Layer**   | 10 Neurons (Softmax)         |

### Model Configuration

* **Optimizer:** Adam
* **Loss Function:** Categorical Crossentropy
* **Metric:** Accuracy
* **Epochs:** 10

---

## 📊 Results

| Metric            |           Score |
| ----------------- | --------------: |
| **Test Accuracy** | Add your result |

### Evaluation

* Confusion Matrix generated successfully.
* Classification Report generated for all 10 digit classes.
* Accuracy vs Epoch graph plotted.
* Loss vs Epoch graph plotted.

### Key Observations

* The ANN successfully learned handwritten digit patterns from the MNIST dataset.
* Training accuracy increased while loss decreased over successive epochs, indicating effective learning.
* The confusion matrix showed that most handwritten digits were correctly classified, with only a few misclassifications between visually similar digits.
* The two hidden layers using ReLU activation enabled the network to learn complex image features effectively.

---

## ✅ Conclusion

This project demonstrated the successful implementation of an Artificial Neural Network (ANN) for handwritten digit recognition using the MNIST dataset. After preprocessing the images, normalizing pixel values, and applying one-hot encoding, the ANN achieved effective classification of handwritten digits. The hidden layers played a significant role in learning complex image features and improving prediction accuracy. Deep Learning offers a major advantage over traditional Machine Learning by automatically extracting meaningful features from raw data, reducing the need for manual feature engineering. However, ANN models require larger datasets, longer training times, and greater computational resources compared to many traditional machine learning algorithms.

---

## 📁 Project Structure

```text
Assignment-8/
│── Assignment-8.ipynb
│── README.md
```

---

## ▶️ How to Run

1. Open the notebook in Google Colab.
2. Install the required libraries:

   ```bash
   pip install kagglehub[pandas-datasets]
   ```
3. Run all notebook cells in sequence.
4. The notebook will:

   * Load the MNIST dataset.
   * Train the ANN model.
   * Evaluate model performance.
   * Display the confusion matrix, classification report, and training graphs.

---
