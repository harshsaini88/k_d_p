# Kidney-Disease-Classification-MLflow-DVC

## Overview

This project predicts kidney diseases using deep learning techniques. It classifies kidney problems into four categories: normal, cyst, tumor, and stone.

## Methodology

I used the VGG-16 model, pretrained on a large dataset, to extract features from kidney images. Transfer learning fine-tuned the model for my dataset, improving its ability to detect different kidney conditions.

## Key Features

- **Modular Coding**: Organized code into modules for better maintenance and collaboration.
- **Pipeline Tracking with DVC**: Managed experiments efficiently with Data Version Control (DVC).
- **Experiment Tracking with MLflow**: Tracked model performance and parameters using MLflow.
- **Deployment on AWS**: Deployed the model on Amazon Web Services (AWS) for real-time predictions.

## Challenges and Future Directions

- **Model Optimization**: Tuning hyperparameters to enhance prediction accuracy.
- **Data Augmentation**: Increasing dataset diversity for better generalization.
- **Interactive Interface**: Developing a user-friendly interface for healthcare professionals.

## Conclusion

This project demonstrates the potential of deep learning in healthcare. By leveraging transfer learning and modern coding practices, I've built a robust solution for kidney disease prediction. Further optimization will enhance diagnostic capabilities.



# How to run?
### STEPS:

Clone the repository

```bash
https://github.com/harshsaini88/kideny_dieases_deep_learning
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n cnncls python=3.8 -y
```

```bash
conda activate cnncls
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```

```bash
# Finally run the following command
python app.py
```

Now,
```bash
open up you local host and port
```
