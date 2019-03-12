# PICWD: A Large-Scale Dataset for Automated Photo Identification of Chinese White Dolphins

![IMG](https://github.com/PICWD/PICWD/blob/master/framework.jpg)

Download link
---------------
#### Baidu Drive: [Dataset](https://pan.baidu.com/s/16dggemhlxTbsSULoOxA4mQ) (code：q4vb) 
#### OneDrive: [Dataset](https://a1od-my.sharepoint.com/:f:/g/personal/a373_my365_tech/EmX060kWLYNDma5I5qiH1cQBi0YUbaa_Rdb-6hegmieWsA?e=LFbybI)


File structure
---------------
### QinZhou

|Filename|Content|
|:---|:---|
|Annotations|37297 xml files (Each xml file includes bndbox_id, bndbox_coordi, score, id of all fins in each image.) |
|ImageSets\Main|train.txt, val.txt (train.txt includes all image names for training, and val.txt includes all image names for validation.)|
|JPEGImages|37297 jpg files (The names of the jpg files are arranged according to when they were taken.)|
|Segmentation|png files (Each png file saves semantic segmentation information corresponding with  each cropped image in bounding box.)|
|QZ_img_info.xls|It holds the same information as xml files in 'Annotations', but in one xls file.|
|QZ_segmentation_intact.xls|It descrisbes whether each segmentation area is intact corresponding with png files in 'Segmentation'.|

### ShanTou

|Filename|Content|
|:---|:---|
|Annotations|16216 xml files|
|ImageSets\Main|train.txt, val.txt|
|JPEGImages|16216 jpg files|
|Segmentation|png files|
|ST_img_info.xls| |
|ST_segmentation_intact.xls| |

Usage License
1. All images and their associated annotations in PICWD **can be used for academic purposes only, but any commercial use is prohibited.**  
2. We reserve the right to terminate researcher's use of the Dataset at any time.  
3. In all the related publications, please cite the paper “PICWD: A Large-Scale Dataset for Automated Photo Identification of Chinese White Dolphins”.
