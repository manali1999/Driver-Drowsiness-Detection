# Driver Drowsiness Detection using Deep Learning

## Overview
This project implements a **driver drowsiness detection system** using **VGG16** and **OpenCV**. The model detects drowsiness based on eye state and yawning detection, providing alerts if the driver appears drowsy.

## Files and Folders

training.ipynb **Jupyter Notebook for training the model**

inference.ipynb **Jupyter Notebook for real-time drowsiness detection**

alarm.wav **Sound alert for drowsy driver**

Predefine_Architecture_VGG16_Model.h5 **Pre-trained model** 



## How to Use
1. **Train the Model**
   - Open `training.ipynb` in Jupyter Notebook.
   - Run all the cells to train the model using VGG16 architecture.
   - The trained model will be saved as `Predefine_Architecture_VGG16_Model.h5`.

2. **Run Inference**
   - Open `inference.ipynb` in Jupyter Notebook.
   - Run the cells to start the camera and detect drowsiness.
   - If drowsiness is detected, an alarm sound (`alarm.wav`) will play.

## Dependencies
- Python 3.x
- TensorFlow
- Keras
- OpenCV
- NumPy
- Matplotlib
- SciKit-Learn
- Seaborn

Install dependencies using:
```sh
pip install tensorflow opencv-python numpy matplotlib scikit-learn seaborn
