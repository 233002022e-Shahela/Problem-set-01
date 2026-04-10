# Problem Set 01 - CNN for Pneumonia Detection

## Objective
To build a Convolutional Neural Network (CNN) model to classify chest X-ray images into:
- Pneumonia
- Normal

## Dataset
- 5,863 X-ray images
- Organized into train, validation, and test folders
- Binary classification problem

## Methodology
- Image preprocessing using rescaling
- CNN model with:
  - Convolution layers
  - Max pooling
  - Fully connected layers
- Activation: ReLU and Sigmoid

## Results
- Model trained for 5 epochs
- Achieved good accuracy on validation and test data

## Challenges
- Large dataset size
- Risk of overfitting
- Requires GPU for faster training

## Conclusion
CNN successfully learned to classify X-ray images and can assist in medical diagnosis.
