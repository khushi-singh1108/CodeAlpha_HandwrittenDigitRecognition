# CodeAlpha - Handwritten Digit Recognition

This project is part of the **CodeAlpha Machine Learning Internship**.

## 📌 Project Overview
This project uses a **Convolutional Neural Network (CNN)** to recognize handwritten digits (0–9) from the **MNIST dataset**.  
It demonstrates image preprocessing, deep learning model building, training, and prediction.

---

## 🧠 Dataset Information
- Dataset: **MNIST** (Keras built-in)
- 60,000 training images  
- 10,000 test images  
- Image size: 28x28 pixels  
- Color mode: Grayscale  

---

## 🏗️ Project Workflow
1. Loaded MNIST dataset  
2. Normalized pixel values (0–1)  
3. Reshaped images for CNN input  
4. Built CNN model with:
   - Conv2D  
   - MaxPooling  
   - Flatten  
   - Dense layers  
5. Trained for **5 epochs**  
6. Evaluated model accuracy  
7. Predicted a sample digit  

---

## ✅ Results
- **Test Accuracy:** ~98%  
- Model successfully predicted handwritten digits  
- Smooth training & validation loss curves  

---

## 📸 Output Screenshots
All output screenshots are available inside the **`outputs/`** folder:
- Training vs Validation Loss Graph  
- Sample Test Image  
- Predicted Digit  
- Test Accuracy Line  

---

## ▶ How to Run This Project
1. Open the notebook:  
   **`CodeAlpha_HandwrittenDigitRecognition.ipynb`**
2. Run it on **Google Colab**  
3. Click **Runtime → Run all**  
4. View:
   - Accuracy  
   - Graph  
   - Predicted digit  

---

## 🛠️ Technologies Used
- Python  
- Google Colab  
- TensorFlow / Keras  
- NumPy  
- Matplotlib  

---

## 📃 Author
**Khushi Singh**  
Machine Learning Intern – CodeAlpha
