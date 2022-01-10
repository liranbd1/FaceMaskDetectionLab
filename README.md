# FaceMaskDetectionLab

This is a lab project for university.

Using MTCNN to detect faces in images and ResNet18 to classify the faces if they have a proper mask on their face or not.

## Files
### MTCNN-POC
This notebook is to find how good is MTCNN in detecting faces.

### Training-Classifier
Training the ResNet18 Classifier to our specific problem

### Prod
Combining all of the parts together to show an E2E tool

## Getting the Dataset
Dataset is located in Kaggle competition https://www.kaggle.com/wobotintelligence/face-mask-detection-dataset/download

## Running the notebooks
Create a new folder in Google Drive and pass into it the images folder and the train.csv from the downloaded dataset.
Update the root variable in the notebooks to the new folder name (Or you can name the folder MaskDetection)
