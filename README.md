# OneButtonDeepLearning
This repo provides the Graphic User Interface for Deep Learning models to realize "One-button" to use these models.
In detail, it provides plugins in [ImagePy](https://github.com/Image-Py/imagepy) to run the DL models.

让深度学习算法触手可及、一键调用，不必每次在命令行进行复杂配置。

# Usage
Download the model folder, and place it in the `imagepy/plugins` folder.
Then the menu for this model will appear in the imagepy menu bar.

只需将要使用的模型文件夹复制到`imagepy/plugins`文件夹下，再次启动ImagePy后即可在菜单栏看到该算法。

## Optional 
If the environment is not configured for the model, just enter its `menus` folder, and run:
~~~~
pip install -r requirements.txt
~~~~ 

# Current available models

## OCR
[PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR) aims to create multilingual, awesome, leading, and practical OCR tools that help users train better models and apply them into practice.

![ocr-demo](OCR/menus/OCR/demo.png)

## YOLOv5
[YOLOv5](https://github.com/ultralytics/yolov5) is a family of compound-scaled object detection models trained on the COCO dataset.

![yolov5-demo](YOLOv5/menus/YOLOv5/demo.png)

## Face Detection
[InsightFace](https://github.com/deepinsight/insightface) is an open source 2D&3D deep face analysis toolbox, and efficiently implements a rich variety of state of the art algorithms of face recognition, face detection and face alignment, which optimized for both training and deployment.

![face-demo](FaceAnalysis/menus/Face/demo.png)

## Cellpose
[Cellpose](https://github.com/MouseLand/cellpose) is a generalist algorithm for cell and nucleus segmentation.

![cellpose-demo](Cellpose/menus/Cellpose/demo.png)

## BulkSeg
[BulkSeg](https://github.com/qixinbo/BulkSeg) which is inspired by Cellpose, is a fast and generalist algorithm for segmenting bulk-like objects.
![bulkseg-demo](BulkSeg/menus/BulkSeg/demo.png)
