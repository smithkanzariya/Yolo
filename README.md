![detection1](https://user-images.githubusercontent.com/48116910/126133426-d4e186c9-809f-4fc9-a050-da1ed9341c08.jpg)
# yolov4_object_object_detection
Darknet Repo ==> https://pjreddie.com/darknet/
pretrained weights ==> https://github.com/AlexeyAB/darknet/releases/download/darknet_yolo_v3_optimal/yolov4.conv.137

run the model from darknet folder'

# Direction to run OD.py

clone this repository==> git clon "name of the repo"

# Download the pretrained weights
clone repository 
git clone https://github.com/AlexeyAB/darknet/releases/download/darknet_yolo_v3_optimal/yolov4.conv.137

Darknet Repo ==> https://pjreddie.com/darknet/

copy coco.name,yolov3.weights,yolov3.cfg files from above two repository and paste where OD.py is present

insert some images inside current directory where OD.py  present 

give the path of your image at line no 16
vc = cv2.VideoCapture"(./name of the image.jpg")

run the script OD.py 
command to run the script python OD.py
