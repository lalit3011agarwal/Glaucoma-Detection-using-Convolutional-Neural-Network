# Glaucoma Detection using Convolutional Neural Network

Created By: Lalit Agarwal

## Dataset Exploration
- Retinal fundus image dataset for glaucoma detection obtained from Kaggle.
- Dataset contains both glaucoma-affected (positive) and healthy (negative) retinal images.
- Challenges include limited availability of labeled datasets and potential lack of diversity in clinical scenarios.

## Preprocessing
Below are the preprocessing steps performed on the dataset:
- Removal of low-quality or duplicate images
- Image resizing to uniform dimensions (e.g., 224x224 pixels)
- Normalization of pixel values
- Data augmentation techniques (flipping, rotating, shifting)
- Dataset split into training, validation, and test sets

## Model Architecture
- Employed ResNet-50 architecture pre-trained on ImageNet
- Fine-tuned for specific task of glaucoma detection
- Model configuration:
  - Batch size: 16
  - Epochs: 30
  - Optimizer: Adam with learning rate of 0.00001
  - Loss function: Binary cross-entropy

## Performance Metrics
- Training Accuracy: 66.50%
- Validation Accuracy: 75.38%
- Training Loss: 1.0553
- Validation Loss: 0.5383

## Challenges and Limitations
- Data Scarcity: Limited availability of large, diverse, labeled datasets
- Model Complexity and Interpretability: Deep learning models often lack transparency in decision-making
- Lack of Explainability: Difficulty in explaining model predictions in a medical context
- Limited Diversity in Datasets: May not capture full range of clinical scenarios and patient demographics

## Potential Model Improvements
- Develop more explainable AI models to enhance clinical trust and acceptance
- Expand datasets to include more diverse patient demographics and clinical scenarios
- Implement systems for long-term monitoring and follow-up of glaucoma patients
- Integrate AI-powered diagnostic tools into clinical workflows and electronic health records
- Collaborate with regulatory bodies for validation and approval of AI-based diagnostic systems

## Future Directions
- Explore advanced techniques for model interpretability
- Investigate multi-modal approaches combining different imaging modalities
- Develop strategies for continuous learning and model updating with new data
- Research on personalized risk assessment and treatment recommendations
- Conduct large-scale clinical trials to validate model performance in real-world settings
