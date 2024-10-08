# Emotion Recognition through Facial Expression

## Project Overview
This project is aimed at developing a model for predicting human emotions based on facial gestures using a Convolutional Neural Network (CNN). We used a dataset from Kaggle's "Facial Expression Recognition" challenge to train and evaluate our model. The project was completed as part of our academic coursework at Kärnten University of Applied Sciences.

## Authors
- Ana Maria Jaramillo - [GitHub Profile](https://github.com/Saghar1261)
- Saghar Ghaffari - [GitHub Profile](https://github.com/Anmjaramillo412)

## Project Objectives
- Develop a model to predict human emotions from facial expressions.
- Implement CNN architectures for emotion recognition.
- Utilize data augmentation techniques to enhance model performance.
- Measure the performance using metrics like accuracy, loss, and confusion matrix.

## Dataset
The dataset used for this project is the **"Facial Expression Recognition"** dataset from Kaggle. It contains 48x48 pixel grayscale images of faces, classified into seven different emotions:
- 0: Angry
- 1: Disgust (removed due to imbalance)
- 2: Fear
- 3: Happy
- 4: Sad
- 5: Surprise
- 6: Neutral

For this study, we focused on six emotions (removing "Disgust" for better balance).

## Model Implementation
We experimented with several CNN architectures, using techniques like:
- Convolutional layers with varying filter sizes.
- Batch normalization to stabilize the learning process.
- Max pooling to reduce spatial dimensions and extract important features.
- Dropout for regularization to prevent overfitting.
- Different optimization strategies (e.g., Adam, RMSprop) and learning rates.

The best-performing architecture was evaluated on a test dataset, including additional self-collected data.

## Results
The model's performance was evaluated using metrics such as:
- **Accuracy**: Measured for training, validation, and test sets.
- **Loss**: Monitored during training to assess convergence.
- **Confusion Matrix**: Visualized the performance for each emotion.

The results indicate that emotions like **Happiness** and **Surprise** were recognized with higher accuracy, while emotions like **Fear** had more misclassifications.

## Files and Notebooks
You can find the detailed implementation in the Jupyter notebooks provided:
- ([https://drive.google.com/drive/folders/1OOT7Td6dqIJA9Bw5wg7jxapQlNttrnvc]

