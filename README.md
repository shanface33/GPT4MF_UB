# Can ChatGPT Detect DeepFakes? A Study of Using Multimodal Large Language Models for Media Forensics

[![Github](https://img.shields.io/badge/Github%20webpage-222222.svg?style=for-the-badge&logo=github)]()
[![arXiv](https://img.shields.io/badge/-arXiv-B31B1B.svg?style=for-the-badge)]()

This is the official repository of the paper:
[Can ChatGPT Detect DeepFakes? A Study of Using Multimodal Large Language Models for Media Forensics]() 

Shan Jia, Reilin Lyu, Kangran Zhao, Yize Chen, Zhiyuan Yan, Yan Ju, Chuanbo Hu, Xin Li, Baoyuan Wu, Siwei Lyu


## Test-data
The synthetic images used as test can be downloaded from the following [link](https://drive.google.com/file/d/1grvgKiIq0ny8ImQzSUXPk3nd-AMEDjNb/view?usp=share_link) alongside a csv file stating the processing applied in the paper on each image. The real images can be downloaded from the following freely available datasets : [IMAGENET](https://image-net.org/index.php), [UCID](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/5307/0000/UCID-an-uncompressed-color-image-database/10.1117/12.525375.short),[COCO - Common Objects in Context](https://cocodataset.org/#home).
The real images should then be placed in a folder with the same name that has been recorded in the csv file
The directory containing the test set should have the following structure:
```
Testset directory
|--biggan_256
|--biggan_512
.
.
.
|--real_coco_valid
|--real_imagenet_valid
|--real_ucid
.
.
.
|--taming-transformers_segm2image_valid
```
