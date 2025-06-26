# 🧠 Brain Tumor Classification Using Deep Learning 

**Brain Tumor Classifier** is a deep learning-powered Flask application that detects and classifies brain tumors from MRI images. The project integrates convolutional neural networks (CNNs) with a clean web interface to assist in medical image diagnostics.

## 📌 Key Features

- 🧠 Classifies MRI images into tumor types using CNNs
- 🔁 Uses Transfer Learning (e.g., VGG19) for improved performance
- 📊 Shows prediction results in real-time
- 🧪 Trained with real MRI datasets
- 🌐 Flask-powered web interface for easy usage
- 📁 Saves flagged/predicted images for analysis

---
## 📹 Video Demo


https://github.com/user-attachments/assets/dbcd802d-eb44-4272-a0b8-8d109da94c25

---


## 📂 Project Structure

| File/Folder                                                       | Description                                                  |
|-------------------------------------------------------------------|--------------------------------------------------------------|
| 📁 `Brain-Tumor-Classification-Using-Deep-Learning/`              | Root project directory                                       |
| ├── `Advance DL Project Brain Tumor Image Classification.ipynb`  | Jupyter notebook for model training and evaluation           |
| ├── `archive.zip`                                                | MRI dataset archive                                          |
| ├── `README.md`                                                  | Project documentation                                        |
| ├── `LICENSE`                                                    | MIT License                                                  |
| ├── `.gitignore`                                                 | Files/folders ignored by Git                                 |
| 📁 `Brain Tumor Classification using DL/`                         | Flask app directory                                          |
| ├── `app.py`                                                     | Flask server script with upload & prediction routes          |
| ├── `flagged/image/`                                             | Stores uploaded and predicted images                         |
| 📁 `static/css/`                                                  | Static frontend CSS files (Bootstrap grid)                   |
| ├── `bootstrap-grid.css`                                         | Grid system for layout                                       |
| └── `bootstrap-grid.css.map`                                     | Source map for the grid CSS                                  |

---

## 🧱 Core Technologies

| Tool / Library       | Description                                              |
| -------------------- | -------------------------------------------------------- |
| **Python**           | Core programming language used across the project        |
| **Jupyter Notebook** | Interactive environment for training and evaluation      |
| **TensorFlow**       | Deep learning framework used for model building          |
| **Keras**            | High-level neural networks API for TensorFlow            |
| **OpenCV**           | Image processing library for handling MRI scans          |
| **Scikit-Learn**     | Machine learning utilities for metrics and preprocessing |
| **Pandas**           | Data manipulation and analysis                           |
| **NumPy**            | Numerical computing and array manipulation               |
| **Matplotlib**       | Visualization library used for plotting graphs           |
| **Flask**            | Lightweight web framework for serving the model          |
| **Bootstrap**        | CSS framework used for basic UI layout and styling       |


---

## 🧠 Model Workflow

1. Preprocess and augment MRI images (resize, normalize)
2. Use CNN with transfer learning (e.g., VGG19)
3. Train on labeled tumor categories
4. Evaluate using accuracy, confusion matrix
5. Serve model via Flask for real-time predictions

---

## 🧪 Sample Results

- Validation Accuracy: ~95%
- Tumor Types Detected:
  - Glioma
  - Meningioma
  - Pituitary Tumor
  - No Tumor

---

## 📸 Web App Interface

- Upload a brain MRI image (JPG, PNG)
- Get tumor prediction in seconds
- Download and flag the image for reference

---
 ##  🗂 Dataset
 
The dataset (archive.zip) includes MRI images for 4 tumor types. It is used for both training and testing. Make sure to extract and organize as needed.

---
 ## 📘 Sample Usage
Start the Flask server

Open the browser and navigate to http://localhost:5000

Upload an MRI scan

View prediction and save the result

---
 ## 📄 License
MIT License – you are free to use, modify, and share with proper attribution.

---

## 🙋 Author
Your: Sahil Mishra

GitHub: sahilmishra108

Email: sahilvatsa959@gmail.com

