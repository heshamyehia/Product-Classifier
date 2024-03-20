Product Image Classifier Readme
Overview
This project implements a product image classifier using deep learning techniques. The classifier categorizes product images into predefined categories.

Approach
Initially, ResNet50 was used with only the top layers removed. However, due to poor accuracy, fine-tuning was applied to some layers.
Data Collection and Preprocessing: Product images are collected and preprocessed, including resizing and format conversion.

Model Selection and Architecture: Initially, ResNet50 with only the top layers removed is used for transfer learning. However, due to poor accuracy, fine-tuning is applied to some layers.

Model Training: The model is trained on the dataset with data augmentation to enhance generalization.

Model Evaluation: The trained model is evaluated on a separate test dataset to assess performance.

Model Deployment: The trained model can be deployed for inference to categorize new product images.

Functionality
Training: Users can train the model on their dataset.
Model Selection: Choose between ResNet50 and DenseNet121 for the base model.
Data Augmentation: Apply augmentation techniques for better model generalization.
Model Fine-tuning: Fine-tune the model for better performance.
Model Evaluation: Assess the model's accuracy using test data.
Model Saving: Save the trained model for future use.
Inference: Deploy the model for categorizing new images.
Conclusion
The product image classifier efficiently categorizes product images, demonstrating high accuracy and generalization ability, suitable for various applications in e-commerce and retail.
