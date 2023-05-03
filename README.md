<h1> FaceMaskDetection_YOLO8

## About the Project
This algorithm is for face mask detection task through training the state-of-the-art YOLOv8. The training and testing datasets bounding box annotation is in YOLO format. I have trained both YOLOv8 medium and nano models to check the best results which is achieved through training medium model. 
More information about the algorithm is explained below.
  
## Requirements
  1. PyTorch version==1.7
  2. ultralytics for YOLOv8
  3. yolov8m.pt (medium) or yolov8n.pt (nano) model
  4. OpenCV (cv2)
  5. natsort library
  
  
 ## Files Description
  1. Download ultralics and yolov8m&n models from https://github.com/ultralytics/ultralytics
  2. Training, testing and validation data pathes as well as number of classes are added to data.yaml file 
  3. Run main.ipynb jupyter notebook 
  4. The best model and training data analysis will be automatically saved into runs file. 
  5. Import the best model best.pth to test with test data from test file.
  6. I have added a part of code to save test images or video into images in "frames" file. 
  7. The detection results are converted into video stream and saved into inferencedata file 
  
  
