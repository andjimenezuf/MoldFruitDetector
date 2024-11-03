# Fresh and Rotten Fruit Classification Model

This project is a deep learning model designed to classify fresh and rotten fruits across six categories: fresh apples, fresh oranges, fresh bananas, rotten apples, rotten oranges, and rotten bananas. By leveraging a pretrained model with transfer learning, this project achieves a high validation accuracy, allowing for accurate classification of fruit freshness.

## Project Overview

The goal of this project is to build a reliable model that can differentiate between fresh and rotten fruits in various categories using image data. The model is trained using a dataset from Kaggle, with categories organized by fruit type and freshness. The project explores the use of transfer learning, data augmentation, and fine-tuning to achieve high classification accuracy.

### Key Concepts Learned
- **Transfer Learning**: Utilized a pretrained model on ImageNet, which provided a strong foundation for image recognition tasks. By repurposing this model, training time was reduced and accuracy improved.
- **Data Augmentation**: Enhanced the dataset through techniques like rotation, flipping, and brightness adjustment, helping the model generalize better to new images.
- **Fine-Tuning**: After initial training, unfreezing the model's base layers and fine-tuning with a low learning rate allowed for targeted improvements without losing the pretrained knowledge.
- **Multi-Class Classification**: Used categorical cross-entropy as the loss function, which is ideal for problems with multiple categories.
- **Model Evaluation**: Measured model performance using accuracy and loss metrics, with a target accuracy of at least 92%.

### Project Structure
- **Data Preparation**: Loading and preprocessing images, setting up training and validation datasets, and applying data augmentation.
- **Model Setup**: Using a pretrained model, modifying the architecture for six-category classification, and compiling it with the appropriate loss and optimizer settings.
- **Training**: Training the model with an initial frozen base, then fine-tuning with a low learning rate.
- **Evaluation**: Achieved a final validation accuracy of 95.44%, surpassing the target and demonstrating effective classification performance.

### Results
The final model achieved a validation accuracy of **95.44%**, indicating strong performance in distinguishing between fresh and rotten fruits across all six categories.
