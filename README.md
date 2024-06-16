# Melanoma-CNN-Prediction

## Problem Statement
In this assignment, you will build a multiclass classification model using a custom convolutional neural network in TensorFlow.

#### Objective
The goal is to develop a CNN-based model that can accurately detect melanoma, a type of cancer that is responsible for 75% of skin cancer deaths if not detected early. An automated solution that can evaluate images and alert dermatologists about the presence of melanoma could significantly reduce the manual effort required for diagnosis.

The dataset consists of 2357 images of both malignant and benign oncological diseases, sourced from the International Skin Imaging Collaboration (ISIC). The images are categorized based on ISIC classifications, with an equal number of images in each subset, except for melanomas and moles, which are slightly more prevalent.

The dataset includes the following diseases:
1. Actinic keratosis
2. Basal cell carcinoma
3. Dermatofibroma
4. Melanoma
5. Nevus
6. Pigmented benign keratosis
7. Seborrheic keratosis
8. Squamous cell carcinoma
9. Vascular lesion

#### Project Pipeline
1. **Data Reading and Understanding**: Define the paths for training and test images.
2. **Dataset Creation**: Create training and validation datasets from the training directory with a batch size of 32. Ensure images are resized to 180x180 pixels.
3. **Dataset Visualization**: Develop code to visualize one instance of each of the nine classes in the dataset.
4. **Model Building and Training**: 
   - Construct a CNN model that can accurately classify the 9 classes in the dataset. Rescale images to normalize pixel values between 0 and 1.
   - Select an appropriate optimizer and loss function for model training.
   - Train the model for approximately 20 epochs.
   - Analyze the model's performance to identify any signs of overfitting or underfitting.
5. **Data Augmentation**:
   - Implement data augmentation strategies to address any issues of overfitting or underfitting.
   - Rebuild and train the CNN model using the augmented data.
   - Train the model for approximately 20 epochs.
   - Evaluate whether the data augmentation resolved the initial issues.
6. **Class Distribution Analysis**:
   - Assess the class distribution in the training dataset.
   - Identify the class with the fewest samples.
   - Determine which classes dominate in terms of sample proportion.
7. **Handling Class Imbalances**:
   - Address class imbalances in the training dataset using the Augmentor library.
8. **Model Building and Training on Balanced Data**:
   - Construct a CNN model that accurately classifies the 9 classes using the balanced dataset. Normalize pixel values between 0 and 1.
   - Choose an appropriate optimizer and loss function for model training.
   - Train the model for approximately 30 epochs.
   - Analyze the model's performance to determine if the issues have been resolved.
  
    Created by
# Amit Ranjan 
