## Overview

This project focuses on classifying waste into various categories using Convolutional Neural Networks (CNNs), aiming to facilitate automated waste sorting and promote efficient recycling. The project uses the TrashNet dataset, a well-known dataset for waste classification. It begins with developing a basic CNN model and then enhances its performance by leveraging pre-trained models through transfer learning. Additionally, the dataset is augmented with pictures of waste items taken personally to ensure diversity and real-world applicability.

## Project Structure

1. **Data Preparation:**
   - Collect and preprocess the dataset, including images of waste items taken personally, resizing them, normalizing, and splitting them into training, validation, and test sets.

2. **Basic CNN Model:**
   - Design and implement a simple CNN architecture to serve as a baseline for classification performance.

3. **Transfer Learning:**
   - Fine-tune pre-trained models on the dataset to leverage features learned from large-scale datasets and improve classification accuracy.

4. **Model Evaluation:**
   - Assess the performance of both the basic CNN model and the fine-tuned pre-trained models using metrics like accuracy, precision, recall, and F1-score. 

5. **Results and Analysis:**
   - Compare the performance of different models and analyze the impact of transfer learning on model accuracy and robustness.

This structure allows for a comprehensive exploration of CNN-based waste classification, from basic implementation to advanced techniques using transfer learning, incorporating real-world data.
