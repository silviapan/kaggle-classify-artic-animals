## Overview of Artic Animal Image Classifier

This project focuses on classifying Arctic animals in images, where the animals often blend into their environments.
The images used in this project are either close-up shots or wider views where the animals are well camouflaged within their surroundings.
The goal is to accurately identify these animals despite the challenging conditions.

### Project
- Jupyter notebook for model training and evaluation
- Use FastAI and Pytorch
- The dataset is created by using DuckDuckGo Image search

## Model Training
The project uses a pretrained model to reduce training time. The training process involves fine-tuning the pretrained model on the Arctic animal dataset.

### Data Preprocessing
- Images are transformed by selecting random part of the image and crop to that randomized selection
![Screenshot 2024-08-19 at 11 51 54 AM](https://github.com/user-attachments/assets/47b026ba-2a6b-4b5d-b419-cc1c741cde0e)

### Evaluation
After training, a confusion matrix is generated to the analyze the model's performance
- The confusion matrix helps identify where the model is misclassifying the animals
![Screenshot 2024-08-19 at 11 51 09 AM](https://github.com/user-attachments/assets/c58a8e6c-7aa8-484a-b6e4-cb96da19084b)

## Future Work
- Clean up the data so the anaimals are accurately labeled
- Deploy model and build web app to accept user uploads
