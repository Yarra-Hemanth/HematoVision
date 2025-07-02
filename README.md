# HematoVision 🧬 | Blood Cell Classification Using Transfer Learning

HematoVision is a deep learning-powered solution designed to **accurately classify blood cells** using transfer learning techniques. Built on a dataset of 12,000 annotated images, the model distinguishes between four major types of blood cells: **eosinophils, lymphocytes, monocytes**, and **neutrophils**.

---

## 🔍 Overview

- 🎯 **Objective**: Build an efficient and scalable blood cell classification model using transfer learning with CNNs.
- 📊 **Dataset**: 12,000 labeled blood cell images from the [Kaggle Blood Cell Dataset](https://www.kaggle.com/datasets/paultimothymooney/blood-cells).
- 🔄 **Approach**: Pre-trained models (e.g., MobilenetV2) are fine-tuned to reduce training time and boost classification accuracy.

---

## 📂 Project Structure
HematoVision/  
├── app.py # Flask backend  
├── Blood cell.h5 # Trained Keras model  
├── requirements.txt # Required Python packages  
├── templates/  
│ ├── home.html # Upload interface  
│ └── result.html # Result display page  
├── static/ # Uploaded images (generated at runtime)  
└── README.md # Project documentation  


---

## 🚀 How to Run in Google Colab

> ✅ Tip: Use [Google Drive integration](https://colab.research.google.com/) to persist your files.

1. **Install dependencies**  
   !pip install flask-ngrok tensorflow
Upload model and HTML templates

Upload Blood cell.h5, home.html, result.html

Run Flask with ngrok
!python app.py
Open the ngrok URL to test your app live!

🧠 Scenarios of Application
📌 Scenario 1: Automated Diagnostic Systems
Integrate with clinical workflows

Real-time classification and reporting

Reduces manual effort, enhances diagnostic speed

🌐 Scenario 2: Remote Medical Consultations
Upload blood images through telemedicine platforms

Automated backend classification ensures timely expert analysis

🎓 Scenario 3: Educational Tools for Medical Training
Use as a training assistant for students and lab technicians

Interactive blood cell recognition with instant feedback

🛠️ Tech Stack
Frontend: HTML, Bootstrap (optional)

Backend: Flask + Flask-ngrok

Model: Keras/TensorFlow with Transfer Learning (e.g., MobilenetV2)

Deployment: Google Colab (for testing), Flask-ngrok for live preview

📌 Requirements
Install via pip:

pip install -r requirements.txt

Contents of requirements.txt:
ngrok
flask
flask-ngrok
tensorflow
numpy
Pillow
📷 Sample Output
A blood cell image is uploaded through the web app, and the predicted class is displayed with high accuracy using the trained CNN model.

Demo:
You can also see the demo: [Click Here.](https://drive.google.com/file/d/1RO9iZyOlyghhoRg4wUB5qBCFuJB9jUyT/view)
Check out the live implementation at the end of the Video.

🤝 Contributions
Feel free to fork, open issues, or submit pull requests to contribute to HematoVision.

📜 License
This project is licensed under the MIT License. See LICENSE for more details.

📫 Contact
Hemanth Yarra
LinkedIn | hemanthyarra@gmail.com

Let me know if you'd like a version with badges, screenshots, or setup for GitHub Pages.
