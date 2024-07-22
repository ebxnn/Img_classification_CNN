# Img_classification_CNN

This project focuses on building an image classification model using TensorFlow and Keras. The model is trained on a dataset of fruits and vegetables, and it can classify images into different categories.

#Introduction
This project demonstrates the use of Convolutional Neural Networks (CNNs) for image classification. The dataset used contains images of various fruits and vegetables, and the model is trained to classify these images into their respective categories.

#Dataset
The dataset is organized into three main directories: train, validation, and test. Each directory contains subdirectories for each class (e.g., apple, banana, etc.). Images are resized to 180x180 pixels.

#Model Architecture
The model is built using the TensorFlow Keras Sequential API and consists of the following layers:

*Rescaling layer to normalize pixel values
*Three convolutional layers with ReLU activation and max-pooling
*Flatten layer to convert the 2D matrix to a 1D vector
*Dropout layer to prevent overfitting
*Fully connected (Dense) layer with ReLU activation
*Output layer with units equal to the number of categories

#Training
The model is compiled with the Adam optimizer and sparse categorical cross-entropy loss function. It is trained for 35 epochs using the training and validation datasets.

#Results
During training, the model's accuracy and loss are plotted for both the training and validation sets to monitor its performance. After training, the model is saved for future use.

############Contributions are welcome! Please open an issue or submit a pull request for any improvements or suggestions.##############
