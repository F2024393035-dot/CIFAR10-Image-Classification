# CIFAR-10 Image Classification
This project demonstrates how to classify images into 10 categories using a Convolutional Neural Network (CNN) on the CIFAR-10 dataset.
## 🧠 Project Goal
To build and train a CNN that can accurately classify images from the CIFAR-10 dataset, including classes like airplanes, cars, birds, cats, and more.
## 📦 Dataset
- CIFAR-10 dataset from Keras datasets
- 60,000 32x32 color images in 10 classes (6,000 images per class)

## 🛠️ Tools Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Jupyter Notebook
## 🚀 Features
- Data normalization and visualization
- CNN architecture: Conv2D, MaxPooling, Dropout, BatchNormalization
- EarlyStopping and Learning Rate Scheduler
- Achieved ~89% accuracy on the test set
## 📁 Files

- `cifar10_classification.ipynb`: Full notebook with training and evaluation
- `model_summary.png`: CNN architecture (if added)
- `README.md`: Project details
## 🔗 How to Run
`bash
pip install -r requirements.txt
python cifar10_classification.ipynb

