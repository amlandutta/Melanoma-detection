# Melanoma-detection
# Skin Cancer Detection Using CNN

## General Information
This project focuses on the development of a Convolutional Neural Network (CNN) model for the detection of various types of skin cancers. Skin cancer, particularly melanoma, is a severe medical condition that requires early detection and intervention for effective treatment. Traditional methods of diagnosis often rely on visual inspection by dermatologists, which can be time-consuming and subjective. Therefore, the aim of this project is to leverage deep learning techniques to create an automated system capable of accurately detecting skin cancer from images.

### Background
Skin cancer, including melanoma, basal cell carcinoma, and squamous cell carcinoma, is one of the most prevalent forms of cancer globally. Early detection is crucial for successful treatment and improved patient outcomes. However, manual diagnosis by dermatologists can be prone to errors and may lead to delays in treatment. Automated systems based on deep learning algorithms offer a promising solution to improve the accuracy and efficiency of skin cancer detection.

### Business Problem
The business problem addressed in this project is the need for an automated system that can accurately detect various types of skin cancers from images. Such a system would significantly reduce the time and effort required for diagnosis, enabling early intervention and improving patient outcomes. Additionally, it could serve as a valuable tool for healthcare professionals, particularly in regions with limited access to dermatologists.

### Dataset
The dataset used in this project consists of images of different types of skin lesions, including melanoma, nevus, basal cell carcinoma, squamous cell carcinoma, and others. The images were obtained from the International Skin Imaging Collaboration (ISIC) dataset. Each image is labeled with its corresponding disease category, allowing for supervised learning of the CNN model.

## Conclusions
1. The developed CNN model achieved a training accuracy of 0.78 and a testing accuracy of 0.41. While the training accuracy indicates a reasonably good fit to the training data, the lower testing accuracy suggests that the model may not generalize well to unseen data.
2. Despite the relatively high training accuracy, the model's performance on the testing dataset is suboptimal, indicating potential overfitting.
3. Further analysis is required to identify the underlying causes of the model's poor performance on the testing dataset. This may involve exploring data augmentation techniques, fine-tuning the model architecture, or addressing class imbalances in the dataset.
4. The class-wise accuracies reveal variations in the model's performance across different disease categories. This information can be used to prioritize improvements in the detection of specific types of skin cancers.

## Technologies Used
- TensorFlow 2.0
- Matplotlib
- NumPy

## Acknowledgements
- This project was inspired by the need for improved methods of skin cancer detection.
- The ISIC dataset provided valuable labeled image data for training and evaluation.
- References: [International Skin Imaging Collaboration (ISIC) Dataset](https://www.isic-archive.com/)

## Contact
Created by Amlan Dutta- feel free to contact me!
