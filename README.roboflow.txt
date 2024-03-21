
Weed Detection - v7 2024-03-04 12:13pm
==============================

This dataset was exported via roboflow.com on March 4, 2024 at 7:14 AM GMT

Roboflow is an end-to-end computer vision platform that helps you
* collaborate with your team on computer vision projects
* collect & organize images
* understand and search unstructured image data
* annotate, and create datasets
* export, train, and deploy computer vision models
* use active learning to improve your dataset over time

For state of the art Computer Vision training notebooks you can use with this dataset,
visit https://github.com/roboflow/notebooks

To find over 100k other datasets and pre-trained models, visit https://universe.roboflow.com

The dataset includes 11160 images.
CarpetWeeds-CrabGrass-Eclipta are annotated in YOLOv8 format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)

The following augmentation was applied to create 3 versions of each source image:
* 50% probability of horizontal flip
* 50% probability of vertical flip
* Random rotation of between -45 and +45 degrees
* Random shear of between -35° to +35° horizontally and -27° to +27° vertically
* Random exposure adjustment of between -21 and +21 percent
* Random Gaussian blur of between 0 and 4 pixels
* Salt and pepper noise was applied to 5.56 percent of pixels

The following transformations were applied to the bounding boxes of each image:
* Random brigthness adjustment of between -40 and +40 percent


