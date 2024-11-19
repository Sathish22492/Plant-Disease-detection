**Plant_Disease_Detection_from_Images**
**Project Overview**
Our project focuses on creating an intuitive Streamlit application that empowers users to upload images of plant leaves for accurate identification of plant diseases. Utilizing a Convolutional Neural Network (CNN) model, this tool is designed to support farmers and gardeners in swiftly diagnosing plant health issues, thereby facilitating timely interventions to enhance crop management.

**Dataset**
The dataset for our project comprises images categorized into 38 classes of plant species and their associated diseases, structured into training, validation, and testing subsets.

**Key classes include:**

Tomatoes (e.g., Late blight, Healthy, Early blight)
Grapes (e.g., Healthy, Black rot)
Oranges (e.g., Huanglongbing)
Potatoes (e.g., Healthy, Late blight)
Corn (maize) (e.g., Northern Leaf Blight)
Strawberries (e.g., Leaf scorch)
Other classes such as Peaches, Apples, Soybeans, Squash, Blueberries, and Cherries.
This structured dataset enables effective training and evaluation of machine learning models for plant disease detection.

**Download the Dataset**
You can download the dataset from this link: New Plant Diseases Dataset.

**Objectives and Goals**
Our project encompasses comprehensive development, including the establishment of an image upload interface using Streamlit, training the CNN model, and delivering a fully functional application that is easy to use. With a strong emphasis on real-world applicability, the project aims to equip farmers and gardeners with a rapid diagnosis tool, ultimately enabling them to respond effectively to plant diseases and optimize their agricultural practices.

**Approach**
1. Image Preprocessing
Implemented image preprocessing steps such as resizing, normalization, and augmentation to improve model performance. Utilized the New Plant Diseases Dataset from Kaggle, which contains images of plant leaves labeled with various diseases.

2. Disease Classification
Developed and trained a Convolutional Neural Network (CNN) model to classify plant diseases based on the uploaded images. Used the dataset from Kaggle for training and testing, applying techniques such as data augmentation and transfer learning to enhance model accuracy. Additionally, compared the performance of the Custom CNN model with at least three pretrained models to ensure the custom model outperforms existing ones. In our project, we have used these pre-trained models:
3. Performance Metrics
We are predicting the different plant diseases using our Custom CNN. Therefore, the following are the metrics that we used:

Accuracy: Measures the overall correctness of the predictions.

F1 Score: Balances performance across all classes by averaging F1 scores.

Precision: Measures how many of the positive predictions were correct.

Recall: Evaluates the ability of the model to capture all relevant positive cases.

4. User Interface Development
We have created a web interface using Streamlit that allows users to upload images of plant leaves. Implemented validations to check the type of file uploaded (e.g., JPEG, PNG) and ensured that the application is intuitive and user-friendly, with clear instructions and feedback for users.

5. Deployment and Testing
Deployed the Streamlit application using Streamlit. Conducted extensive testing to ensure the application correctly predicts plant diseases and handles various image inputs effectively.
