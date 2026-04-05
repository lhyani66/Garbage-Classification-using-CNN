# ♻️ Garbage Classification using CNN

## 📌 Project Description
This project uses a Convolutional Neural Network (CNN) to classify garbage images into different categories. The model is built using TensorFlow and Keras and trained on an image dataset with multiple classes.

## 🧠 Model
- Type: Convolutional Neural Network (CNN)
- Framework: TensorFlow / Keras
- Input size: 224 x 224 images
- Output: Multi-class classification (softmax)

## 📂 Dataset
The dataset should be organized in the following structure:

dataset/
  ├── class_1/
  ├── class_2/
  ├── class_3/
  └── ...

Each folder represents a class label.

## ⚙️ Installation

pip install tensorflow numpy matplotlib scikit-learn

## 🚀 How to Run

1. Prepare the dataset
2. Run the training script:

python train_model.py

## 📊 Evaluation
After training, the model shows:
- Accuracy score
- Classification report
- Confusion matrix
- Training vs validation graphs

## 📈 Results
The model is evaluated on validation data and performance metrics are displayed after training.

## ⚠️ Limitations
- Trained for a small number of epochs
- No transfer learning used
- Performance depends on dataset quality

## 🛠️ Tools Used
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Scikit-learn

## 👤 Author
Your Name
