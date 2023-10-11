# MAIS202-Kaggle-Competition

## About this project:
The MNIST dataset, a cornerstone in the realm of computer vision and deep learning, has long been a touchstone for aspiring data scientists and machine learning enthusiasts. This competition, hosted by the McGill Artificial Intellegence Society on Kaggle, presents a unique opportunity to delve into the world of image classification and push the boundaries of what can be achieved with modern machine learning techniques.

## Business Value:

## Main Findings:
**Preprocessing of Images:** The process starts with preprocessing the input images. Morphing and blurring techniques are applied to enhance the clarity of object outlines and reduce the impact of black dots in the images. Additionally, dilation is used to expand the shapes within the pictures. These preprocessing steps are carried out on both the training and test datasets.

**Model Architecture:** The model architecture is based on a CNN (Convolutional Neural Network) structure. It comprises three convolutional layers activated by Rectified Linear Unit (ReLU) functions. After each convolutional layer, max-pooling is applied to reduce the number of parameters by half, aiding in feature extraction. A 25% dropout layer is included to regularize the data and prevent overfitting. The model then flattens the results to transform them into a vector format. Subsequently, a dense layer creates a fully connected graph, followed by another dropout layer. Finally, a dense layer with the SoftMax activation function outputs a vector of length 10, representing the ten classes of the data.

**Model Results:** The trained model provided secured 4th place in the competition with a testing accuracy score of 87.64%.

## Reproducing Results:
To reproduce the results, please open the Jupyter notebook and run the entire notebook from top to bottom. The notebook will automatically generate an output file with the predictions, named "subm.csv." If you prefer not to retrain the model and would rather use the pre-trained model, please follow the instructions provided in the notebook for loading the existing model.

To run the notebook, download both the notebook itself and the training/test files from the Kaggle competition (https://www.kaggle.com/c/mais202fall2021/). Ensure that all the files are placed in the same directory and then run the notebook from that location.
