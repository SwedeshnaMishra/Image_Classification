# 🧠 AI-Powered Sports Celebrity Image Classification

This is an end-to-end **Machine Learning/Data Science** project that classifies images of sports celebrities using image processing and supervised learning techniques. The system uses **Python**, **Flask**, and a browser-based interface to allow users to upload images and get predictions via a trained model.

---

## 🚀 Project Overview

This project demonstrates how to build a complete machine learning pipeline for image classification, including:

- Data preprocessing using OpenCV and wavelet transformation
- Model training using `scikit-learn`
- Model deployment using `Flask`
- User interface with HTML, CSS, and JavaScript
- Local image prediction using webcam or file upload

---

## 📁 Folder Structure

```
Image_Classification/
│
├── model/
│   ├── sports_celebrity_classification.ipynb   # Model building and training notebook
│   ├── opencv/haarcascades/                    # Face detection models
│   ├── test_images/                            # Sample test images
│   └── requirements.txt                        # Python dependencies
│
├── server/
│   ├── artifacts/                              # Saved model and class dictionaries
│   ├── opencv/haarcascades/                    # Haarcascade XML files for face detection
│   ├── test_images/                            # Test images
│   ├── server.py                               # Flask backend API
│   ├── util.py                                 # Helper functions (wavelet, preprocessing, etc.)
│   └── wavelet.py                              # Custom wavelet transform code
│
├── UI/
│   ├── app.html                                # Web UI page
│   ├── app.css                                 # Styling
│   ├── app.js                                  # JS logic
│   ├── dropzone.min.css                        # Dropzone drag-and-drop support
│   └── dropzone.min.js                         # Dropzone logic
│
└── image dataset/                              # Dataset of sports celebrity images
```

---


## 🛠️ Technologies Used

### 🧮 Core Libraries:
- **Python**
- **NumPy** & **OpenCV** – for image preprocessing
- **Matplotlib** & **Seaborn** – for data visualization
- **scikit-learn** – for model training and evaluation

### 💻 Development:
- **Jupyter Notebook**
- **Visual Studio Code**
- **PyCharm**

### 🌐 Deployment:
- **Flask** – to serve the ML model as an HTTP API
- **HTML/CSS/JavaScript** – to build the user interface

---

## ✅ Features

- Real-time image classification of sports celebrities
- Automatic face detection using Haarcascade classifiers
- Wavelet transform-based feature extraction
- Interactive and modern drag-and-drop interface
- Flask-powered lightweight backend API

---

## 🔧 Installation & Running the Project

### 1. Clone the Repository

```bash
git clone https://github.com/SwedeshnaMishra/Image_Classification.git
cd Image_Classification
```

### 2. Create and Activate Virtual Environment (Optional but Recommended)

```bash
python -m venv venv
source venv/bin/activate
```

### 3. Install Required Dependencies

```bash
pip install -r model/requirements.txt
```

### 4. Run the Flask Server

```bash
cd server
python server.py
```

### 5. Open the UI

Open `UI/app.html` in your browser to interact with the system.

---

## 📷 Sample Workflow
- User uploads an image using the drag-and-drop UI.
- Flask server detects face using Haarcascade from OpenCV.
- Feature extraction is performed using wavelet transform.
- Trained model predicts the celebrity class.
- Prediction is returned and shown in the frontend.

---

📌 Celebrities Included
- Lionel Messi
- Maria Sharapova
- Roger Federer
- Serena Williams
- Virat Kohli

---

## For Contributing
If you want to contribute to this project, please follow these steps:
- `Fork` the repository.
- Create a new branch `(git checkout -b feature/your-feature-name)`.
- Make your changes and commit them `(git commit -m 'Add some feature')`.
- Push to the branch `(git push origin feature/your-feature-name)`.
- Open a pull request.

---

## Project Maintainer
**Github:** [Swedeshna Mishra](https://github.com/SwedeshnaMishra)
