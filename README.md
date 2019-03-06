# PICWD: A Large-Scale Dataset for Automated Photo Identification of Chinese White Dolphins

![IMG](https://github.com/PICWD/PICWD/blob/master/123.jpg)

download link：
---------------

File structure：
---------------
### QinZhou

|Filename|Content|
|:---|:---|
|Annotations|37297 xml files (Each xml file includes bndbox_id, bndbox_coordi, score, id of all fins in each image.) |
|ImageSets\Main|train.txt includes all image names for training, and val.txt includes all image names for validation.|
|JPEGImages|37297 jpg files (The names of the jpg files are arranged according to when they were taken.)|
|Segmentation|30786 png files (Each png file saves semantic segmentation information corresponding with  each cropped image in bounding box.)|
|QZ_img_info.xls|It holds the same information as xml files in 'Annotations', but in one xls file.|
|QZ_segmentation_intact.xls|It descrisbes whether each segmentation area is intact corresponding with png files in 'Segmentation'.|

### ShanTou

|Filename|Content|
|:---|:---|
|Annotations|16216 xml files (Each xml file includes bndbox_id, bndbox_coordi, score, id of all fins in each image.) |
|ImageSets\Main|train.txt includes all image names for training, and val.txt includes all image names for validation.|
|JPEGImages|16216 jpg files (The names of the jpg files are arranged according to when they were taken.)|
|Segmentation|12610 png files (Each png file saves semantic segmentation information corresponding with each cropped image in bounding box.)|
|ST_img_info.xls|It holds the same information as xml files in 'Annotations', but in one xls file.|
|ST_segmentation_intact.xls|It descrisbes whether each segmentation area is intact corresponding with png files in 'Segmentation'.|

