# NightOwls API

This is the SDK for NightOwls dataset (http://www.nightowls-dataset.org/)

We provide two APIs:
## 1) Python
The data format/API is fully compatible with MS-COCO (http://cocodataset.org/)

`load_training_data_demo.py` - script demonstrating loading the dataset

`eval.py` - pedestrian detection evaluation



## 2) Matlab
The data format is compatible with Caltech Pedestrians dataset (http://www.vision.caltech.edu/Image_Datasets/CaltechPedestrians/)

`demo.m` - script demonstrating loading the dataset

`matDetectionsToJson.m` - convert detections in .mat format into a JSON format (MSCOCO compatible)

`txtDetectionsToJson.m` - convert detections in .txt format into a JSON format (MSCOCO compatible)

