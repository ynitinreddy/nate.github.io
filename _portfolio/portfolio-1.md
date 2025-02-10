---
title: "Wildlife Detection from Aerial Images"
excerpt: "Study on small instances detection using the novel CBAM-YOLOv7 model <br/><img src='/images/cbam_yolo.jpg'>"
collection: portfolio
---

In this project, I introduced a novel CBAM-YOLO model by integrating the Convolutional Block Attention Module (CBAM) into the YOLOv7 framework to enhance wildlife detection in drone imagery, the dataset is from the paper [WAID: A Large-Scale Dataset for Wildlife Detection with Drones](https://www.mdpi.com/2076-3417/13/18/10397) by Mou et al. Additionally, I reproduced the original YOLOv7 architecture and conducted a comparative study to evaluate the effectiveness of CBAM-YOLO against both the baseline YOLOv7 and a modified SE-YOLO model. Through extensive experimentation on the WAID dataset, the study revealed that while CBAM-YOLO improved feature prioritization, SE-based attention mechanisms yielded superior results for this specific application. This research provides valuable insights into optimizing attention mechanisms for real-world object detection in conservation efforts. The code and report for the study can be found [here](https://github.com/ynitinreddy/CBAM-YOLOv7-Wildlife-Detection-in-Drone-Imagery).
