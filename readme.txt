# Product Defect Detection Using CNN

## Overview
This project implements a convolutional neural network (CNN) using TensorFlow and Keras to detect product defects in images. The CNN model is trained on labeled images of various defect types and can classify new images into these categories.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/product-defect-detection.git
2. Navigate to the project directory:
     ```bash
cd product-defect-detection
3. Install the required Python packages using pip:
```bash
pip install -r requirements.txt
## Usage

1. Organize your training images in the 'train' directory and testing images in the 'test' directory.
2. Configure the model parameters and file paths in defect_detection.py as needed.
3. Run the training script to train the CNN model:
```bash
python defect_detection.py
4. Evaluate the model's performance and accuracy on the test set.
5. Use the trained model to make predictions on new images or integrate it into a production system for defect detection.

## File Structure
defect_detection.py: Python script for model training, evaluation, and prediction.
requirements.txt: List of required Python packages with versions.
train/: Directory containing training images categorized by defect type.
test/: Directory with test images for evaluating the model.


   
