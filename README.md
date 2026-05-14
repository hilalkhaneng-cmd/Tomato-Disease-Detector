## Tomato Disease Classification Using Deep Learning

This project presents an intelligent tomato leaf disease classification system developed using Deep Learning and Computer Vision techniques. The model is designed to automatically identify different tomato plant diseases from leaf images captured in real-field agricultural conditions. Early and accurate disease detection can help farmers reduce crop loss, improve yield quality, and support precision agriculture practices.

The system uses the TensorFlow and the pre-trained EfficientNetB0 architecture for transfer learning. A custom classification head was added on top of the base model to improve disease recognition performance on tomato leaf datasets. The model was trained using realistic agricultural image augmentation techniques such as rotation, brightness adjustment, zooming, flipping, and shifting to simulate real environmental conditions.

To handle dataset imbalance, class balancing techniques and weighted training were applied. The dataset was automatically divided into training, validation, and testing subsets using stratified splitting to ensure fair evaluation. The project also includes performance analysis using accuracy, precision, recall, F1-score, confusion matrix visualization, ROC-AUC evaluation, and bootstrap confidence intervals.

The training process was divided into two phases:

1. Feature extraction using a frozen pre-trained model.
2. Fine-tuning selected layers to improve classification accuracy.

The final system is capable of predicting tomato diseases from new leaf images and returning the predicted disease class along with confidence scores. The trained model can be integrated into smart farming applications, mobile systems, or agricultural monitoring platforms for real-time disease diagnosis.

### Key Features

* Deep learning-based tomato disease classification
* Transfer learning using EfficientNetB0
* Real-field image augmentation
* Automatic train/validation/test splitting
* Class imbalance handling using class weights
* Performance visualization and evaluation metrics
* Model saving and deployment-ready prediction function
* Google Colab and Google Drive integration

### Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Google Colab

### Objective

The main objective of this project is to develop an accurate, efficient, and scalable AI-based solution for automatic tomato disease detection that can assist farmers and agricultural researchers in making faster and more reliable crop health decisions.
