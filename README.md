# Optimized-U-Net-Model-for-Advanced-Road-Extraction-Using-Satellite-Images-

## Overview
HybridRoadSegNet is an optimized U-Net-based deep learning model designed for automatic road extraction from high-resolution satellite imagery. The model improves upon traditional U-Net architecture by integrating Batch Normalization, SeparableConv2D layers, and a hybrid loss function (Binary Cross-Entropy, Dice Loss, and Focal Loss) to enhance feature extraction, reduce class imbalance, and improve segmentation accuracy.

## Key Features
Optimized U-Net Architecture: Enhanced with SeparableConv2D for efficient computation and better feature learning.
Hybrid Loss Function: Combines BCE, Dice Loss, and Focal Loss to improve segmentation performance.
DeepGlobe Dataset: Trained and evaluated on the DeepGlobe Road Extraction Dataset for real-world applicability.
Performance Metrics: Achieves high Precision, Recall, F1-Score, and Intersection over Union (IoU) compared to state-of-the-art methods.
Applications: Useful for urban planning, autonomous navigation, disaster response, and geospatial analysis.


## Model Architecture
The architecture follows an encoder-decoder U-Net structure with skip connections and optimizations in feature extraction:

![final_unet](https://github.com/user-attachments/assets/b3766f1e-7dd2-49b5-80ab-627255911925)


## Performance Metrics
The proposed model outperforms existing methods such as DA-RoadNet, GOALF, and DCS-TransUperNet, achieving the highest Recall (73.53%), F1-Score (74.00%), and IoU (58.73%) on the DeepGlobe dataset.

Metric	Value |
Precision	74.47% |
Recall	73.53% | 
F1-Score	74.00% | 
Intersection over Union (IoU)	58.73%


![precision](https://github.com/user-attachments/assets/4bb7a0cc-0681-46ca-8d53-f588c35a4a61)
![IOU](https://github.com/user-attachments/assets/1623766e-5582-4f46-953a-e7d91de0af4f)
![f1_score](https://github.com/user-attachments/assets/76cb8d54-a890-4f1a-96d5-21b0630462e5)
![recall](https://github.com/user-attachments/assets/c01ce072-e18c-4e0f-bdf0-85d607fe122e)

## Example Predictions
Below are some sample outputs from the model, demonstrating its road extraction capability:
![1st_img](https://github.com/user-attachments/assets/9a40cb15-b93a-45b8-bb18-df7113e98914)
![3rd_img](https://github.com/user-attachments/assets/2d75211c-abc6-44d7-b0af-2279f587c0e2)
![2nd_img](https://github.com/user-attachments/assets/81a70a57-4d37-4080-9f94-d17658c12ff7)
