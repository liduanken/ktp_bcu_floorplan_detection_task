# Object Detection using Floorplan Dataset
## Detect rooms, windows and doors

I utilised a Faster RCNN network to achieve a detection algorithm for detecting rooms, windows and doors on floorplans.
![Model](figs/Fast-RCNN-Rest50.jpg)
Figure: Fast RCNN with ResNet50 as a Backbone

![Model](figs/Processed_floorplan.png)
Figure: An example of processed floorplans

- Faster R-CNN model fine-tuning

- 82.86% MAP at 50% IoU threshold on test set

- NMS post-processing to further improve prediction
