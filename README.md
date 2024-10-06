# Object Detection with CNN on MNIST
## This project demonstrates a simple object detection model using convolutional neural networks (CNN) on the MNIST dataset. The aim is to predict bounding box coordinates around digits in the images.

## Steps Involved:
### Libraries: Essential libraries like TensorFlow, Keras, and NumPy are imported to build and train the CNN model.
### Data Preprocessing: MNIST data is loaded, and synthetic bounding box coordinates are generated for each image.
### Model Creation: A CNN model is defined with multiple convolutional layers to predict the bounding box coordinates (x, y, width, height).
### Training: The model is trained over 10 epochs using mean_squared_error as the loss function.
### Evaluation: The model achieves a low validation loss of 7.8536e-05.
### Bounding Box Visualization: The predicted and actual bounding boxes are visualized on the test images.
