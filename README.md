# 🧠 Brain Tumor Detection & Classification

This project aims to detect and classify brain tumors from MRI images using YOLOv8n for object detection and ResNet-50 for classification. It includes a Flask-based user interface for easy interaction.

## 📌 Features

- Tumor detection using YOLOv8n on MRI scans
- 4 Tumor classes: **Glioma**, **Meningioma**, **Pituitary**, **No Tumor**
- Region of Interest (ROI) extraction post-detection
- Classification using ResNet-50
- Flask Web UI for uploading MRI scans and viewing results

## 🧠 Models Used

- **YOLOv8n**: for tumor detection
- **ResNet-50**: for tumor classification

## 🖼 Sample MRI Classes

- Glioma
- Meningioma
- Pituitary
- No Tumor

## 🚀 Technologies Used

- Python
- YOLOv8n (Ultralytics)
- OpenCV
- PyTorch
- Flask (for web UI)
- NumPy, Pandas, Matplotlib

## 📸 UI Preview

![image](https://github.com/user-attachments/assets/676e5617-d985-49dc-b452-58208b404b51)


## 💻 How to Run Flask

cd Flask_Web
python webapp.py

