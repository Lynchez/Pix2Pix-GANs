# Pix2Pix-GANs

[//]: # (Image Reference)

[img]: ./assets/1.png "SLAM"

![SLAM][img]

## Project Overview

In this project, Using Mask R-CNN to image segmentation

## Project Instruction

### Instruction

1. Clone the repository and navigate to the downloaded folder.
	```
		git clone https://github.com/Lynchez/Satellite-Image-Segmentation
		cd Satellite-Image-Segmentation-master
	```
2. Train your model
	```
		python satellite.py train --dataset=/path/to/dataset --weights=coco
	```
2. Test your model
	```
		python satellite.py splash --weights=/path/to/weights/file.h5 --image=URL or path to file
	```
