# Object-Tracking-PyTorch-YOLOv5-DeepSort

This repo represents implimentation of YOLOv5 and DeepSort in Pytorch for object tracking


![Demo](img.gif)


# Watch Demo:

https://www.youtube.com/watch?v=SnoTsGAR9aY


## Steps:
``pip install -r yolov5/requirements.txt``

- CPU Only
``conda install pytorch==1.7.0 torchvision==0.8.0 torchaudio==0.7.0 cpuonly -c pytorch``

``pip install easydict``

``python detect_sort.py --weights yolov5s.pt  --img 640  --source pedestrian.mp4``