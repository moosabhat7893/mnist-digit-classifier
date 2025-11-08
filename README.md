Digit-Recognition-Using-CNN

Handwritten digit classification using a Convolutional Neural Network (CNN) built with TensorFlow/Keras to identify digits (0–9) from the MNIST dataset.
The model learns spatial hierarchies of features from grayscale 28×28 images and achieves high accuracy, demonstrating the strength of CNNs in image recognition tasks.

Objective

To develop and evaluate a deep learning model capable of classifying handwritten digits from the MNIST dataset by learning spatial and visual patterns automatically using convolutional layers.

Technologies / Libraries

Python
TensorFlow / Keras
NumPy, Pandas
 
Dataset

MNIST Dataset
a benchmark dataset containing 60,000 training and 10,000 testing grayscale images of handwritten digits (0–9), each sized 28×28 pixels.

Key Features

Preprocessing: reshaping and normalization of image data

CNN model built with multiple convolutional, pooling, and dense layers

Model training and evaluation on unseen test data

Visualization of training accuracy and loss over epochs

Sample predictions on test digits with actual vs. predicted labels

Results
Metric	Training Accuracy	Test Accuracy	Loss
Value	  ~99%	            ~98%	        Low

Insights:

CNN effectively captures pixel-level features for digit recognition.

Model generalizes well to unseen handwritten digits, achieving over 98% test accuracy.

Visual Outputs


Sample Predictions

![Sample Predictions](images/sample_predictions.png)

Future Enhancements

Add dropout and batch normalization to improve generalization

Compare with LeNet-5 or VGG-like architectures

Visualize feature maps and misclassified images

Deploy model as a web app using Streamlit or Flask for live digit recognition

License

This project is open-source under the MIT License.

Author
Muhammad Moosa
GitHub: moosabhat7893
