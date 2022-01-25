# BreastCancerPrediction

## Introduction
In this project, I build a Logistic regression model using Scikit-learn to classify breast cancer as either Malignant or Benign. I use the [Breast Cancer Wisconsin (Diagnostic) Data Set](https://www.kaggle.com/uciml/breast-cancer-wisconsin-data) from Kaggle. **The goal** is to use a simple logistic regression classifier to **classify between cancerous and noncancerous patients**.

## Data description
Features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe characteristics of the cell nuclei present in the image.
There is some attribute information such as: ID number and Diagnosis (M = malignant, B = benign) and ten real-valued features that are computed for each cell nucleus:

  - radius (mean of distances from center to points on the perimeter)
  - texture (standard deviation of gray-scale values)
  - perimeter
  - area
  - smoothness (local variation in radius lengths)
  - compactness (perimeter^2 / area - 1.0)
  - concavity (severity of concave portions of the contour)
  - concave points (number of concave portions of the contour)
  - symmetry
  - fractal dimension ("coastline approximation" - 1)

## Implementation
1. Load & exlore the dataset
2. Perfirm LabelEncoding
3. Split the data into independent and dependent sets; perform feature scaling
4. Build logistic regression classifier
5. Evaluate the performance of the model


## Results
I have checked the efficiency of a trained model on the test data and labels. In this case, the accuracy of the method is about 96,5%, which is high enough. So, I made a conclusion that the implementation using logistic regression classifier is suitable and efficient.
