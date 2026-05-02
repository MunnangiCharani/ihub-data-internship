## Week 3 Task 1: Semantic Segmentation

### Description
Performed semantic segmentation on extracted frames using YOLOv8 segmentation model.

### Steps
- Used YOLOv8n-seg model
- Generated segmented images
- Converted images into video using FFmpeg
- Added background audio

### Output Video
https://drive.google.com/file/d/1PmNTuZf5PNm61_EYJYeUuh2zU5CJQogN/view?usp=sharing

### Performance Metrics
- Precision: 0.70
- Recall: 0.56
- mAP50: 0.65
- mAP50-95: 0.49

### Observations
- Segmentation provides pixel-level boundaries
- Accuracy depends on pretrained dataset
- Some frames had no detections

### Learning
Understood difference between object detection and segmentation and implemented full pipeline.
