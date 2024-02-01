
mold - v4 2023-12-27 9:16pm
==============================

This dataset was exported via roboflow.com on December 28, 2023 at 8:20 AM GMT

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

The dataset includes 847 images.
Injera-mold are annotated in YOLOv8 format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 640x640 (Stretch)

The following augmentation was applied to create 3 versions of each source image:
* Random brigthness adjustment of between -36 and +36 percent
* Random exposure adjustment of between -33 and +33 percent
* Random Gaussian blur of between 0 and 1.25 pixels
* Salt and pepper noise was applied to 3 percent of pixels


