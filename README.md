# Mask R-CNN for Object Detection and Segmentation using TensorFlow 2 (2.6.0)

## Introduction
The [MASK-RCNN-TF2.6.0](https://github.com/winovation/Mask-RCNN-TF2.6.0) project edits the original [Mask_RCNN](https://github.com/matterport/Mask_RCNN) project, which only supports TensorFlow 1.0, so that it works on TensorFlow 2 (Especially 2.6.0). Based on this new project, the [Mask R-CNN](https://arxiv.org/abs/1703.06870) can be trained and tested (i.e make predictions) in TensorFlow 2. The Mask R-CNN model generates bounding boxes and segmentation masks for each instance of an object in the image. It's based on Feature Pyramid Network (FPN) and a ResNet101 backbone.

Compared to the [Mask_RCNN](https://github.com/matterport/Mask_RCNN) and [Mask-RCNN-TF2](https://github.com/ahmedfgad/Mask-RCNN-TF2), this project edits the following 2 modules:

1. `model.py`
2. `utils.py`

This project is tested against **tensorflow 2.6.0**, **keras 2.6.0**, and **python 3.7.13**. Note that the project will not run in TensorFlow 1.0.

## Reference
https://github.com/matterport/Mask_RCNN  
https://github.com/ahmedfgad/Mask-RCNN-TF2
