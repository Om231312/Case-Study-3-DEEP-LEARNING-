# 🧠 Brain Tumor Detection using CNN

<p align="center">
A Deep Learning project that detects brain tumors from MRI images using a Convolutional Neural Network (CNN).
</p>

---

## 📌 Project Overview

```text
This project uses a Convolutional Neural Network (CNN) to detect
whether a brain MRI image contains a tumor or not.

The model learns important visual patterns from MRI scans
and classifies images into two categories:
Tumor or No Tumor.
```

Brain tumor detection using deep learning helps doctors in **early diagnosis and medical image analysis**.

---

## 📂 Dataset Information

```text
Dataset Type : Brain MRI Images
Total Images : Varies depending on dataset
Image Type : MRI Scan Images
Classes : 2
```

### Classes

```text
1. Tumor
2. No Tumor
```

Each image is an **MRI scan of the brain** used to train the CNN model.

---

## ⚙️ Technologies Used

```text
✔ Python
✔ TensorFlow / Keras
✔ NumPy
✔ OpenCV
✔ Matplotlib
✔ Scikit-Learn
```

---

## 🧠 CNN Model Architecture

```text
Input Layer
MRI Image
        ↓

Convolution Layer
Extracts features like edges and patterns
        ↓

ReLU Activation
Introduces non-linearity
        ↓

Max Pooling Layer
Reduces feature map size
        ↓

Multiple Convolution + Pooling Layers
Learn deeper image features
        ↓

Flatten Layer
Converts feature maps into vector
        ↓

Dense Layer
Fully connected neural network
        ↓

Output Layer
Binary Classification
(Tumor / No Tumor)
Activation : Sigmoid
```

---

## 🔄 Project Workflow

```text
1️⃣ Load MRI image dataset
2️⃣ Resize images for model input
3️⃣ Normalize pixel values
4️⃣ Split dataset into training and testing sets
5️⃣ Build CNN architecture
6️⃣ Train the model using epochs
7️⃣ Evaluate model accuracy
8️⃣ Predict tumor presence
```

---

## 🧪 Model Training Example

```python
model.fit(
    X_train,
    y_train,
    epochs=20,
    batch_size=32,
    validation_data=(X_test, y_test)
)
```

### What is an Epoch?

```text
Epoch = One complete pass of the training dataset
through the neural network.
```

Example:

```text
Epoch 1 → Model learns basic patterns
Epoch 10 → Model improves prediction ability
Epoch 20 → Model achieves higher accuracy
```

---

## 📊 Model Performance

```text
Training Accuracy : ~95%
Testing Accuracy  : ~90–94%
Loss Function     : Binary Crossentropy
Optimizer         : Adam
```

CNN performs well for medical images because it can **identify complex patterns in MRI scans**.

---

## 📁 Project Structure

```text
Brain-Tumor-Detection-CNN
│
├── dataset
├── train_model.py
├── cnn_model.py
├── predict_image.py
├── requirements.txt
└── README.md
```

---

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/brain-tumor-detection-cnn.git
```

### 2️⃣ Install Dependencies

```bash
pip install tensorflow numpy opencv-python matplotlib scikit-learn
```

### 3️⃣ Train the Model

```bash
python train_model.py
```

### 4️⃣ Predict MRI Image

```bash
python predict_image.py
```

---

## 🎯 Applications

```text
✔ Medical image analysis
✔ Early brain tumor detection
✔ AI-assisted healthcare systems
✔ Radiology support tools
✔ Hospital diagnostic systems
```

---

## 👨‍💻 Author

```text
Name : Om Prakash Kannaujiya
GitHub : https://github.com/yourusername
```

---

⭐ If you like this project, consider giving it a **Star ⭐ on GitHub**.
