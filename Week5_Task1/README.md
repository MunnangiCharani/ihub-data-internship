# Week 5 - Task 1 : YOLO Dataset Preparation

## Objective

The objective of this task is to prepare a labeled dataset for YOLO object detection training. The dataset contains training, validation, and test images extracted from a video source and annotated using Label Studio.

## Dataset Structure

```text
dataset/
│
├── train/
│   ├── train_images/
│   └── train_labels/
│
├── val/
│   ├── val_images/
│   └── val_labels/
│
├── test/
│   └── test_images/
│
├── data.yaml
├── train.txt
└── val.txt
```

## Annotation Format

The label files are stored in YOLO format:

```text
<class_id> <x_center> <y_center> <width> <height>
```

All coordinates are normalized between 0 and 1.

## Classes Used

* 0 : person
* 1 : car
* 2 : bike

## Metadata Files

### data.yaml

The `data.yaml` file contains:

* training image path
* validation image path
* number of classes
* class names

### train.txt and val.txt

These files contain image paths for training and validation datasets respectively.

### Label Files

Each image has a corresponding `.txt` annotation file generated using Label Studio.

## Tools Used

* FFmpeg
* Label Studio
* Google Colab
* GitHub

## Workflow

1. Extracted frames from video using FFmpeg
2. Split dataset into train, validation, and test sets
3. Annotated train and validation images using Label Studio
4. Exported annotations in YOLO format
5. Created YAML and TXT metadata files
6. Organized dataset structure for YOLO training

## References

* https://labelstud.io/guide/
* https://docs.ultralytics.com/datasets/detect/
