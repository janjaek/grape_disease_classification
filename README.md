# grape_disease_classification
Small CNN computer vision project for the Uni.
The Notebook contains the image preporcessing, an alternative method to the CNN which is used as a baseline, the hyperparamter optimization of the CNN using a gridsearch on a smaller subset of the data and finally the trainig of the best found network architecture on the full dataset.
The Project also contains a gradcam to inspect the last convolutional layer of the network.
The gradcam reveals that the network used the disease spots to classify the images.
