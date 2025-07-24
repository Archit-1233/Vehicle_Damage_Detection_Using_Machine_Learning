# 🚗 YOLOv8 Vehicle Damage Detection System

> A real-time deep learning-based system that detects **scratches**, **dents**, and **broken parts** in vehicle images using a custom-trained YOLOv8 object detection model.

---


### 🎯 Highlights

- ✅ **63% Precision** achieved on custom real-world vehicle damage dataset  
- 🔍 Detects **Scratches**, **Dents**, and **Broken Parts**  
- 📷 Real-time inference on **images**, **videos**, and **live webcam feed**  
- 🧪 Fully **customizable** to detect new damage categories  
- 📊 Evaluates model with **Precision**, **Recall**, and **mAP**

---

## 📌 Project Overview

This system is designed to support:

- 🚘 **Insurance companies** for automated damage assessment  
- 🛠️ **Car service centers** for quick inspection reports  
- 🧾 **Vehicle rental agencies** to track vehicle condition before & after use

---

## 🧠 Features

- 📸 **Real-time damage detection** using YOLOv8
- 🔁 Live camera feed / video / image support
- 📊 Model performance tracking: **Precision**, **Recall**, **mAP**
- 🎯 Detects 3 types of damages:  
  - 🔧 Scratch  
  - 🔨 Dent  
  - 🧱 Broken Part  
- 🧬 Supports model **retraining** and **fine-tuning** with your own dataset
- ⚙️ Built for **Colab**, **Jupyter**, and **local systems**

---

## 🛠️ Tech Stack

| Component     | Details                                     |
|---------------|---------------------------------------------|
| **Model**     | YOLOv8 (Ultralytics)                        |
| **Language**  | Python                                      |
| **Libraries** | `ultralytics`, `OpenCV`, `PyTorch`, `NumPy`, `Matplotlib` |
| **Annotation**| Roboflow / CVAT                             |
| **Environment** | Google Colab / Jupyter Notebook / Local   |

---

## 🗂 Dataset

Custom-annotated dataset using **Roboflow**, with following labels:

- 🔧 **Scratch**
- 🔨 **Dent**
- 🧱 **Broken Part**

⚠️ **Note**: The dataset was **imbalanced**, so data augmentation and hyperparameter tuning were applied during training.

---

## 📊 Results

| Metric       | Value  |
|--------------|--------|
| Precision    | 63%    |
| Recall       | *TBD*  |
| mAP@0.5      | *TBD*  |

---

## 🖼️ Sample Results

### 🔹 Input Image
<img src="images/sample_input.jpg" alt="Input Image" width="500"/>

### 🔸 YOLOv8 Detection Output
<img src="images/sample_output.jpg" alt="Detection Output" width="500"/>

| Input | Output |
|-------|--------|
| ![](images/img1_input.jpg) | ![](images/img1_output.jpg) |
| ![](images/img2_input.jpg) | ![](images/img2_output.jpg) |

> 💡 _Add as many input/output pairs as needed. Keep them in `images/` folder._

---

## 🚀 Getting Started

### 🔧 1. Clone the Repository

```bash
git clone https://github.com/your-username/vehicle-damage-detection.git
cd vehicle-damage-detection
