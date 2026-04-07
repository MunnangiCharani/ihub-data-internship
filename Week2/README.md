# Week 2 Tasks

Task 1: Virtual Environment
- Created virtual environment using venv
- Activated environment using:
  venv\Scripts\activate

Task 2: Install Ultralytics
- Installed using:
  pip install ultralytics

Task 3: Object Detection using YOLOv8
- Ran YOLOv8 pretrained model on sample image
- Command used:
  yolo predict model=yolov8n.pt source=https://ultralytics.com/images/bus.jpg

Output
- Detected objects: person, bus, stop sign.
