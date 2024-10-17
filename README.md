# Breast Cancer Diagnosis Using Deep Learning and Synthetic Data Generation
# Project Overview
Breast cancer is one of the most prevalent cancers worldwide, with millions of women being diagnosed every year. Early detection plays a critical role in improving survival rates, and mammography is one of the most effective screening tools available. However, identifying subtle abnormalities in mammogram images can be challenging due to the complexity and variability in breast tissue appearances.
# Key Features:
CNN-based Model: A deep learning model trained on real mammogram data to classify breast images as healthy or containing lesions (cancerous or non-cancerous).
Synthetic Data Generation: A Stable Diffusion model used to create synthetic mammogram images based on mammogram characteristics (e.g., view, density), expanding the dataset and improving model performance.
Data Augmentation: Techniques such as rotation, flipping, and zooming were applied to the dataset to prevent overfitting and increase model robustness.
High Accuracy: Achieved a final validation accuracy of 98% after retraining with synthetic data.
Healthcare Impact: Demonstrates the potential of AI and synthetic data to assist healthcare professionals in making more accurate diagnoses
# Results
After incorporating the synthetic data into the training process, the model’s performance improved significantly. The model initially achieved 50.50% accuracy, but after retraining with the expanded dataset, it reached an accuracy of 98% on the validation set.

