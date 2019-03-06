# PICWD: A Large-Scale Dataset for Automated Photo Identification of Chinese White Dolphins

![IMG](https://github.com/PICWD/PICWD/blob/master/123.jpg)

download link：
---------------

File structure：
---------------
### QinZhou

|Filename|Content|
|:---|:---|
|Annotations|37297 xml files (each xml file includes bndbox_id, bndbox_coordi, score, id of all fins in each image) |
|ImageSets\Main|train.txt includes all image names for training, val.txt includes all image names for validation|
|JPEGImages|37297 jpg files |
|Segmentation|30786 png files (each png file saves semantic segmentation information corresponding with cropped images in bndbox)|
|QZ_img_info.xls|the same as information in 'Annotations' file, but in one xls file|
|QZ_segmentation_intact.xls|it descrisbes whether each segmentation area is intact|

