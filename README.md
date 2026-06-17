# Transfer-Learning-Surface-Defect
Problem Statement: Automatically classify surface defects in steel materials using real-world industrial image data and a transfer learning approach. Surface defects such as cracks, scratches, inclusions, and pits commonly occur during manufacturing processes and can significantly affect product quality. Manual inspection of these defects is time-consuming, inconsistent, and difficult to scale.

Flow Diagram:
<img width="282" height="1398" alt="image" src="https://github.com/user-attachments/assets/56fbe4c9-3810-42d1-a70c-5da6930c59aa" />


Tasks:
- Data Loading & Preparation
  - Dataset understanding & structure
     - Load images & labels
     - Check & visualise class distribution
  - Data preprocessing & transformation
     - Apply image transformations
     - Create DataLoaders for both training & validation datasets
- Transferring Knowledge & Model Training
  - Pretrained model selection
     - Load pre-trained model
     - Freezing strategy and classifier design
     - Verify final frozen and trainable parameters
  - Model training
     - Training configuration
     - Model training loop
     - Visualise the training loss across epochs throughout the training process
- Evaluation & Final Predictions
  - Evaluation metrics & bias-variance tradeoff
     - Calcualte appropriate evaluation metrics to assess model performance
     - Dataset diagnostics
  - Prediction analysis
     - Visualise prediction on a few sample images from validation set
- Conclusion
 - Conclusion & insights
     - Conclude with the insights drawn and final outcomes & results. include teh details of your model selection, freezing and evaluation processes

Python libraries used:
- OS
- Numpy
- Tensorflow
- Collections
- json (to handle JSON data)
- joblib (to save where required)
- random
- seaborn
