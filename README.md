🚗 YOLOv8 Vehicle Damage Detection System
A real-time deep learning-based system that detects scratches, dents, and broken parts in vehicle images using a custom-trained YOLOv8 object detection model.



🎯 Achieved 63% precision on a custom dataset with real-world vehicle damage annotations.

📌 Project Overview
This project aims to assist insurance companies, car rental agencies, and vehicle inspection services by automating the detection of external vehicle damage.

🧠 Features
🔍 Detects Scratches, Dents, and Broken Parts

📷 Real-time inference on images, videos, and live webcam

📊 Tracks performance via Precision, Recall, and mAP

🧪 Fully customizable for new damage types

🛠️ Tech Stack
Model: YOLOv8 (Ultralytics)

Language: Python

Libraries: ultralytics, OpenCV, PyTorch, NumPy, Matplotlib

Environment: Google Colab / Jupyter Notebook / Local Machine

Dataset: Custom-annotated using Roboflow or CVAT

🗂 Dataset
A custom dataset consisting of vehicle images annotated with the following labels:

🔧 Scratch

🔨 Dent

🧱 Broken Parts

⚠️ Note: The dataset was imbalanced, so data augmentation and tuning were applied during training.

📊 Results
Metric	Value
Precision	63%
Recall	TBD
mAP@0.5	TBD

🖼️ Sample Results
🔹 Input Image:
<img src="images/sample_input.jpg" alt="Input Image" width="500"/>
🔸 YOLOv8 Detection Output:
<img src="images/sample_output.jpg" alt="Detection Result" width="500"/>
Above: The model detects scratches, dents, and broken parts accurately in real-time.

Add more results as needed:

markdown
Copy
Edit
| Input | Output |
|-------|--------|
| ![](images/img1_input.jpg) | ![](images/img1_output.jpg) |
| ![](images/img2_input.jpg) | ![](images/img2_output.jpg) |
🚀 Getting Started
🔧 1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/your-username/vehicle-damage-detection.git
cd vehicle-damage-detection
📦 2. Install Requirements
bash
Copy
Edit
pip install -r requirements.txt
🏋️ 3. Train the Model (Optional)
bash
Copy
Edit
yolo task=detect mode=train model=yolov8n.pt data=your_data.yaml epochs=50 imgsz=640
🔍 4. Run Detection
Image
bash
Copy
Edit
yolo task=detect mode=predict model=best.pt source=images/test.jpg
Video / Webcam
bash
Copy
Edit
yolo task=detect mode=predict model=best.pt source=0  # Webcam
📌 Folder Structure (Example)
css
Copy
Edit
vehicle-damage-detection/
├── images/
│   ├── sample_input.jpg
│   ├── sample_output.jpg
│   └── ...
├── runs/
│   └── detect/
├── data/
│   └── your_data.yaml
├── models/
│   └── best.pt
├── main.py
├── README.md
└── requirements.txt
🔮 Future Improvements
 Add severity classification (minor, major)

 Build web interface using Flask/Streamlit

 Train on a larger and balanced dataset

 Integrate insurance/inspection report generator

🙌 Acknowledgements
Ultralytics YOLOv8

Roboflow – for dataset annotation

OpenCV and Python community

📬 Contact
Archit Agrawal
📧 architagrawal@email.com
🔗 LinkedIn

