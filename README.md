# VISION-EXTRACTION
#Vision Extraction

This project focuses on object segmentation and visualization using the COCO dataset and OpenCV.
It demonstrates how to extract and overlay single or multiple object masks on original images with adjustable transparency.
#Overview
The notebook Vision_Extraction.ipynb includes the following:
Downloading and extracting image datasets and annotations.
Loading and processing COCO-style segmentation data.
Extracting object masks from annotations using pycocotools.
Combining single or multiple masks and overlaying them on the original image.
Visualizing results using OpenCV and Matplotlib.

#Requirements

Install all required libraries before running the notebook:

pip install numpy matplotlib opencv-python pycocotools

Vision_Extraction/
│
├── Vision_Extraction.ipynb   # Main notebook
├── data/                     # (Optional) Folder for images and annotations
└── README.md                 # Project documentation
