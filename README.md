# 😷 Covid-19 Face Mask Detection

This project implements a real-time face mask detection system using a combination of traditional computer vision (Haar cascades) and deep learning (Convolutional Neural Networks). It enables automated identification of individuals wearing or not wearing face masks from webcam video streams, supporting health safety compliance in public spaces.

---

## 🎯 Objectives

- Detect faces in real-time video using OpenCV's Haar Cascade.
- Classify whether a person is wearing a mask or not using a trained CNN model.
- Provide a practical application for health and safety monitoring.

---

## 🧠 Core Components

- **`preprocessing.ipynb`**: Data preprocessing, augmentation, and preparation for model training.
- **`training.ipynb`**: CNN architecture design, compilation, and model training using labeled mask/no-mask images.
- **`maskdetect.ipynb`**: Real-time video stream analysis and mask detection using OpenCV.
- **`haarcascade_frontalface_default.xml`**: Face detection cascade used for region-of-interest extraction.

---

## 🖼️ Sample Output

![Sample](https://user-images.githubusercontent.com/your-image.png)

---

## 🛠️ Tech Stack

- Python, OpenCV
- TensorFlow / Keras (CNN)
- NumPy, Matplotlib
- Haar Cascades for face detection


---

## 📈 Results

- Achieved high accuracy on validation set for binary classification (mask vs. no mask).
- Real-time frame processing with minimal latency (~30 FPS).
- Clear bounding box color coding: Green (Mask), Red (No Mask).

---

## 🚀 How to Run

1. Clone the repo and install dependencies.
2. Run `training.ipynb` to train the model (or load existing weights).
3. Execute `maskdetect.ipynb` to start webcam-based mask detection.
4. Ensure your webcam is active and `haarcascade_frontalface_default.xml` is in the root directory.

---

## 🔒 Use Cases

- Health safety enforcement in offices, airports, and public buildings
- Automated surveillance and compliance monitoring


