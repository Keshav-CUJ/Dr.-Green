# 🌱 Plant Disease Detection (Tomato) 🍅

## 📌 Overview
Our project aims to develop a **mobile and web-based application** that detects **plant diseases** in real-time, primarily focusing on **tomatoes**. The system utilizes **Machine Learning (ML) and Deep Learning (DL) algorithms** to predict diseases and suggest **preventive measures and treatments**.

## 🔍 Features we will provide
- 📸 **Image-Based Disease Detection**: Users can upload images of tomato leaves, and the model will classify potential diseases.
- 🌡 **Environmental Data Integration**: The model also considers **temperature, humidity, and location**.
- 🗂 **Advanced ML & DL Processing**: Utilizes state-of-the-art **CNNs, feature extraction, and classification techniques**.
- 🏥 **Disease Prevention & Treatment Suggestions**: Provides actionable insights for farmers and agriculturists.
- 🤖 **AI-Powered Chatbot**: Offers general agricultural assistance and answers queries.
- 🔄 **Continuous Learning**: Feedback loop for improving model performance over time.

## 🏗 System Architecture
![System Architecture](./Introduction/Screenshot%202025-04-01%20142754.png)

### 🔹 How It Works:
1. **User uploads images** of tomato leaves (2-3 images from different angles).
2. **Preprocessing**: Images are segmented, enhanced, and passed to the ML model.
3. **Feature Extraction**: Extracts low and deep-level features from images and environmental data.
4. **Classification**: Predicts the disease using an optimized **Artificial Neural Network (ANN)**.
5. **Results & Recommendations**: The model provides disease classification, preventive measures, and treatments.
6. **Feedback Mechanism**: Users can provide feedback to refine predictions and improve accuracy.

## 🛠 Technical Approach
![Technical Approach](./Introduction/Screenshot%202025-04-01%20144312.png)

### 📂 Datasets
- **PlantVillage**: Contains **54,000 images** of 14 crops and 38 disease classes.
- **CCMT & PlantDoc**: Real-world images used for meta-learning and model generalization.
- **Custom Dataset**: Web-scraped and manually labeled images to overcome real-time data challenges.

### 🖥 Preprocessing
- **Denoising**
- **Bias Field Correction**
- **Sharpening & Edge Detection**
- **Contrast & Brightness Enhancement**
- **Image Normalization & Augmentation**

### 🏷 Classification & Feature Extraction
- **Deep Learning Models**: Fine-tuned **VGG19, InceptionV3, and DenseNet201**.
- **Segmentation**: Multi-class segmentation masks.
- **Feature Extraction & Ensembling**: Combining **ML and DL** approaches for feature fusion.
- **Weight Optimization**: Assigns optimized weights based on crop type.

### 🌐 Libraries, Models and tech
| Category        | Libraries, Models|
|---------------|-----------------|
| **Image enhancement** | Pytorch, OpenCV, REDNet|
| **Segmentation** | UNet|
| **Feature extraction** | Tensorflow, VGG16, InceptionV3 |
| **Training** | ANN, Nature Inspired algorithms |


## 📌 Future Enhancements
- **Expand dataset** for other plant species.
- **Integrate IoT sensors** for real-time environmental monitoring.
- **Offline Model Deployment** for remote areas with low internet access.

## 🤝 Contributing
We welcome contributions! Feel free to:
- Fork the repository 🍴
- Create a new branch 🌿
- Submit a pull request 🔥

## 📞 Contact
For inquiries, collaborations, or suggestions, reach out via **bkeshav218@gmail.com**.

---
🌿 _Revolutionizing plant disease detection with AI & ML!_ 🚀

