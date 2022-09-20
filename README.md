# Traffic-light-management-System
We make use of the YOLO v5 object detection model to process the numbers of cars, buses , trucks etc at any signal, and then we feed that data to a function that calculates the appropriate green signal time , based on traffic density and a few other parameters such as average crossing times. This helps in efficient regulation of traffic across junctions.

The time for each signal is shown in the RYG format in the form of a nested list.

We used Transfer Learning on a Yolov5s (trained on COCO dataset), and trained it on a custom dataset. The thresholds for IOU and NMS were data driven. 
