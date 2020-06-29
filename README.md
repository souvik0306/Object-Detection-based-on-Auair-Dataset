# Object-Detection-based-on-Auair-Dataset
The original code of this project refers to https://github.com/ultralytics/yolov3.

However, the dataset is quite different, the dataset of this project is https://bozcani.github.io/auairdataset.

We modified the size of anchor box according to the change of different images and objects in the dataset. This operation improves the model and then we got a better mAP.

There are 8 classes of objects in the dataset whcih is not hard to do the classification, however, the images were shot by drones so the size of objects in which is 

quite small. Therefore, as we all know that it's difficult for YOLO to predict small objects, so modifying the size of anchor boxes to be smaller could be helpful

for refression.
