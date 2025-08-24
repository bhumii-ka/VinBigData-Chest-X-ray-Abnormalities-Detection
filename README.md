# VinBigData-Chest-X-ray-Abnormalities-Detection

A deep learning project for automated detection of chest X-ray abnormalities using YOLOv11m object detection model.<br>
Kaggle Notebook Link: https://www.kaggle.com/code/bhumiikaa/x-ray-model-yolov11m

## Dataset
- **Source**: [VinBigData Chest X-ray Abnormalities Detection](https://www.kaggle.com/c/vinbigdata-chest-xray-abnormalities-detection) from Kaggle
- **Training Images**: 3,000 chest X-rays
- **Validation Images**: 700 chest X-rays
- **Classes**: 14 different chest abnormalities

### Medical Classes Detected
```
0: Aortic enlargement     7: Lung Opacity
1: Atelectasis           8: Nodule/Mass
2: Calcification         9: Other lesion
3: Cardiomegaly         10: Pleural effusion
4: Consolidation        11: Pleural thickening
5: ILD                  12: Pneumothorax
6: Infiltration         13: Pulmonary fibrosis
```

## Model Performance
- **Architecture**: YOLOv11m (Medium)
- **Training Duration**: 3 hours on Kaggle GPU
- **Epochs**: 100
- **Final mAP@50**: 0.228
- **Image Size**: 640×640 pixels

## 📋 Key Features
- ✅ Handles DICOM medical imaging format
- ✅ Multi-class detection for 14 chest abnormalities  
- ✅ Robust image preprocessing with percentile normalization
- ✅ Medical-grade bounding box predictions
- ✅ Confidence scoring for each detection

## 🔬 Results
The model successfully detects various chest abnormalities with reasonable accuracy for a medical AI system. Below are some inference examples:

<!-- Add your inference results here -->
#### Example detection showing multiple chest abnormalities with confidence scores
<img width="1200" height="800" alt="Screenshot 2025-08-25 002609" src="https://github.com/user-attachments/assets/67b1e08b-54e2-46a6-910e-c68736dcd2da" />

#### Successful detection of  Aortic enlargements and Cardiomegaly
<img width="870" height="500" alt="image" src="https://github.com/user-attachments/assets/8b21c33f-9b83-40a2-ba5c-7a0e31b4c719" />

