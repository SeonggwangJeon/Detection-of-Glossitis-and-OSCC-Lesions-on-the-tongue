# diagnosing-tongue-disease

This repository contains the code for the paper "--" by Yeon-Hee Lee, Seonggwang Jeon. The code includes data preprocessing, model training and testing, Grad-CAM heatmap generation, and activation visualization for the detection of Tongue disease using deep learning techniques.

## Repository Structure

- **1.data_preprocessing.ipynb**
  - Jupyter notebook for data preprocessing. This includes loading the MRI images and clinical data, and preparing them for model training.
  - 
- **2.data_initial_analyze.ipynb**
  - Jupyter notebook for data analyze. This includes analyzing feature distributions.
    
- **3.Tongue.ipynb**
  - Jupyter notebook for training and testing the convolutional neural network (CNN) models. It includes three schemes: from-scratch, fine-tuning, and freeze, and four CNN based models (VGG16, VGG19, RESNET50, RESNET152).
    
- **4.Voting_Tongue.ipynb**
  - Jupyter notebook for training and testing the convolutional neural network (CNN) models. It includes three schemes: from-scratch, fine-tuning, and freeze, and four CNN based models (VGG16, VGG19, RESNET50, RESNET152) with image cropping and voting strategy.
    
- **5.Feature_map.ipynb**
  - Jupyter notebook for generating activated node maps to visualize the regions sparsity of trained CNN models.
    
- **6.GradCam_Heatmap.ipynb**
  - Jupyter notebook for generating Grad-CAM heatmaps to visualize the regions focused on by the model during prediction.

- **LICENSE**
  - License file for the project.

- **README.md**
  - This file. Provides an overview of the project and instructions for use.

## Installation and Usage

1. **Clone the repository:**
   ```bash
   git clone https://github.com/SeonggwangJeon/diagnosing-tongue-disease.git

## Contact
 **For any questions or issues, please contact:**
  - Yeon-Hee Lee: omod0209@gmail.com
  - Seonggwang Jeon: qq22512@hanyang.ac.kr

  
## Acknowledgments
  - This work was supported by the Department of Orofacial Pain and Oral Medicine, Kyung Hee University Dental Hospital, and the Department of Computer Science, Hanyang University.**

