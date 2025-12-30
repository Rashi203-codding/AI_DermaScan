🧬 DermalScan: AI Facial Skin Aging Detection App

DermalScan is an AI-powered facial skin analysis application that detects and classifies visible skin aging signs such as wrinkles, dark spots, puffy eyes, and clear skin using deep learning.
It leverages EfficientNetB0, OpenCV face detection, and a web-based interface to provide accurate, percentage-based predictions with visual annotations.

🚀 Project Overview

1.The goal of DermalScan is to build an end-to-end deep learning pipeline that:

2.Detects faces from uploaded images

3.Identifies skin aging signs

4.Classifies detected regions into predefined categories

5.Displays predictions with bounding boxes and confidence percentages

6.Allows users to export annotated images and prediction logs

7.This project combines computer vision, deep learning, and web deployment into a single practical application.

🎯 Key Features

✅ Face detection using Haar Cascade Classifier

✅ Skin aging classification using EfficientNetB0

✅ Categories supported:

Wrinkles

Dark Spots

Puffy Eyes

Clear Skin

✅ Percentage-based prediction confidence

✅ Annotated bounding boxes on facial regions

✅ Web-based image upload and visualization

✅ Downloadable CSV logs and annotated outputs

🧠 Tech Stack
Area	Tools & Libraries


Image Processing	OpenCV, NumPy
Deep Learning	TensorFlow, Keras
Model	EfficientNetB0 (Transfer Learning)
Dataset	Labeled facial skin images
Frontend	GRADIO / HTML / CSS
Backend	Python (Modular Inference Pipeline)
Evaluation	Accuracy, Loss, Confusion Matrix
Export	CSV, Annotated Images
 
🧪 Model Training Details

Input size: 224 × 224

Architecture: EfficientNetB0 (pretrained on ImageNet)

Loss Function: Categorical Cross-Entropy

Optimizer: Adam

Evaluation Metrics: Accuracy & Loss

Target Accuracy: ≥ 90%

🔍 Workflow

User uploads a facial image

Face is detected using Haar Cascade

Detected face is preprocessed and resized

EfficientNetB0 predicts skin aging category

Output displayed with:

Bounding boxes

Labels

Confidence percentages

User can download:

Annotated image

CSV prediction logs

 

📊 Output Samples

Annotated facial images with bounding boxes

Percentage-based skin aging predictions

CSV logs for further analysis or reporting

📈 Evaluation Criteria

✔ Balanced and clean dataset

✔ Stable validation accuracy

✔ Fast inference time (≤ 5 seconds per image)

✔ Clean UI and export functionality

✔ Well-structured documentation

🔮 Future Enhancements

Add real-time webcam analysis

Improve localization using facial landmarks

Add skin care recommendation engine

Deploy using cloud services (AWS / GCP)

Mobile-friendly UI

🤝 Contribution

Contributions, suggestions, and improvements are welcome.
Feel free to fork the repository and submit a pull request.

📜 License

This project is for educational and research purposes.
