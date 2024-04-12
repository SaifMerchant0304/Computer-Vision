### Computer-Vision Project

**Botanical Research Project: Plant Species Classification**

**Data Preparation and Understanding**
- Extract the dataset from 'plant-seedlings-classification.zip' into a new folder using Python.
- Map images from the train folder with train labels to form a DataFrame.
- Implement a function to display n random images along with their species labels.

**Data Preprocessing**
- Create X & Y from the DataFrame.
- Encode labels of the images.
- Ensure uniform shape for all images.
- Normalize all images.

**Model Training**
- Split the data into train and test sets.
- Design a new CNN architecture for model training.
- Train the model on the train data and validate it on the test data.
- Select a random image, print its actual label, and predict its label using the trained model.

**Botanical Research Project: Flower Species Classification**

**Data Understanding**
- Import and read the oxflower17 dataset from tflearn, splitting it into X and Y.
- Print the number of images and their shape.
- Print the count of each class from Y.

**Image Exploration & Transformation**
- Display 5 random images from the dataset.
- Select an image from the dataset and assign it to a variable.
- Transform the image into grayscale format and display it.
- Apply a filter to sharpen the image and display it before and after sharpening.
- Apply a filter to blur the image and display it before and after blurring.
- Display all four images side by side to observe the differences.

**Model Training and Tuning**
- Split the data into train and test sets with an 80:20 proportion.
- Train a model using any Supervised Learning algorithm and share performance metrics on the test data.
- Train a model using a Neural Network and share performance metrics on the test data.
- Train a model using a basic CNN and share performance metrics on the test data.
- Predict the class/label of the image 'Prediction.jpg' using the best-performing model and share the predicted label.

In both projects, the primary objective is to create classifiers capable of determining plant and flower species from photos, respectively. The projects involve steps such as data import, understanding, preprocessing, model training, and evaluation. These steps aim to prepare the data, transform images for analysis, design and train appropriate models, and assess their performance on test data. Finally, the models are utilized to predict the species of new images, contributing to the automation of species classification in botanical research.
