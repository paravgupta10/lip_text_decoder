# Lip Reading Model using CNN + LSTM

## Overview
This project implements a lip reading model that detects spoken text from lip movements in video data. It combines Convolutional Neural Networks (CNN) for spatial feature extraction from video frames and Long Short-Term Memory (LSTM) networks for temporal sequence modeling.

## Model Architecture
1. **CNN**: Extracts spatial features from video frames (lip region).
   - Input: Preprocessed video frames
   - Layers: Conv2D, MaxPooling, BatchNormalization, Dropout.
2. **LSTM**: Models temporal dependencies across frames.
   - Input: CNN-extracted feature sequences.
   - Layers: Bidirectional LSTM, Dense layers for classification.
3. **Output**: Predicted text (word or phoneme sequences).

   
 ![gradio_interface](https://github.com/user-attachments/assets/3e12c09d-ed50-4528-81dc-2bdd516ac0df)
