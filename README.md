🤖 Hand Gesture Recognition Model
This project was developed as part of my internship at SkillCraft Technology. It is a deep learning-based hand gesture recognition system designed to identify and classify different hand gestures from image input, enabling intuitive and responsive human-computer interaction.

📌 Project Overview
This model detects and recognizes various hand gestures using a Convolutional Neural Network (CNN) trained on image data. It aims to contribute to real-time gesture-based control systems that can be used in areas like automation, gaming, virtual reality, and assistive technologies.

🔧 Technologies Used
Python

TensorFlow / Keras

OpenCV

CNN (Convolutional Neural Networks)

🎯 Features
Detects and classifies multiple hand gestures

Built with a custom-trained CNN model

Real-time recognition supported via OpenCV

Good accuracy on testing data

Easily extendable to new gestures or datasets

📁 Project Structure
css
Copy
Edit
├── Dataset/
│   └── [Training and Testing Images]
├── model/
│   └── gesture_model.h5
├── main.py
├── train_model.py
├── predict.py
├── README.md
└── requirements.txt
🚀 How to Run
Clone the repository

bash
Copy
Edit
git clone https://github.com/Anushkasai2006/SCT_ML_4.git
cd SCT_ML_4
Install required packages

bash
Copy
Edit
pip install -r requirements.txt
To Train the Model

bash
Copy
Edit
python train_model.py
To Run Gesture Recognition

bash
Copy
Edit
python main.py
📊 Sample Results
High classification accuracy on test data

