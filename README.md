# Custom Dataset Training on YOLO-V8

## Overview
This project involves training a YOLOv8 (You Only Look Once version 8) object detection model on a custom dataset provided by BGSW (Bosch) during a 48-hour hackathon. The dataset includes raw images along with labeled annotations that include measurements of objects.

The primary goal of this project was to develop a robust object detection model that can accurately identify and localize objects within the provided images.

## Dataset
- The dataset provided by BGSW contains raw images.
- Labeled annotations include object measurements and labels.

## Data Annotation
To prepare the dataset for training, data annotation was performed using Roboflow. Roboflow is a platform that simplifies the process of annotating images for computer vision tasks like object detection. It helps streamline the data preparation workflow.

## Model Training
- The YOLOv8 architecture was used for object detection.
- Training involved feeding the annotated dataset into the YOLOv8 model and fine-tuning the model to accurately detect objects in the images.
- Model training typically includes setting hyperparameters, choosing an appropriate loss function, and optimizing the model's performance over multiple epochs.

## Evaluation
- The model's performance was evaluated using a separate test dataset to assess its accuracy and generalization.
- Common evaluation metrics include mean average precision (mAP), intersection over union (IoU), and accuracy.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Author
- GitHub: [Gururagavendra](https://github.com/Gururagavendra)

