# Digital Image Processing Project

## Topic: Brain Tumor Detection using Convolution Neural Network

### Team Members:
- **Saniya Joseph**
  - Reg No: 232BDA07
- **Harishma**
  - Reg No: 232BDA22

## Abstract:
This project proposes a brain tumor segmentation method utilizing a Convolutional Neural Network (CNN). MRI images undergo preprocessing, followed by CNN-based feature extraction for distinguishing between normal and tumor tissue. The trained CNN segments unseen MRI scans by classifying each pixel based on learned features, offering accurate tumor segmentation without manual feature engineering.

## Introduction:
Early and accurate diagnosis of brain tumors is crucial for effective treatment. Manual segmentation of brain tumors from MRI scans is time-consuming and prone to errors. This project presents a CNN-based approach for brain tumor segmentation, leveraging its ability to automatically learn features from labeled data, potentially improving segmentation accuracy and efficiency.

## Purpose:
The purpose is to develop an automated method for detecting and outlining brain tumors in MRI scans using CNNs. By eliminating manual segmentation, the approach aims to streamline diagnosis, reduce errors, and enhance the speed and accuracy of tumor detection for better patient outcomes.

## Literature Review:

| Year | Title | Author | Dataset Link | Methodology | Result | Conclusion |
|------|-------|--------|--------------|-------------|--------|------------|
| 2011 | Brain tumor detection using CNN | Sunil Kumar, Renu Dhir, Nisha | Combination of BR35H 2020 and Central Research UK datasets | CNN | Achieved up to 92% accuracy | Presented a novel method combining preprocessing and CNN-based segmentation for brain tumor detection. |
| 2019 | CNN for Brain Tumor detection | D.C Fedrianto, Soesanti, H.A Nugroho | Kaggle Brain MRI dataset | CNN | Achieved up to 93% prediction accuracy | Demonstrated the effectiveness of CNNs in classifying brain tumors from MRI images. |
| 2019 | Brain tumor detection using CNN | Tonmony Hossain, Fairuz Shadmani, Mohsena | BRATS dataset | CNN | Achieved up to 97.87% accuracy | Combined clustering, traditional classifiers, and CNN for brain tumor segmentation, emphasizing feature-based approaches. |
| 2022 | MRI Based brain tumor image detection using CNN based deep learning | Arkapravo Chattopadhyay, Mausumi Maitra | BRATS dataset | CNN | Achieved up to 99.74% accuracy | Refined CNN parameters and optimizer for improved tumor segmentation accuracy. |
| 2022 | Brain tumor detection using deep convolutional neural network | Md. Saikat Islam Khan, Anichur Rahman | BRATS dataset | CNN, Transfer learning | Achieved up to 96.74% accuracy | Combined MRI image processing with SVM for effective brain tumor detection. |

## Dataset Description:
The dataset comprises 4001 MRI scans categorized into four classes: Glioma, Meningioma, No Tumor, and Pituitary tumors. It includes axial, coronal, and sagittal views with a balanced split of 2891 images for training and 410 for testing, facilitating machine learning model development for accurate tumor segmentation.

## Methodologies:
The project employs a CNN architecture built with the Keras Sequential API for brain tumor segmentation. The CNN extracts features directly from MRI scans, comprising convolutional layers for feature extraction, pooling layers for dimensionality reduction, and fully-connected layers for classification. By training the CNN on labeled data, the model learns to accurately segment brain tumors in unseen MRI scans, eliminating manual feature engineering and leveraging spatial information for robust segmentation.

## Result:
The CNN model achieved approximately 90% accuracy on split validation data after training and monitoring for overfitting. Evaluation metrics like F1-score and exploration of data augmentation techniques could further enhance model performance.

## Conclusion:
This project introduces an automated method for brain tumor detection in MRI scans using CNNs. By eliminating manual intervention, the CNN-based approach offers faster and more reliable tumor segmentation, potentially leading to improved diagnosis and treatment outcomes.
