# Week-5: Computer Vision with YOLOv8

## 05WT1 - Dataset Annotation

* Installed and configured Label Studio in a virtual environment
* Annotated training and validation images
* Generated YOLO label files
* Prepared `train.txt`, `val.txt`, and `data.yaml`

---

## 05WT2 - Image Preprocessing

* Resized dataset images using FFmpeg
* Preserved aspect ratio to maintain YOLO normalized annotations
* Prepared optimized images for training

---

## 05WT3 - YOLOv8 Training

* Trained a pretrained YOLOv8 model on the custom dataset
* Monitored training and validation loss across epochs
* Generated custom trained weights (`best.pt`)

---

## 05WT4 - Object Detection

* Used trained weights for inference on test images
* Detected custom classes such as person, car, and bike
* Saved prediction outputs with bounding boxes

---

## 05WT5 - Demo Video Generation

* Converted prediction outputs into video format using FFmpeg
* Generated a final demo showcasing automated object detection results

---

## Tools & Technologies

* Python
* YOLOv8
* Label Studio
* FFmpeg
* OpenCV
* Ultralytics

---

## Output

* Custom YOLOv8 trained weights
* Detection outputs with bounding boxes
* Demo video generated from predictions

