# CNN-Based Binary Retinal Detachment Detection on Raspberry Pi 4



## Project Overview

This project focuses on developing a Convolutional Neural Network (CNN) for binary classification of retinal images into two categories: retinal detachment and non-retinal detachment. The trained model was optimized for deployment on a Raspberry Pi 4, enabling real-time, on-device image classification suitable for low-resource settings.

## Objectives

- Build a TensorFlow-based CNN model for binary image classification.
- Improve model performance using advanced convolutional layers and batch normalization.
- Optimize the model for real-time inference on Raspberry Pi 4.

## Tools and Technologies Used

- Python  
- TensorFlow  
- Keras  
- NumPy  
- Matplotlib  
- Raspberry Pi 4

## Folder Structure

```
├── RDnonRDNCode.ipynb       # Main notebook for training and evaluation
├── gui.py                   # GUI script for image input and result display (optional)
├── transform.py             # Preprocessing and image transformation script (optional)
├── GAT.pt                   # Model weights file (if using PyTorch version)
├── README.md                # Project documentation
```

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/retinal-detachment-cnn.git
cd retinal-detachment-cnn
```

2. Install required libraries:

```bash
pip install tensorflow keras numpy matplotlib
```

3. Open and run the Jupyter notebook:

```bash
jupyter notebook RDnonRDNCode.ipynb
```

If you have `gui.py` and want to test the GUI:

```bash
python gui.py
```

## Model Summary

- Accuracy: 88.1% after 30 training epochs  
- Optimizer: SGD  
- Loss Function: Binary Crossentropy  
- Batch Normalization used for training stability  
- Deployed on Raspberry Pi 4 for real-time usage

## Notes

- This model can be used as a lightweight solution for medical image classification in embedded systems.
- The accuracy can be improved further with more data and advanced preprocessing.

