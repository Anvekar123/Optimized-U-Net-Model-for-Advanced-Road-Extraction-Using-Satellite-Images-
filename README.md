# Optimized-U-Net-Model-for-Advanced-Road-Extraction-Using-Satellite-Images-

##Overview
HybridRoadSegNet is an optimized U-Net-based deep learning model designed for automatic road extraction from high-resolution satellite imagery. The model improves upon traditional U-Net architecture by integrating Batch Normalization, SeparableConv2D layers, and a hybrid loss function (Binary Cross-Entropy, Dice Loss, and Focal Loss) to enhance feature extraction, reduce class imbalance, and improve segmentation accuracy.

##Key Features
Optimized U-Net Architecture: Enhanced with SeparableConv2D for efficient computation and better feature learning.
Hybrid Loss Function: Combines BCE, Dice Loss, and Focal Loss to improve segmentation performance.
DeepGlobe Dataset: Trained and evaluated on the DeepGlobe Road Extraction Dataset for real-world applicability.
Performance Metrics: Achieves high Precision, Recall, F1-Score, and Intersection over Union (IoU) compared to state-of-the-art methods.
Applications: Useful for urban planning, autonomous navigation, disaster response, and geospatial analysis.

##Model Performance
The proposed model outperforms existing methods such as DA-RoadNet, GOALF, and DCS-TransUperNet, achieving the highest Recall (73.53%), F1-Score (74.00%), and IoU (58.73%) on the DeepGlobe dataset.
