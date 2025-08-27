# Melanoma Detection Using Deep Learning

## Introduction
This project focuses on developing a custom convolutional neural network (CNN) to accurately identify melanoma from skin lesion images. Its primary objective is to support dermatologists in the early detection of melanoma, a critical factor in saving lives. The model is trained using the International Skin Imaging Collaboration (ISIC) dataset, which includes a diverse collection of skin lesion images classified into various disease types, including melanoma.

## Objectives
- **Develop an automated system** for melanoma detection to support dermatological assessment.
- **Implement advanced deep learning algorithms** that classify melanoma from dermoscopic images, leveraging CNN architectures such as ResNet50.
- **Achieve high diagnostic accuracy**, enhancing clinical workflows and enabling rapid assessments.

## Dataset
- The model uses publicly available datasets containing dermoscopic images.
- The project supports data augmentation and preprocessing to address class imbalance and improve model generalisation.

## Workflow Overview

1. **Image Preprocessing**
   - Resize images for uniform input size (e.g., $$28 \times 28$$ or as required by the chosen model).
   - Convert images to grayscale or apply colour normalisation as needed.

2. **Data Splitting**
   - Stratified split into training and test sets, preserving label distribution.

3. **Model Architecture**
   - Implement CNN-based models.
   - Use transfer learning for efficiency and improved accuracy.
   - Employ activation functions such as ReLU and Softmax for classification layers.

4. **Training**
   - Model training utilizes early stopping and data augmentation.
   - Track metrics including accuracy, sensitivity, and specificity for model evaluation.

5. **Deployment**
   - Optional deployment: a web application using Python frameworks (e.g., Flask) for clinical use, enabling image upload and real-time inference.


## Contributing
Pull requests are welcome. 

## License
This project is licensed under the MIT License.


