# Competitions Summary

## Competition 1: Handwritten Digit Recognition
- **Model**: State-of-the-Art (SoTA) model used is CLIP4STR.
- **Approach**: Utilized Scene Text Recognition due to varied backgrounds and stroke thickness in the images.
- **Repository**: [CLIP4STR](https://github.com/VamosC/CLIP4STR)
- **Model Details**: CLIP-ViT-L-14

## Competition 2: IT001 Score Prediction
- **Features**: Created features for each student from the original dataset.
- **Libraries**: Used AutoML libraries such as H2OAutoML, AutoML sklearn, TPOTRegressor.
- **Achievement**: Achieved top 1 position.

## Competition 3: Motorcycle Classification
### Pipeline 1
- **Feature Extraction**: Used Dinov2 for feature extraction.
- **Models**: Trained LGBM and CatBoost models and combined them using a Voting model.
- **Achievement**: Achieved top 4 position.

### Pipeline 2
- **Finetuning**: Finetuned Dinov2-large.
- **Techniques**:
  - **GradScaler**: Used 16-bit floating point numbers instead of 32-bit to reduce tensor size and GPU memory requirements.
  - **DataParallel**: Distributed data and computation across multiple GPUs to reduce training time.
- **Training Environment**: Trained on Kaggle GPU T4 x2.
- **Achievement**: Achieved top 1 position.
