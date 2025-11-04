# Plant Disease Detection

This project is an AI-powered system to detect plant diseases from images. I trained a custom CNN using MobileNetV2 to classify plant leaves into Healthy, Powdery and Rust categories.

The project was developed and deployed using Microsoft Azure, which provided a powerful cloud environment with pre-configured Python and TensorFlow support, making training and deployment smooth and efficient.

This tool can help farmers and researchers quickly identify crop issues, take early action, and improve yield and sustainability.

## Dataset
[Dataset](https://www.kaggle.com/code/vad13irt/plant-disease-classification)

## Model
**Architecture:** MobileNetV2 with custom dense layers on top  
**Training:** Data augmentation was used to improve robustness  
**Fine-tuning:** Last layers of MobileNetV2 were unfrozen for better accuracy

## Usage
[Clone Repository](https://github.com/silyones/Plant-Disease-Detection-AZURE-ML.git)

## Training Results
![Training Loss](https://github.com/silyones/Plant-disease-Prediction-AZURE-ML/blob/main/model_loss.jpg?raw=true)  
*Training loss curve showing model performance over epochs.*

