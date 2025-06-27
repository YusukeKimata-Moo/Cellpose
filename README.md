# Cell Image Analysis Project based on Cellpose

## Overview

This project is a collection of Jupyter Notebooks for segmenting and restoring microscopy images using [Cellpose](https://github.com/MouseLand/cellpose) and related models.

It is designed to run on Google Colaboratory, enabling high-speed processing using GPUs.

## Features

### 1. Image Restoration with Cellpose3

- **`Cellpose3_restoration.ipynb`**
- Utilizes the image restoration features integrated into Cellpose3.
- Improves the quality of microscopy images by performing the following processes:
    - **Denoising**
    - **Deblurring**
    - **Upsampling**
    - **Oneclick**

### 2. Segmentation with Cellpose3

- **`Cellpose3_segmentation.ipynb`**
- Performs cell segmentation using the Cellpose3 model.

### 3. Segmentation with Cellpose-SAM

- **`Cellpose-SAM.ipynb`**
- Higher precision cell segmentation by Cellpose-SAM.

## Directory Structure

```
.
├── Cellpose-SAM.ipynb
├── Cellpose3_restoration.ipynb
├── Cellpose3_segmentation.ipynb
├── input/                # Directory for input images
│   ├── image.tif
│
├── output/               # Directory for output results
│   ├── image_label.tif
│   ├── image_denoised.tif
│   ├── image_deblured.tif
│   ├── image_upsampled.tif
│   └── image_restored.tif
└── README.md
```

## How to Use

1.  Download this project or place it in your Google Drive.
2.  Open any of the Notebook (`.ipynb`) files in Google Colab.
3.  Upload the images you want to analyze (e.g., `.tif`) to the `input` directory.
4.  Open the Notebook and modify the file paths in the code as needed.
5.  Run the cells in the Notebook sequentially from the top.
6.  Once the processing is complete, the results will be saved in the `output` directory.
