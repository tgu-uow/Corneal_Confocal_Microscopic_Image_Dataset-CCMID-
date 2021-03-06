# Corneal Confocal Microscopic Image Dataset (CCMID)

## About CCMID
[TGU-UOW Lab](http://www.tgu-uow.com/)

## CCMID Introduction
The CCMID dataset provides three different types of image data：

* **raw_data**: An unprocessed image set. The image size is 384 × 384, the image format is .Jpg.
* **preprocessed_data**: Image set with image vignetting processing. Prevent affecting subsequent image stitching operations.
* **stitched_data**：Manually stitching images. The image format is .tif, and '- tracking' is the corneal nerve tracking extracted image of the stitched image.

**Folder Structure:**

example：

    |-- raw_data
        |-- OD
        |-- OS
    |-- preprocessed_data
		|-- OD
        |-- OS
    |-- stitched_data



### raw_data<br>
![raw_data](example/raw_data/OD/zxOD174.jpg)
### preprocessed_data<br>
![preprocessed_data](example/preprocessed_data/OD/zxOD174.jpg)
### stitched_data<br>
![stitched_data](example/stitched_data/zxOS.jpg)
### stitched-tracking_data<br>
![stitched_data](example/stitched_data/zxOS-tracking.jpg)

## TODO List
1. Fix the abnormal neural grayscale value in some images in preprocessed_data.

2. Add corneal nerve annotation images (annotated by a physician) for image segmentation tasks.

3. Upload more image data

## Citing CCMID
If you use CCMID in a scientific publication, we would appreciate references to the following paper:

Biblatex entry:

``
Coming soon
``

## Contact Us
To discuss the dataset, Please contact email

liguangxu@tiangong.edu.cn

litianyu@tiangong.edu.cn

## Copyright
Do not use for commercial purposes without permission. <br>
Copyright (c) 2021 TGU-UOW

---
# 角膜共聚焦显微图像数据集（CCMID）

## 关于CCMID数据集

## CCMID数据集介绍
CCMID数据集提供3种不同的图像数据

* raw_data: 未经任何处理的图像，图像尺寸为384×384，图像格式为.jpg。
* preprocessed_data: 对原图像进行了渐晕处理，防止影响后续图像拼接操作。
* stitched_data：手动拼接图像，图像格式为.tif，-tracking为拼接图像的角膜神经追踪提取图像。

## 待办事项清单
1. 修正preprocessed_data中某些图片中神经灰度值异常问题。

2. 添加角膜神经标注图（由医生标注），用于图像分割任务。

3. 上传更多图像数据
## 引用 CCMID
如果您在论文中使用CCMID数据集，我们将感谢您参考以下论文：

Biblatex entry:

``
Coming soon
``

## 联系我们
讨论数据集的相关问题或其他问题，请通过电子邮件联系：

**liguangxu@tiangong.edu.cn**

**litianyu@tiangong.edu.cn**

## 版权所有
未经允许，禁止用于商业用途 <br>
Copyright (c) 2021 TGU-UOW