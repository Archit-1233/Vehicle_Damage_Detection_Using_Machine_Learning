# 🚗 YOLOv8 Vehicle Damage Detection System

> A real-time deep learning-based system that detects **scratches**, **dents**, and **broken parts** in vehicle images using a custom-trained YOLOv8 object detection model.

---
## Result - 01
<img width="1024" height="683" alt="image" src="https://github.com/user-attachments/assets/611acd84-24e9-4c06-871e-f577a34ec89d" />

## Result -02

<img width="882" height="579" alt="image" src="https://github.com/user-attachments/assets/7eecaad1-0a0a-4dc6-ab4b-99fa6209eb16" />

## Result -03
<img width="600" height="401" alt="image" src="https://github.com/user-attachments/assets/2a63b8ff-b6fc-4462-a76c-eff667db2fcd" />

## Result - 04
<img width="1300" height="956" alt="image" src="https://github.com/user-attachments/assets/7b671599-0726-4ce9-b8c4-8fb7d66c1822" />




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
<img width="1003" height="268" alt="image" src="https://github.com/user-attachments/assets/fa63d3d9-43ee-4f29-a1a3-9f35be4b480c" />


<img width="956" height="321" alt="image" src="https://github.com/user-attachments/assets/760db6a8-0930-4b8c-a8f6-e3ebbaff85c8" />


<img width="964" height="132" alt="image" src="https://github.com/user-attachments/assets/56861e6f-3e9e-4485-91a7-11034c202d13" />




| Metric       | Value  |
|--------------|--------|
| Precision    | 63%    |
| Recall       | 53%  |
| mAP@0.5      | 0.524  |

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
