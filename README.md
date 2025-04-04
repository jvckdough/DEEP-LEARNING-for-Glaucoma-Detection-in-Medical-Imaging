# Glaucoma-Detection-Using-Deep-Learning
This study presents a deep learning-based approach for automated glaucoma detection using VGG16, a convolutional neural network (CNN) pre-trained on ImageNet. The model was trained on 650 retinal OCT images, with data augmentation techniques applied to enhance generalization. The dataset was split into 70% training, 15% validation, and 15% test sets, ensuring balanced representation across classes.

After 23 epochs, the model achieved a test accuracy of 84.46%, with a macro-average F1-score of 0.84. The classification report indicates strong precision (0.87) and recall (0.85) across both glaucoma-positive and negative classes. The confusion matrix highlights a sensitivity of 97% for Class 0 (non-glaucoma) and 72% for Class 1 (glaucoma), indicating robust detection capabilities but room for improvement in recall for glaucoma cases.

This research demonstrates the feasibility of transfer learning and data augmentation for improving deep learning-based glaucoma screening. Future work will explore alternative architectures, hyperparameter tuning, and larger datasets to further enhance performance and clinical applicability.

## Data
The dataset used can be found here:
https://www.kaggle.com/datasets/sshikamaru/glaucoma-detection

## Run File:
Open .ipynb file in jupyter notebook. Download the data from  https://www.kaggle.com/datasets/sshikamaru/glaucoma-detection and be sure to adjust file paths to directory of dataset. 

## Collaboration:
Please email me at jackdoughty63@gmail.com with ideas on how to improve the model, feedback, or other collaborations.
