# Tennis-game-Analysis-object-detection-with-YOLO-family

This project set to achieve detection and classification of a small object, specifically a tennis ball in a sideview video footage.

A dataset of tagged video was provided for training purposes, the videos were being short form different angles,
specifically left and right points of view, different lighting conditions and differently colored courts.


We picked a neural net with a YOLOv5 architecture, 
since it has low inference time and was trained on COCO dataset that includes sports balls as a class category.

Training process included 6600 training images (84.6%) and 1200 test images (15.4%) 

That resulted in a network with mAP @.5 = 0.725 on the test set.

Test inference video output :  

![Output sample](https://github.com/eldadoh/Tennis-game-Analysis-object-detection-with-YOLO-family/blob/main/assets/gif.gif)

Best weights results: 

![Output sample](https://github.com/eldadoh/Tennis-game-Analysis-object-detection-with-YOLO-family/blob/main/assets/Final_training_Result.JPG)


