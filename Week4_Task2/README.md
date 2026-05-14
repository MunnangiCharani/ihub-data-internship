# YOLO Object Detection Dataset

## Objective
The objective of this project is to create a labeled dataset for object detection using YOLO format. Frames were extracted from a video and annotated using Label Studio.

## Dataset Structure

dataset/
├── train/
│   ├── images/
│   └── labels/
│
├── val/
│   ├── images/
│   └── labels/
│
├── test/
│   └── images/
│
└── data.yaml

## Annotation Format

The label files are stored in YOLO format:

<class_id> <x_center> <y_center> <width> <height>

All coordinates are normalized between 0 and 1.

## Classes Used

0 - person  
1 - car  
2 - bike  

## Tools Used

- FFmpeg
- Label Studio
- Google Colab

## Metadata Files

### data.yaml
The `data.yaml` file contains:
- training dataset path
- validation dataset path
- number of classes
- class names

### Label Files
Each image has a corresponding `.txt` file containing object annotations in YOLO format.

## References

- https://labelstud.io/guide/
- https://docs.ultralytics.com/datasets/detect/
