# YOLOv7 and EfficientNet Based Program For Detecting and Classifying Fish in Aquaculture Environment

## Description
The "YOLOv7 and EfficientNet Based Program for Detecting and Classifying Fish in Aquaculture Environment" project represents a pioneering effort at the intersection of computer vision, deep learning, and aquaculture. This innovative program is designed to revolutionize the way fish are monitored and managed in aquaculture settings, offering enhanced accuracy and efficiency in fish detection and classification. The goal of this study is to create a program that uses deep learning algorithms for identifying and categorizing fish in an aquaculture setting. YOLOv7 is implemented as a fish detection approach in this work, while EfficientNet is used as a classification method to identify or classify the fish species.

## Data
The data used in the study was obtained from Kaggle https://www.kaggle.com/datasets/crowww/a-large-scale-fish-dataset with the name "A Large Scale Fish Dataset". 

## Method
The proposed method, started with labeling the augmented images by annotating  9 classes of fish. The annotated images are then fed to the YOLOv7 network for object detection. Meanwhile, EfficientNet-B0 is used as the base model by applying transfer learning. The result of the model is then evaluated based on accuracy, precision, recall, and mAP (Mean Average Precision)  metrics.
![rm architecture drawio (1)](https://github.com/kaylaadira/fish_detection/assets/130166504/dfac5996-9feb-41f8-b46d-796889b96387)

## Result
<img alt="image" src="https://github.com/kaylaadira/fish_detection/assets/130166504/174bae4b-8646-4e3e-98f8-f727c0b55ab7">

<img alt="image" src="https://github.com/kaylaadira/fish_detection/assets/130166504/de2245f7-0282-4bc5-af41-3db70db049c7">

Using YOLOv7 and EfficientNet, we create a deep learning-based algorithm for identifying and categorizing fish in the aquaculture environment. The results of the fish detection have an mAP score of 0.994 with the accuracy of 0.9919 on the train set and 0.8139 on the test set. 
