# Real-time Sign Language Translation Using CNNs and RNNs

This project focuses on real-time sign language translation using Convolutional Neural Networks (CNNs) and Recurrent Neural Networks (RNNs). The goal is to build a system capable of recognizing sign language gestures and translating them into text in real-time.

## Dataset

The dataset used in this project was self-collected by capturing images of various sign language gestures. The data was gathered using a webcam, with the following Python code to collect images for each gesture class. The dataset contains images of 26 sign language gestures corresponding to the alphabet (A-Z).

### Dataset Details:
- **Collection Method:** The dataset was collected using OpenCV to capture frames from a webcam. For each gesture, 150 images were collected and saved in separate directories corresponding to each gesture class.
- **Number of Samples:** 26 classes, each with 150 images (for a total of 3,900 images).
- **Data Type:** Images (static).
- **Gesture Labels:** The dataset represents the American Sign Language alphabet (A-Z), with each gesture corresponding to a letter.
- **Google Drive Link:** You can access the dataset on Google Drive [here](https://drive.google.com/file/d/1kO8swytdVen0190W5Rp8MBW9U39Dw7gS/view?usp=sharing).

## Project Structure

- **AML.ipynb:** The Jupyter notebook containing the implementation of the sign language recognition system, including preprocessing, model training, and evaluation.
- **model.ipynb:** A Jupyter notebook where the model is trained and saved using PyTorch. The trained model is later saved using `torch.save()` and can be loaded for further inference or deployment.

## Deployment
- **Streamlit Wandb:** You can access the github [here](https://github.com/aliblackk/sign-language).
- **Streamlit Testing:** You can access the github [here](https://github.com/aliblackk/sign-language-image).
