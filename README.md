# Video Captioning Project

This project is designed to generate descriptive captions for videos by leveraging deep learning for visual feature extraction and natural language generation.

## Overview

This video captioning pipeline is divided into two main stages:
1. **Visual Information Extraction** - Using ResNet50, we process each frame in the video to extract meaningful visual features.
2. **Caption Generation** - Based on the extracted visual features, captions are generated using an LSTM-based encoder-decoder model, implemented with TensorFlow.

The pipeline aims to create captions that accurately capture the essence of video content.

## Project Structure

- **`VideoProcessing.ipynb`**: Handles video frame processing. ResNet50 is used to extract feature vectors from each frame, which serve as inputs to the caption generator.
- **`CaptionGeneration.ipynb`**: Generates captions based on the visual features using an LSTM-based encoder-decoder model built with TensorFlow.

## Requirements

- Python 3.x
- TensorFlow
- OpenCV (for video processing)
- NumPy
