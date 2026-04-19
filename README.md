
## Project Describtion
This project shows how to use Computer Vision in medical application. (You Only Look Once) algorithm version 8 introduce a Segmentation layer which is added after detecting the the bounding box to achieve ability for generating segmentation masks precised on the on the object being deteced

I implemented (You Only Look Once) algorithm version 8 **from scratch** according to it's research paper using PyTorch 

Code details in the colab notebook above "how to train Segmentation model on cancer tumor dataset.ipynb"

## Project Idea is to build completely from scratch YOLO algorithm from it's it's research paper using low level pytorch only. with out any high level tool
How to train yolo algorithm on a specific data set **from scratch** to perform segmentation tasks.


Code details in the colab notebook above "how to train Segmentation model on cancer tumor dataset.ipynb"


## Dataset
[Dataset Link](https://www.kaggle.com/datasets/sartajbhuvaji/brain-tumor-classification-mri/data)

## Why YOLO algorithm for Brain Tumor Detection?
1- Fast object detection: YOLO is designed for real-time object detection. This makes it highly efficient in identifying brain tumors in the very low hardware resources machines, which is crucial in medical applications where time is important with limmited resources computers unlike the two stage algorthims as the familly of R-CNN that has high number of parameters which make it heavy algorithms.

2- Localization: YOLO's streamlined architecture allows it to detect tumors with high precision, even when they vary in size, shape, light condition or location within the brain, making it a reliable tool for medical imaging tasks.

## final output after training (Prediction Phase)
![Image](https://github.com/user-attachments/assets/ac780dd6-f1c7-44d8-a236-87dde0e36ea9)
![Image](https://github.com/user-attachments/assets/893b63f0-341e-469a-87cc-0059186d8a7b)
![Image](https://github.com/user-attachments/assets/2eab9407-fc1c-4bbe-b404-0128636824e9)



