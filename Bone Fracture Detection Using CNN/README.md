# Bone Fracture Detection Using X-rays

## Project Overview
This project is a **Bone Fracture Detection system** that identifies whether a bone is fractured or not using X-ray images. It provides a **user-friendly web interface** where users can upload an X-ray image and instantly receive the prediction.

The system leverages **machine learning / deep learning models** trained on a labeled dataset of X-ray images to accurately classify images as either “Fractured” or “Normal.”

---

## Dataset
The dataset used for this project is publicly available on Kaggle:  
[Bone Fracture Detection Dataset](https://www.kaggle.com/datasets/vuppalaadithyasairam/bone-fracture-detection-using-xrays?resource=download)  

- **Input:** X-ray images of bones  
- **Output labels:**  
  - `Fractured` – Image shows a bone fracture  
  - `Normal` – Image shows a healthy bone

---

## Features
- **Web Interface:** A simple webpage to upload X-ray images  
- **Instant Prediction:** Provides real-time classification of the uploaded image  
- **User-Friendly:** Minimal interface for easy interaction by medical professionals or patients  
- **Accurate:** Model trained on a large labeled dataset of bone X-ray images

---
## Input & Output
- **Input:** Single X-ray image (JPEG, PNG, or other standard formats)  
- **Output:** Text output on the webpage indicating if the bone is **Fractured** or **Normal**

---

## Technologies Used
- **Machine Learning / Deep Learning Frameworks:** TensorFlow / Keras / PyTorch  
- **Web Framework:** Flask / Django  
- **Data Preprocessing:** Image resizing, normalization, and augmentation  
- **Visualization:** Optionally, show uploaded image with prediction  

---

## Acknowledgements
- Dataset provided by [Adithya Sairam Vuppala on Kaggle](https://www.kaggle.com/datasets/vuppalaadithyasairam/bone-fracture-detection-using-xrays)  
- Open-source libraries like TensorFlow, Keras, PyTorch, and Flask for development and deployment


