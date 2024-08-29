# Object Detection for SSA Imagery

The purpose of this repo is to be a fork of Ultralytics Yolo libary which has been modified to train models on single channel grayscale 16-bit .fits imagery. This type of image format is common with space surveillence images, and the standard YOLO libary does not accomodate for 16-bit or single channel images. 

The code contains two things, the modified library and a Jupyter notebook which shows how to run a one-click method to train a DL model on space data. 
