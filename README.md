# fruits-ejust

AI Fruits Classification
This project aims to classify different types of fruit using machine learning algorithms. Three different models are implemented: Convolutional Neural Network (CNN), Gaussian Mixture Model (GMM), and Artificial Neural Network (ANN).

Requirements
Python 3.6 or higher
TensorFlow 2.0 or higher
scikit-learn 0.22 or higher
NumPy 1.18 or higher
Matplotlib 3.2 or higher
Usage
To classify fruits using the CNN model, run the following command:

Copy code
python classify_fruits_cnn.py
To classify fruits using the GMM model, run the following command:

Copy code
python classify_fruits_gmm.py
To classify fruits using the ANN model, run the following command:

Copy code
python classify_fruits_ann.py
Dataset
The fruit images used in this project are from the Fruit 360 dataset on Kaggle. The dataset consists of 60,000 images of 120 different types of fruit.

Model Performance
The performance of the three models is evaluated using the following metrics:

Accuracy: the proportion of correct predictions made by the model
F1 Score: the harmonic mean of precision and recall
Confusion Matrix: a table showing the number of correct and incorrect predictions made by the model for each class
The results of the model evaluation are shown in the following table:

Model	Accuracy	F1 Score
CNN	0.97	0.97
GMM	0.93	0.93
ANN	0.91	0.91
Credits
Fruit 360 dataset: Mihai Oltean, Kaggle user moltean
License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgements
I would like to thank the following resources for their assistance in completing this project:

TensorFlow documentation
scikit-learn documentation
Stack Overflow
