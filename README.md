# yolo_object_detection
Gun detection using YOLO5


Dataset:
 https://www.kaggle.com/datasets/issaisasank/guns-object-detection

Yolov5: 
 https://github.com/ultralytics/yolov5
 clone cmd: !git clone https://github.com/ultralytics/yolov5

preparing data yolo required format and do predictions. 
Backend is openvc.
Model is saved as onnx foramt.
used opencv deep neural nerwork NMSBoxes(Non Maximum suppression) to remove/filter redudant boxes.
Draw dredicted bounding boxes.
