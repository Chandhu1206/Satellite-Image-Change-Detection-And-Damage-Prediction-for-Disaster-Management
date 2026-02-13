🌍 Satellite Image Change Detection and Damage Prediction for Disaster Management
📌 Overview

This project focuses on detecting changes in satellite images before and after disasters (floods, earthquakes, etc.) and predicting damage using deep learning techniques.

The system compares multi-temporal satellite images to identify structural and environmental changes.

🎯 Objectives

Detect changes between pre-disaster and post-disaster satellite images

Classify damaged and non-damaged regions

Assist disaster management teams in rapid assessment

🛰 Dataset

Dataset used: Onera Satellite Change Detection Dataset (OSCD)

🔗 Download here:
https://ieee-dataport.org/open-access/oscd-onera-satellite-change-detection

⚠ Dataset is not included in this repository due to size limitations.

After downloading, place it inside:

data/

🧠 Model Used

Convolutional Neural Network (CNN)

Image segmentation techniques

Binary classification for change detection

🛠 Tech Stack

Python

PyTorch / TensorFlow

OpenCV

NumPy

Matplotlib

▶ How to Run

Clone repository:

git clone https://github.com/Chandhu1206/Satellite-Image-Change-Detection-And-Damage-Prediction-for-Disaster-Management.git


Install dependencies:

pip install -r requirements.txt


Run training:

python src/train.py

📊 Results

The model successfully detects changed regions between temporal satellite images and highlights potential damage zones.

🚀 Future Improvements

Use UNet architecture

Integrate real-time disaster APIs

Deploy as web application

👤 Author

Chandhu
