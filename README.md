# Numberplate-Detection
Numberplate detection using yolov5

here in prepare_data i have downloaded data and labels using urllib.
than i converted in darnet format which is must have to train any yolo model.
than i clone yolov5 model for training and first i have to install requirements using requirments.txt file.
than i just do training using yolov5 pytorch on google colab gpu and that's it, my model is ready which is best.pt
Now i can detect numberplate in any image or video in using yolo's detect.py file and in weights 
just pass best.pt and your result will be stored in inference folder in yolov5 folder.
