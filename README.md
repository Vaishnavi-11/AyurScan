# 🌿 AyurScan - Indian Medicinal Leaf Detection System

**AyurScan** is a mobile application 📱 designed to automate the identification of medicinal leaves 🌱 used in Ayurvedic medicine. This app leverages **Machine Learning (ML)** 🤖 and **Deep Learning (DL)** 🧠 to classify and provide information about the leaves based on their physical characteristics, making Ayurvedic knowledge more accessible. Built using **Flutter** for the frontend, **Python** for the ML model, and **Google Firebase** for the database 🔥.

---

## 🛠️ Technology Stack

- **Frontend**: Flutter (for cross-platform mobile apps)
- **Backend**: Python (ML/DL models), Flask (server)
- **Database**: Google Firebase (plant data storage)

---

## 🧭 Overview

### 📖 Ayurveda and Medicinal Plants

“Ayurveda” is an ancient healing system that originated in India 🇮🇳 over 3,000 years ago. Over 90% of its remedies are plant-based 🌿. Due to India's rich biodiversity, it serves as a natural pharmacy for traditional medicine.

Identifying the correct plant species is crucial for effective treatment. Traditionally, this has required deep botanical knowledge and is a manual, time-consuming task ⏳.

### ⚠️ The Problem

Accurate identification of medicinal leaves is complex due to variations in **shape**, **color**, **size**, **texture**, and **venation**. Manual classification can be error-prone and resource-intensive.

### ✅ The Solution

**AyurScan** offers an AI-powered solution 🚀. By simply capturing an image of a leaf, users receive instant classification results along with medicinal information. This boosts accuracy and accessibility, especially for users with limited botanical expertise 👩‍⚕️👨‍🌾.

---

## 🧩 System Architecture

<img src="Snapshots/system_architecture.png" width="500">

---

## 🔍 How It Works

1. 📸 **Capture and Upload an Image** via the app.
2. 🧼 **Preprocessing** is done on the backend to extract features.
3. 🧠 **Classification** is performed using a trained ML model.
4. 📋 **Results and Info** are displayed to the user with medicinal details.

---

## 🧱 System Components

### 📲 Mobile Application (Flutter)

- User-friendly interface for capturing & uploading images.
- Communicates with backend for real-time classification.

### 🔙 Backend (Python + Flask)

- Handles image processing and classification.
- Interfaces with Firebase for relevant leaf data.

### 🤖 Machine Learning Model

- Built with **TensorFlow/Keras**.
- Trained on 1,500+ leaf images across 30 species.
- Detects features like **shape**, **color**, **texture**, and **size**.

### 🔥 Google Firebase

- Stores and serves medicinal leaf data.
- Ensures fast, scalable access to plant information.

---

## 📂 Dataset

We used the [Medicinal Leaf Dataset](https://data.mendeley.com/datasets/nnytj2v3n5/1), which contains:

- ✅ 1,500+ high-quality images
- ✅ 30 species of Indian medicinal plants
- ✅ 60–100 images per species

<img src="Snapshots/dataset.png" width="400">

---

## 📸 Screenshots

### 🧬 Feature Extraction

<img src="Snapshots/feature_extraction.png" width="400">

### ✨ Splash Screens

<table>
    <tr>
        <td>Splash Screen 1</td>
        <td>Splash Screen 2</td>
        <td>Splash Screen 3</td>
    </tr>
    <tr>
        <td><img src="Snapshots/splash_screen1.png" width="200"></td>
        <td><img src="Snapshots/splash_screen2.png" width="200"></td>
        <td><img src="Snapshots/splash_screen3.png" width="200"></td>
    </tr>
</table>

### 🏠 Main Screen

<table>
    <tr>
        <td>Upload Image</td>
    </tr>
    <tr>
        <td><img src="Snapshots/main_screen.png" width="200"></td>
    </tr>
</table>

### 🔎 Identification Result Screen

<table>
    <tr>
        <td>Prediction</td>
        <td>Prediction (contd.)</td>
    </tr>
    <tr>
        <td><img src="Snapshots/result1.png" width="200"></td>
        <td><img src="Snapshots/result2.png" width="200"></td>
    </tr>
</table>

---
