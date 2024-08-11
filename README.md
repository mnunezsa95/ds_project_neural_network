# Age Verification Model for Alcohol Sales Compliance

## Overview
Good Seed, a supermarket chain, is leveraging Data Science to ensure compliance with alcohol laws by preventing the sale of alcohol to underage individuals. This project focuses on evaluating data science techniques for accurate age verification through the analysis of photographs taken in the checkout area.

## Description
The project involves building and evaluating a model to verify individuals' ages based on photographs. The dataset includes images labeled with corresponding ages, which will be used to develop and test the age verification model. The ultimate goal is to help Good Seed comply with legal regulations and prevent the sale of alcohol to minors.

The images in the dataset may have minor rotations, but significant rotations or black edges due to cropping could affect model accuracy. The project's approach involves using computer vision methods to analyze these photographs and determine the age of the individuals.

## Objectives
- Develop a model to accurately predict ages from photographs of individuals purchasing alcohol.
- Evaluate the effectiveness of the model in verifying ages, with a focus on accuracy and consistency.
- Ensure the model can handle minor image rotations and prevent potential issues like black edges or cropping that might impact performance.
- Provide insights into the model's performance and suggest areas for further improvement.

## Libraries
- pandas: For data manipulation and analysis.
- numpy: For numerical operations.
- tensorflow: For building and training the deep learning model.
- matplotlib: For visualizing training results and model performance.
- tensorflow.keras: Includes modules for image preprocessing, model building, and optimization.

## Conclusion
The Sequential model built using the ResNet50 architecture was trained with the Adam optimizer at a learning rate of 0.0005. The training results indicate a promising trend, with the mean absolute error (MAE) consistently decreasing over epochs for the training dataset, reflecting effective learning and optimization.

For the test dataset, MAE showed variability, with occasional increases, suggesting less consistency in performance on unseen data. Despite this, the model generally performed well, maintaining an MAE below 8 for most epochs. The results highlight the potential of the ResNet50-based model and the Adam optimizer, while also pointing out the need for further refinement to improve stability and generalization on test data.
