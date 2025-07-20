# DEEP-LEARNING-PROJECT

COMPANY: CODTECH IT SOLUTIONS

NAME: HARINI P

INTERN ID: CT04DH454

DOMAIN: DATA SCIENCE

DURATION: 4 WEEKS

MENTOR: NEELA SANTHOSH KUMAR

# DESCRIPTION

EDITOR USED: VISUAL STUDIOS

For the second task in my Data Science internship, I worked on a basic yet important deep learning project using TensorFlow: image classification. The objective was to build a neural network model that could correctly classify images into various categories using Convolutional Neural Networks (CNN). This task helped me understand the real-world pipeline of working with image data—from loading and preprocessing images to training a model and visualizing predictions.

To begin with, I used TensorFlow and Keras to build the deep learning model. I also used matplotlib to visualize the images and training history, and numpy for numerical operations. Instead of downloading images from the internet, I used a dataset of images that I already had on my local system. These images were structured in a folder format with subfolders for each class label, which is a typical setup for classification tasks.

I started by importing the necessary libraries. Then I used TensorFlow’s image_dataset_from_directory function to load the images from the local directory. This function automatically reads the images, labels them based on the folder name, resizes them to a uniform shape, and prepares them in the format required for training. I split the data into training and validation sets with a fixed random seed to ensure consistency.

The CNN model I built consists of multiple convolutional layers with ReLU activation, followed by MaxPooling layers that reduce the spatial dimensions. These layers help the model learn different features of the images like edges, patterns, and textures. After flattening the output of the convolutional layers, I added a dense layer with softmax activation to output the class probabilities. The model was compiled with the Adam optimizer and sparse categorical crossentropy loss, and accuracy as the evaluation metric.

For training, I used 10 epochs and observed the model performance using the validation accuracy and loss plots. The results were decent considering this was a beginner-friendly dataset and model. I also included steps to display a batch of images from the dataset along with their predicted labels to visually confirm the performance of the trained model.

This task helped me get hands-on experience with the full deep learning pipeline. I learned how to structure datasets for image classification, build and train CNN models, and evaluate them both numerically and visually. I also became comfortable using key TensorFlow/Keras functions for working with image data.

From a practical point of view, the skills and concepts I gained from this task are applicable in several real-world areas. For example, this type of image classification system can be used in medical image analysis (like classifying X-rays), e-commerce (like categorizing product images), agriculture (like identifying plant diseases), security and surveillance, and many more fields. The ability to build such models is essential in the AI and computer vision domain.

Overall, this task was an eye-opener for me. It showed how deep learning is not just about theory but about real implementations that can solve meaningful problems. It made me realize the importance of data preprocessing, model tuning, and evaluation. More importantly, it gave me the confidence that I can build models from scratch using Python and TensorFlow, and understand the results thoroughly.

#OUTPUT

<img width="1920" height="935" alt="Image" src="https://github.com/user-attachments/assets/8f235497-0a1c-4ba0-ad89-7a8752b1c494" />

<img width="1920" height="946" alt="Image" src="https://github.com/user-attachments/assets/d173bfaa-2c59-402b-9f61-2b5f8a34f576" />

