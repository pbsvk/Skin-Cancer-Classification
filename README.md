# Skin Cancer Detection using Image Processing and SVM Algorithm

A MATLAB-based application to assist in the early detection and classification of skin cancer using image processing techniques and a Support Vector Machine (SVM) classifier.

## Project Overview

This project aims to identify five major types of skin cancer from images:
- Actinic Keratosis
- Basal Cell Carcinoma
- Cherry Nevus
- Dermatofibroma
- Melanoma

Using a combination of preprocessing, segmentation, feature extraction, and classification, the application supports early diagnosis through a user-friendly interface.

## Technologies & Tools

- **Language**: MATLAB
- **Libraries/Toolboxes**:
  - Image Processing Toolbox
  - Statistics and Machine Learning Toolbox

## Methodology

1. **Image Input**: Upload or capture skin lesion images.
2. **Preprocessing**: Median filtering and histogram equalization to enhance image quality.
3. **Segmentation**: Fuzzy C-Means clustering isolates the region of interest.
4. **Feature Extraction**: 
   - Gabor Filters for texture analysis
   - GLCM (Gray-Level Co-occurrence Matrix) for spatial features
5. **Classification**: 
   - SVM (Support Vector Machine) to classify the lesion into one of the five types.

## Sample Workflow

Input Image → Preprocessing → Segmentation → Feature Extraction → SVM Classification → Output

## Features

- User-friendly GUI for easy interaction
- Automated classification of skin lesion types
- Image-based analysis requiring minimal manual input

## Dataset

The project was trained and tested on a dataset of over 1000 labeled skin lesion images. 

##  Execution

1. Open the project folder in MATLAB.
2. Ensure Image Processing and ML Toolboxes are installed.
3. Run the main application script (`main.m` or GUI file).
4. Upload a skin lesion image and view the classification results.

## Future Enhancements:

- Integration with mobile apps or web platforms for real-time accessibility
- Expansion to classify more skin conditions beyond the five major types
- Incorporation of deep learning models (e.g., CNNs) for improved accuracy and adaptability
- Real-time camera input and instant feedback
- Inclusion of a larger and more diverse dataset for better generalization

## Contributors

- Bhaskara Sai Vamsi Krishna Padala



