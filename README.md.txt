# 🫁 Pneumonia Detection using CNN & Transfer Learning

## Problem
Early detection of pneumonia from chest X-rays is critical for timely treatment.

## Dataset
Kaggle Chest X-ray Dataset (Normal vs Pneumonia)

## Approach
- Built CNN from scratch
- Applied MobileNetV2 transfer learning
- Fine-tuned top layers
- Performed threshold tuning

## Model
- Backbone: MobileNetV2
- Input: 224x224 RGB
- Output: Binary classification

## Results
- Accuracy: ~84%
- Recall (Pneumonia): ~98%
- Threshold: 0.3

## Medical Relevance
Focused on minimizing false negatives to ensure patient safety.

## Future Work
- Grad-CAM explainability
- Larger dataset
- Deployment
