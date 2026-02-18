# Spring Internship Project 2026  
## Image Data Augmentation and Image Classification (Cat vs Dog)

---

## 📌 Project Description

This project was completed as part of the Spring Internship Program 2026.

The objective of this assignment is to demonstrate:

- Downloading and preparing a real-world image dataset
- Performing image preprocessing using OpenCV
- Applying data augmentation using PyTorch and Torchvision
- Creating datasets using ImageFolder
- Implementing DataLoader for batch processing
- Verifying transformations through visualization

The project uses a Cat vs Dog dataset to showcase practical image classification preprocessing workflows.

---

## 📂 Repository Structure

Spring-Internship-Image-Classification-2026  
│  
├── 09-Imagedata_Augmentation_and_Image_Classification_Spring_2026.ipynb  
├── moon-pexels-frank-cone.jpg  
├── Internship_Report_Rohit_Antony.pdf  
└── README.md  

---

## 🐱 Dataset Information

The Cat and Dog dataset is automatically downloaded inside the notebook using:

!curl -O https://s3.amazonaws.com/content.udacity-data.com/nd089/Cat_Dog_data.zip  
!unzip -o Cat_Dog_data.zip  

This creates the "Cat_Dog_data" directory containing:

- Training images  
- Test images  
- Separate folders for cats and dogs  

Note: The dataset (~553MB) is not uploaded to GitHub due to size constraints.  
It is automatically downloaded when the notebook is executed.

---

## 🖼 Image Processing & Augmentation Tasks

The following tasks are implemented:

- Image loading using OpenCV  
- Image shape inspection  
- Grayscale conversion  
- Image resizing  
- Image rotation  
- Affine transformations  
- Data augmentation using Torchvision transforms  
- Dataset creation using ImageFolder  
- Batch loading using DataLoader  
- Visualization of transformed images  

---

## 🛠 Technologies Used

- Python  
- NumPy  
- OpenCV (cv2)  
- PyTorch  
- Torchvision  
- Matplotlib  

---

## ▶ How to Run the Project

1. Clone the repository:
   git clone https://github.com/RohitAntony1304/Spring-Internship-Image-Classification-2026.git  

2. Open the notebook in Google Colab or Jupyter Notebook.

3. Run all cells from top to bottom.

4. The dataset will automatically download and unzip.

---

## 👤 Author

Rohit Antony  
Spring Internship 2026
