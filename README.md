# FOOD-IMAGE-RECOGNITION-CLASSIFICATION-SYSTEM
(EPT4046 - PROJECT)-A project to create a simple model that classifies food images. Transfer Learning is used to create the model.


**Objective:**

The main objective of the project is to build a Multi-Class Image Classifier to identify the food category, given an image of food.

**Dataset:**

The Dataset "Food-11 image dataset" is obtained from Kaggle (click [here)](https://www.kaggle.com/datasets/trolukovich/food11-image-dataset). This dataset contains 16643 food images grouped in 11 major food categories. There are 3 splits in this dataset:
- Training
- Validation
- Testing

**Architecture Used:**

The following Neural Network Architechtures are used to build models via the technique of Transfer Learning in Python on Google Colab with the usage of Tensorflow libraries:
- Inception V3
- VGG-16
- DenseNet-121
- ResNet-50

**Evaluation:**

The Metric used for evaluation of the neural network architectures is using percentage of accuracy with respect to the predicted and actual classes of food.

**Result:**

| Model  | Accuracy |
| ------------- | ------------- |
| Inception V3  | 91.93%  |
| VGG-16  | 87.00%  |
| DenseNet-121  | 90.80%  |
| ResNet-50  | 90.98%   |
