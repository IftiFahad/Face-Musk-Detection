# 🩺 Face Mask Detection using MobileNetV2

This project is a **Face Mask Detection System** built using **TensorFlow (Keras)** and **MobileNetV2**.  
It classifies images into two categories:

- ✅ With Mask  
- ❌ Without Mask  

The model is trained on custom datasets (Train, Validation, Test) with **ImageDataGenerator** for augmentation, then fine-tuned using **MobileNetV2** pre-trained on ImageNet.

---

## 🚀 Features
- Pre-trained **MobileNetV2** for transfer learning
- Image augmentation for better generalization
- Real-time face mask classification
- Supports both:
  - Uploading local images
  - Providing image URLs
- Model saving and downloading as `.h5`

---

## 📂 Project Structure
├── facemask_model.h5 # Saved trained model
├── train/ # Training dataset
├── validation/ # Validation dataset
├── test/ # Test dataset
├── facemask_detection.ipynb # Main notebook (Google Colab)
└── README.md

🛠️ Tech Stack

Python

TensorFlow / Keras

MobileNetV2

Matplotlib

NumPy

Pillow

📌 Future Improvements

Real-time detection using OpenCV

Extend to multi-class detection (mask, no mask, improper mask)

Deploy as a web app using Flask / FastAPI

🙌 Acknowledgements

TensorFlow

Keras Applications

MobileNetV2 Pretrained Weights (ImageNet)

👤 Author

Iftikharul Fahad
📧 Email: iftifahad996@gmail.com

📍 Chattogram, Bangladesh
