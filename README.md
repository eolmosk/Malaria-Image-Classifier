# Malaria Clasifier
 
 This project presents a computer vision classification model designed to differentiate between uninfected and parasitized red blood cells, with the goal of providing a reliable, fast, and cost-effective means of diagnosing malaria. The model is capable of analyzing input images of red blood cells and accurately classifying them as either infected or uninfected. This project was developed as part of the Massachusetts Institute of Technology's Applied Data Science Program.

Table of contents of the Notebook:

Milestone 1

1. Problem definition
  1.1 Context
  1.2 Objectives
  1.3 Description of the data

2. Loadings
  2.1 Mounting the Drive
  2.2 Loading libraries
  2.3 Loading the data
  2.4 Checking if data is balanced

3. Data Exploration
  3.1 Let's visualize the images from the train data
  3.2 Normalizing the images
  3.3 Plotting the mean images for parasitized and uninfected

4. Data Pre-processing
  4.2 Converting RGB to HSV of Images using OpenCV
  4.3 Processing Images using Gaussian Blurring

5. Proposed approach
  Potential techniques:
  Overall solution design:
  Measures of success:

6. Must run cells
  One Hot Encoding on the train and test labels
  Function to plot train and validation accuracy, loss and validation loss.
  Importing the required libraries for building and training our Model
  Function to Plot the Confusion Matrix and printing the classification report


Milestone 2
1. Base Model
  1.1 Building the model
  1.2 Fit and train the Model
  1.3 Evaluating the model on test data

2. ANN Base Model
  2.0 Pre-processing images
  2.1 Building the model
  2.2 Fit and train the model
  2.3 Evaluating the model on test data

3. Model 1
  3.1 Building the Model
  3.2 Fit and Train the model
  3.3 Evaluating the model

4. Model 2 with Batch Normalization and LeakyRelu
  4.1 Building the Model
  4.2 Fit and train the model
  4.3 Evaluating the model

5. Model 2B
  5.1 Building the Model
  5.2 Fit and train the model
  5.3 Evaluating the model

6. Model 2 (trained and tested with HSV images)
  6.1 Building the model
  6.2 Fit and train the model
  6.3 Evaluating the model

7. Model 2GB (trained an tested with images pre-processed with gaussian blurring)
  7.1 Building the Model
  7.2 Fit and Train the model
  7.3 Evaluating the model

8. Model 3 with Data Augmentation
  8.0 Using image data generator
  8.1 Building the Model
  8.2 Fit and Train the model
  8.3 Evaluating the model

9. Model 3B (Data Augmentation with Gaussian Blur)
  9.0 Using image data generator with the blurred train image set.
  9.1 Building the Model
  9.2 Fit and Train the model
  9.3 Evaluating the model

10. Model 4 with Pre-trained model (VGG16)
  10.1 Getting the pre-trained layers and top
  10.2 Fit and Train the model
  10.3 Evaluating the model

11. Comparing every model performance:
  Observations and Conclusions drawn from the final model:
  Insights
