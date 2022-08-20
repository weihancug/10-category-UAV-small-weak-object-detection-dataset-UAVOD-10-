# 10-category-UAV-small-weak-object-detection-dataset-UAVOD-10-
This repository is about downloading and using the UAVOD-10 dataset, which is now available on [Baidu Netdisk](https://pan.baidu.com/s/1GlEiHENSAcG2V8bthTUn6A) or [Google Driver](https://pan.baidu.com/s/1GlEiHENSAcG2V8bthTUn6A) after the relevant paper is published.


The UAVOD-10 consists of 844 images and 18,234 instances. These instances are labeled with horizontal bounding boxs (HBB) with VOC format. The images’ widths range from 1,000 to 4,800 pixels, and their resolutions are about 0.15 meters. Some examples of the 10-class objects are displayed in the figure. The 10 categories of objects are building, ship, vehicle, prefabricated house, well, cable tower, pool, landslide, cultivation mesh cage, and quarry.
existing works.
![UAVOD-10 example](./data_example.png)


If this UAVOD-10 data is used in the research works, please the related papers:

```
@article{HAN2022102966,
title = {A context-scale-aware detector and a new benchmark for remote sensing small weak object detection in unmanned aerial vehicle images},
journal = {Int. J. Appl. Earth Obs. Geoinformation},
volume = {112},
pages = {102966},
year = {2022},
issn = {1569-8432},
doi = {https://doi.org/10.1016/j.jag.2022.102966},
author = {Wei Han and Jun Li and Sheng Wang and Yi Wang and Jining Yan and Runyu Fan and Xiaohan Zhang and Lizhe Wang},
}

@article{small-weak-object-detection-survey,
	author    = {Wei Han and Jia chen and Lizhe Wang and Ruyi Feng and Fengpeng Li and Lin Wu and Tian Tian and Jining Yan},
	title     = {A survey on methods of small weak object detection in optical high-resolution remote sensing images},
	journal   = {{IEEE} Geosci. Remote. Sens. Mag.},
	pages     = {8--34},
	year      = {2021},
	volume = {9},
	issue = {4}
}

@article{hard_example_mining,
	author    = {Wei Han and Runyu Fan and Lizhe Wang and Ruyi Feng and Fengpeng Li and Ze Deng and Xiaodao Chen},
	title     = {Improving Training Instance Quality in Aerial Image Object Detection with A Sampling-balance based Multi-stage Network},
	journal   = {{IEEE} Trans. Geosci. Remote. Sens.},
	pages     = {1--15},
	year      = {2020}
}
```
