# Brain Tumor Detection using YOLOv10

This project demonstrates the detection of brain tumours in MRI images using the YOLOv10 model. The model is trained on a dataset of brain MRI images sourced from [Roboflow](https://universe.roboflow.com/brain-mri/mri-rskcu/dataset/3). YOLOv10, a state-of-the-art object detection model, is used to identify and localize brain tumours in MRI scans. The project utilizes Google Colab for model training and Gradio for deployment, allowing users to interact with the model via a simple web interface.

## Project Overview

The main goal of this project is to develop an automated system capable of detecting brain tumors in MRI images. By using YOLOv10, the model can efficiently predict the presence of tumours and pinpoint their locations within the images. The project leverages a publicly available dataset and showcases the potential of deep learning in medical image analysis.

## YOLOv10

YOLOv10 (You Only Look Once) is a highly efficient object detection model that is known for its speed and accuracy. It works by dividing an image into a grid and predicting bounding boxes and class probabilities for each cell. YOLOv10 is an advanced version that brings improvements in both detection accuracy and inference speed, making it ideal for real-time applications like this one.

- Learn more about YOLOv10: [YOLOv10 GitHub](https://github.com/ultralytics/yolov5)

## Dataset

The dataset used in this project is the [Brain MRI Dataset from Roboflow](https://universe.roboflow.com/brain-mri/mri-rskcu/dataset/3). It contains annotated MRI images of brain scans, labelled with the locations of tumors. The dataset is pre-split into training and validation sets, which allows for efficient model training and evaluation.

- Access the dataset: [Brain MRI Dataset on Roboflow](https://universe.roboflow.com/brain-mri/mri-rskcu/dataset/3)

## Tech Stack

- **YOLOv10**: Object detection model used for detecting and localizing brain tumors in MRI images.
- **Google Colab**: Cloud-based environment used for model training and experimentation.
- **Gradio**: Tool for building and deploying interactive machine learning applications.
- **Python Libraries**: OpenCV, NumPy, Matplotlib, etc., for data manipulation and visualization.

## Training and Deployment

1. **Model Training**: The model is trained on the Brain MRI dataset using YOLOv10. The training process is carried out in Google Colab, where the dataset is loaded, processed, and used to fine-tune the model.
   
2. **Deployment with Gradio**: After training the model, it is deployed using Gradio, creating an interactive web interface for users to upload MRI images and receive real-time tumor detection results.

- Access the deployed model: [Gradio Link](https://your-gradio-link.com)

## How to Use

1. Clone the repository:
   
   ```bash
   git clone https://github.com/your-username/brain-tumor-detection-yolov10.git
   cd brain-tumor-detection-yolov10

