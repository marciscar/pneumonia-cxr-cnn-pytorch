# Pneumonia CXR Classification – A PyTorch Project

This repository contains my solution to an educational project using the [Chest X-Ray Images (Pneumonia) dataset](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia).  
The goal is to classify chest X-ray images as **Normal** or **Pneumonia** using a Convolutional Neural Network (CNN) built with PyTorch.

---

## Project Structure

pneumonia-cxr-cnn-pytorch/    
├── data/ # Chest X-ray dataset (not tracked by Git)    
│ ├── train/    
│ ├── val/    
│ └── test/    
├── Pneumonia_CXR_CNN_PyTorch.ipynb # Main Jupyter notebook    
├── .gitignore    
├── README.md # You are reading it    


---

## Project Goals

- Perform an exploratory data analysis (EDA) of the dataset  
- Train a simple CNN baseline on grayscale chest X-rays  
- Evaluate the model with accuracy, F1-score, and a confusion matrix  
- Visualize results, including correct/incorrect predictions  


---


## How to Reproduce

1. **Download the dataset** from Kaggle:  
   [Chest X-Ray Images (Pneumonia)](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)  

2. **Place the data** inside the `data/` folder:

├──data/    
│ ├── train/    
│ │ ├── NORMAL/    
│ │ ├── PNEUMONIA/    
│ ├── val/    
│ │ ├── NORMAL/    
│ │ ├── PNEUMONIA/    
│ ├── test/    
│ │ ├── NORMAL/    
│ │ ├── PNEUMONIA/    

3. **Run the notebook** `Pneumonia_CXR_CNN_PyTorch.ipynb` cell by cell.


## Results

- **Validation Accuracy**: _____  
- **Test Accuracy**: _____  
- **F1 macro**: _____  





