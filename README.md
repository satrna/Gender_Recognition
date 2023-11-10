# Gender_Recognition

## Overview
Gender recognition is a crucial task in computer vision, with applications ranging from human-computer interaction to targeted advertising. This project focuses on deploying a gender recognition model using state-of-the-art deep learning architectures. The models, based on VGG19, VGG16, ResNet50, ResNet101, and GoogleNet, are implemented using TensorFlow and Keras.

## Motivation
The motivation behind this project stems from the need for accurate and efficient gender recognition in various real-world scenarios. Understanding the gender of individuals in images has implications in industries such as retail, marketing, and security. By deploying a model capable of recognizing gender, we aim to provide a valuable tool for applications that require such insights.

## Model Architectures
The selected architectures have proven effectiveness in image classification tasks. Each architecture was fine-tuned to adapt to the specific requirements of gender recognition, ensuring optimal performance.

## Data Preprocessing
Pandas, a powerful data manipulation library, was employed for data preprocessing. The CelebA dataset, a diverse dataset with 5000 samples, was chosen for training. The dataset includes a wide variety of facial features, making it suitable for training a robust gender recognition model.

## Training
Transfer learning is utilized to leverage the pre-trained weights of the selected architectures on large image datasets. Fine-tuning is then applied on the CelebA dataset to specialize the model for gender recognition. TensorFlow and Keras provide the necessary tools for seamless model training.

## Deployment with Gradio
The model is deployed using Gradio, a user-friendly library that simplifies the process of creating interfaces for machine learning models. Gradio allows users to interact with the gender recognition model easily, providing predictions for input images in real-time.

## Results
Sample results, demonstrating the model's ability to accurately predict gender, are included in the project. These results showcase the practical application of the deployed model in real-world scenarios.

[Include images or links to sample results here]

## Deployment Link
The gender recognition model is deployed and can be accessed [here](https://s.id/GenderRecog).

## Future Work
The project is an ongoing effort, and future updates may include improvements to model performance, additional features, and support for a broader range of datasets.

## Contact
For any inquiries, collaboration opportunities, or feedback, please feel free to reach out via email:
[satrna0@gmail.com](mailto:satrna0@gmail.com)
