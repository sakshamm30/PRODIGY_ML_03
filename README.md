🐶🐱 Cats vs Dogs Classification using Support Vector Machine (SVM)

This project implements a Support Vector Machine (SVM) model to classify images of cats and dogs. The images are preprocessed by converting them to grayscale, resizing them, and extracting Histogram of Oriented Gradients (HOG) features before training the classifier. The trained model is then evaluated using standard machine learning metrics and can predict whether a new image contains a cat or a dog.

🚀 Features
Image preprocessing (grayscale conversion and resizing)
HOG feature extraction for image representation
Binary classification using Support Vector Machine (SVM)
Model evaluation with:
Accuracy
Precision
Recall
F1-Score
Confusion Matrix
Prediction on custom test images
Compatible with Google Colab and Jupyter Notebook
🛠️ Technologies Used
Python
OpenCV
NumPy
Scikit-learn
Scikit-image
Matplotlib
📂 Dataset

The project uses the Cats vs Dogs image dataset containing labeled images of cats and dogs for binary classification.

📊 Workflow
Load and preprocess the dataset.
Resize images and convert them to grayscale.
Extract HOG features from each image.
Split the data into training and testing sets.
Train an SVM classifier.
Evaluate the model using various performance metrics.
Predict the class of unseen images.
📈 Model Performance

The model achieves approximately 73% accuracy on the test dataset using HOG features and a linear SVM. Performance can be further improved through hyperparameter tuning, feature engineering, or advanced deep learning approaches.
