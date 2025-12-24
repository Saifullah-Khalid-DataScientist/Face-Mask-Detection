😷 Face Mask Detection using YOLOv11
📌 Project Overview

This project detects whether a person is wearing a face mask or not using a deep learning-based object detection model. The system can be used in public places such as hospitals, offices, airports, and schools to monitor safety compliance.

🎯 Objective

To automatically identify:

✅ Mask

❌ No Mask
from images using a trained YOLO model.

📂 Dataset Description

Two classes: Mask and No Mask

Images captured under different lighting conditions and angles

Dataset annotated in YOLO format

Dataset prepared using Roboflow

🛠️ Technologies Used

🧠 YOLOv11 (Ultralytics)

🐍 Python

👁️ OpenCV (for image processing & visualization)

📊 Google Colab / Jupyter Notebook

🔄 Methodology

Collect and prepare face mask dataset

Annotate images in YOLO format

Train YOLO model using transfer learning

Fine-tune model for better accuracy

Test model on unseen images

Visualize results using OpenCV

📈 Results

The model successfully detects Mask and No Mask

Bounding boxes are drawn on detected faces

Confidence scores are displayed for each detection