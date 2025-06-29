This project performs image upscaling (super-resolution) using a custom-trained RRDN (Residual-in-Residual Dense Network) model. 
The goal is to enhance low-resolution images by training on a dataset and generating high-quality, high-resolution outputs while preserving color and detail.
 Repository files
  RRDN_arch.py 
  Contains the architecture definition for the RRDN model. This file builds the deep learning model used for both training and inference.
  
  train_rrdn.py 
  Script to train the RRDN model using a custom dataset of low-resolution and high-resolution image pairs.  
  ➤ Output: A trained model file (e.g., `rrdn_model.pth`).
  
  final_enhance.py 
  Contains the final code to upscale the image using streamlit interface
  
  Take a dataset from kaggle to train rrdn model

  
