# Real-time Sign Language Translation Using CNNs and RNNs

This project focuses on real-time sign language translation using Convolutional Neural Networks (CNNs) and Recurrent Neural Networks (RNNs). The goal is to build a system capable of recognizing sign language gestures and translating them into text in real-time.

## Dataset

The dataset used in this project was self-collected and consists of images of various sign language gestures. The dataset includes both static and dynamic gesture representations, which are used to train the model for gesture recognition. The dataset is labeled with corresponding sign language symbols for effective training.

### Dataset Details:
- **Collection Method:** The dataset was collected using custom-built devices and methods to capture various sign language gestures.
- **Number of Samples:** [3900]
- **Data Type:** [Image]
- **Gesture Labels:** [Insert labels here, e.g., Alphabet, Phrases, etc.]

## Project Structure

- **AML.ipynb:** The Jupyter notebook containing the implementation of the sign language recognition system, including preprocessing, model training, and evaluation.
- **Model:** A combination of CNNs for feature extraction and RNNs for sequence prediction, designed to recognize gestures in real-time.
