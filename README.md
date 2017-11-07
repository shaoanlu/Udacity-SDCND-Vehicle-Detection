# Udacity-SDCND-Vehicle-Detection

https://shaoanlu.wordpress.com/2017/05/07/vihicle-detection-using-ssd-on-floybhub-udacity-self-driving-car-nano-degree/


result video: https://www.youtube.com/watch?v=Vc1g27yJgsw

![](https://github.com/shaoanlu/Udacity-SDCND-Vehicle-Detection/raw/master/result.gif)

## Descriptions

For keras 1

**ssd_download_essentials.ipynb:** Run this notebook first to download SSD implemnetation, moviepy package and target video from github.

**SSD_car_detection.ipynb:** Car detection using SSD is done in the first 6 cells.

For keras 2

**ssd_download_essentials_keras2.ipynb:** Run this notebook first to download SSD implemnetation, moviepy package and target video from github.

**SSD_car_detection_keras2.ipynb:** Car detection using SSD is done in the first 6 cells. This script will be in ./ssd_keras-master after running ssd_download_essentials_keras2.ipynb

Mask-RCNN

**Mask_RCNN_download_essentials.ipynb:** This notebook git clone Mask-RCNN from matterportm download projecty video and pip install essential packages.

**visualize_car_detection.py**: Utilities for visaulize Mask-RCNN result .Put this file in `./Mask_RCNN/`

**Mask_RCNN_demo_car_detection.ipynb**: Put this file in `./Mask_RCNN/`

## Requiremnets

* Keras 1 or keras 2
* Tensorflow (1.3 for Mask-RCNN)
* Python 3
