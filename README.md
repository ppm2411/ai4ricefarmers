# ai4ricefarmers 🌾🤖  
**AI-Powered Rice Leaf Disease Detection System**

This project leverages deep learning to detect diseases in rice leaves, empowering farmers with fast, reliable, and automated diagnostics. Built using TensorFlow and advanced image processing techniques, this tool aims to classify rice leaf diseases using image data. Leveraging TensorFlow and image processing tools, the model distinguishes between three common diseases affecting rice crops:
- Bacterial Leaf Blight  
- Brown Spot  
- Leaf Smut

The goal is to support early diagnosis and disease-specific treatment recommendations in smart agriculture systems.


## 🔧 Technologies Used
- TensorFlow / Keras
- OpenCV
- PIL (Python Imaging Library)
- NumPy, Pandas
- Matplotlib, Seaborn
- CNN (Convolutional Neural Network)

Images were processed using OpenCV and PIL, and loaded efficiently using `glob`.

## 📌 Project Highlights
- **Implemented** a custom CNN for multi-class image classification.
- **Applied** data augmentation and preprocessing techniques to handle visual variations.
- **Trained** the model on a high-quality rice disease image dataset from Kaggle.
- **Visualized** training metrics and confusion matrix to evaluate model performance.



## 📊 Results

After training the Convolutional Neural Network (CNN) model, we obtained the following key results:

- **Classification Accuracy**: The model achieved a **highest accuracy of 83%** on the validation dataset after **25 epochs**, effectively distinguishing between the three rice leaf diseases:  
  - Bacterial Leaf Blight  
  - Brown Spot  
  - Leaf Smut
  
- **Confusion Matrix**: The confusion matrix reveals how well the model classified the rice leaf diseases:
  - **Row 1 (Bacterial Leaf Blight)**: 7 correctly predicted, 0 misclassified as Brown Spot, and 1 misclassified as Leaf Smut.
  - **Row 2 (Brown Spot)**: 1 misclassified as Bacterial Leaf Blight, 6 correctly predicted, and 1 misclassified as Leaf Smut.
  - **Row 3 (Leaf Smut)**: 0 misclassified as Bacterial Leaf Blight, 1 misclassified as Brown Spot, and 7 correctly predicted.


