# ♻️ Smart Waste Image Classification Using Deep Learning

## 📌 Project Overview
Smart Waste Image Classification is a Deep Learning project that automatically identifies and classifies waste materials using images. It uses CNN and MobileNetV2 to predict waste categories and helps improve waste segregation and recycling.

## 🎯 Objectives
- Automatically classify waste images.
- Reduce manual waste sorting.
- Support recycling and proper waste management.
- Build an easy-to-use image prediction application.

## 📂 Dataset
**Garbage Classification V2 Dataset**

The dataset contains images of different waste materials, organized into category folders.

## 🗂️ Waste Categories
- Cardboard
- Glass
- Metal
- Paper
- Plastic
- Trash

*The actual categories depend on the dataset folders used for training.*

## 🛠️ Technologies Used
- Python
- TensorFlow
- Keras
- CNN (Convolutional Neural Network)
- MobileNetV2
- NumPy
- Matplotlib
- Gradio
- Google Colab / Jupyter Notebook

## ⚙️ Project Workflow
1. Load the Garbage Classification V2 dataset.
2. Preprocess and resize images to 224 × 224.
3. Apply data augmentation.
4. Build a CNN model using MobileNetV2.
5. Train the deep learning model.
6. Evaluate model accuracy and loss.
7. Save the trained model.
8. Develop a Gradio application for image prediction.

## 🧠 Model Architecture
The project uses MobileNetV2 with additional CNN layers, MaxPooling, Global Average Pooling, Dense layers, and Dropout for image classification.

**Optimizer:** Adam

**Learning Rate:** 0.0001

**Loss Function:** Sparse Categorical Crossentropy

**Evaluation Metric:** Accuracy

## 🚀 Application Features
- Upload waste images.
- Automatically predict waste categories.
- Display prediction confidence.
- Simple and user-friendly Gradio interface.

## 📊 Model Evaluation
The model is evaluated using:
- Training Accuracy
- Validation Accuracy
- Training Loss
- Validation Loss

## 🔮 Future Enhancements
- Real-time waste detection using cameras.
- Smart waste bin integration.
- IoT-based waste monitoring.
- Automated waste segregation.
- Mobile application deployment.

## 🌍 Conclusion
Smart Waste Image Classification demonstrates how Artificial Intelligence and Deep Learning can help solve real-world waste management problems. The system aims to encourage recycling, improve waste segregation, and support a cleaner and more sustainable environment.

## 👨‍💻 Project Type
Deep Learning | Computer Vision | Image Classification | Environmental Sustainability
