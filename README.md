# 🩺 X-Ray Disease Prediction using CNN

## 📌 Overview

This project is a deep learning-based system that detects **pneumonia from chest X-ray images** using a Convolutional Neural Network (CNN). It helps in assisting medical professionals by providing fast and accurate predictions.

The model is trained on a large dataset of chest X-ray images and deployed using a Flask web application for real-time predictions.

---

## 🚀 Features

* Detects pneumonia from chest X-ray images
* Achieves **85–90% accuracy**
* Uses **CNN for automatic feature extraction**
* Includes **data augmentation** to improve generalization
* Real-time prediction using a **Flask web app**
* Integrated **medical chatbot (NLP-based)** for user queries

---

## 🛠️ Tech Stack

* **Programming Language:** Python
* **Libraries:** TensorFlow, Keras, NumPy, Pandas, Matplotlib
* **Deep Learning:** CNN (Convolutional Neural Network)
* **Web Framework:** Flask
* **NLP Tools:** NLTK / SpaCy (for chatbot)

---

## 📂 Project Structure

```
├── dataset/
├── model/
├── static/
├── templates/
├── app.py
├── train_model.py
├── requirements.txt
└── README.md
```

---

## ⚙️ How It Works

1. **Data Collection:** Chest X-ray images dataset
2. **Preprocessing:** Image resizing, normalization
3. **Data Augmentation:** Rotation, flipping, zooming
4. **Model Training:** CNN learns patterns from images
5. **Evaluation:** Accuracy and validation metrics
6. **Deployment:** Flask app for real-time predictions

---

## 📊 Model Performance

* Accuracy: **85–90%**
* Evaluation Metrics: Accuracy, Loss, Validation Score

---

## 🧠 CNN Architecture (Simplified)

* Convolution Layers → Feature Extraction
* Pooling Layers → Dimensionality Reduction
* Fully Connected Layers → Classification
* Output Layer → Pneumonia / Normal

---

## 💻 Installation & Setup

### 1. Clone the repository

```
git clone https://github.com/your-username/xray-disease-prediction.git
cd xray-disease-prediction
```

### 2. Install dependencies

```
pip install -r requirements.txt
```

### 3. Run the application

```
python app.py
```

### 4. Open in browser

```
http://127.0.0.1:5000/
```

---

## 📸 Usage

* Upload a chest X-ray image
* Click on **Predict**
* View prediction result (Pneumonia / Normal)

---

## 💡 Future Improvements

* Improve accuracy using advanced models (ResNet, EfficientNet)
* Deploy on cloud (AWS / Azure)
* Add multi-disease detection
* Enhance chatbot with LLMs

---

## 🎯 Applications

* Healthcare assistance
* Early disease detection
* Hospital automation systems

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repo and submit a pull request.

---

## 📬 Contact

**Nisha Kumari**
📧 Email: [nishalegend53@gmail.com](mailto:nishalegend53@gmail.com)
🔗 LinkedIn: https://linkedin.com/in/nishakumari19

---

⭐ If you found this project helpful, please give it a star!
