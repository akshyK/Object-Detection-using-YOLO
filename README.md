# Object-Detection-using-YOLO
A Object detection system trained using YOLO algorithm on a dataset of pictures taken from the hood of a car provided by drive.ai. It can detect 80 different classes of objects. Anchor boxes are chosen by exploring the training data to choose reasonable height/width ratios that represent the different classes. The YOLO architecture is: IMAGE (m, 608, 608, 3) -> DEEP CNN -> ENCODING (m, 19, 19, 5, 85). Non-ax supprssion is used to select the most suitable bounding box. 
