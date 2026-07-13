# Pneumonia Detection from Chest X-Ray Images

## Project Overview

This project uses a Convolutional Neural Network (CNN) to classify chest X-ray images as either Normal or Pneumonia. The model was trained on the Chest X-Ray Images dataset and achieved a test accuracy of 88.94%.

## Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook

## Dataset

The project uses the Chest X-Ray Images (Pneumonia) dataset containing Normal and Pneumonia chest X-ray images.

## Model Architecture

* Conv2D (32 filters)
* MaxPooling2D
* Conv2D (64 filters)
* MaxPooling2D
* Conv2D (128 filters)
* MaxPooling2D
* Flatten
* Dense (128 neurons)
* Dropout (0.5)
* Output Layer (Sigmoid)

## Results

* Test Accuracy: 88.94%
* Normal Precision: 94%
* Normal Recall: 75%
* Pneumonia Precision: 87%
* Pneumonia Recall: 97%

## Uploading one X-ray image and checking the model prediction
<img width="1780" height="1214" alt="image" src="https://github.com/user-attachments/assets/b9bb5109-cd8b-4418-ad21-b914aee8e08c" />
<img width="774" height="1180" alt="image" src="https://github.com/user-attachments/assets/3cad7157-83f4-4d37-993a-9ba8a5bc6981" />

## Conclusion

The CNN model successfully learned features from chest X-ray images and was able to distinguish between Normal and Pneumonia cases with good accuracy.
