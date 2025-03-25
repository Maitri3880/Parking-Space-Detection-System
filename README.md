# Car Parking Spaces Detection Using Satellite Images

## Overview
This project addresses the challenge of inefficient parking management on large campuses by developing a user-friendly car parking detection system using advanced computer vision techniques. The solution leverages satellite imagery and state-of-the-art deep learning models to provide real-time parking space availability updates.

## Dataset
- Total Images: 901
  - Original Images: 150
  - Augmented Images: 751
- Sources: Google Earth Engine, LCMS
- Preprocessing: 
  - Resizing and tiling
  - Filtering
- Dataset Augmentation:
  - Spatial transformations (flips, rotations)
  - Image quality adjustments (brightness, blur, noise)
    
## Technologies and Tools
### Machine Learning
- Object Detection Models: 
  - YOLOv11 (Enhanced feature extraction)
  - YOLO-NAS (Neural Architecture Search)
    
### Web Technologies
- Frontend: ReactJS
- Backend: Flask
- Deployment: AWS EC2, Netlify
- Database: PostgreSQL

## Model Performance
### Validation Results
| Model      | mAP    | Precision | Recall |
|------------|--------|-----------|--------|
| YOLOv11    | 83.6%  | 82.5%     | 78.2%  |
| YOLO-NAS   | 76.2%  | 81.4%     | 72.9%  |

## Live Demo
Explore the parking space detection system: 
[UMBC Parking Space Detection](https://umbc-parking-space-detection.netlify.app)

## Future Work
- Model Optimization
  - Hyperparameter tuning
  - Ensemble modeling
- Real-Time Processing 
