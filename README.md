# Garbage classification with Data augmentation

The project concerns waste classification to determine if it may be recycled or not. In this approach, we will use a Convolutional Neural Network(CNN) model with data augmentation to achieve better results. It is a binary classification problem and we will train the model in Keras as well.

# Data augmentation
is a technique of applying different transformations to original images which result in multiple transformed copies of the same image. Each copy is different from the other ones in certain aspects depending on the augmentation techniques you apply like rotating, shifting, flipping, etc. These techniques not only expand the size of our dataset but also include a level of variation in the dataset which allows our model to generalize better on unseen data. The model becomes more robust when it is trained on new, slightly altered images.

# Dataset

The dataset contains images divided into two classes: organic waste and recycled waste and it is split into train data (85%) and test data (15%). The training dataset contains 22564 images while the test dataset contains 2513 images.

# Summary
The aim of the project was waste classification by using Deep Neural Networks. The dataset contains waste images recyclable and organic ones. I have built a model to predict if the waste may be recyclable or not. In the analysis, I have used the Convolutional Neural Network (CNN) model with data augmentation and transfer learning to get more accurate predictions and choose the best one for that.

# Project includes:
Waste classification with CNN model - Waste_cnn.ipynb
Waste Classification with data augmentation - Waste_Augumentation.ipynb
Waste Classification with transfer learning - waste_transfer_learning.ipynb

# Technologies
The project is created with:

Python 3.8
libraries: TensorFlow, Keras, pillow, numpy, pandas, seaborn.
Running the project:

To run this project use Jupyter Notebook or Google Colab.
