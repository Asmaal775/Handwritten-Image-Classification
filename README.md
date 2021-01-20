# Handwritten-Image-Classification
This project part of Efad2 hackathon in Riyadh.
# cluster similar words representing in images by using K-means algorithm.
 computer vision for Text recognition and clustering words of images that contains Arabic language. This project part of Efad2 hackathon in Riyadh.
 
# EasyOCR
EasyOCR is a python module for extracting text from image. It is a general OCR that can read both natural scene text and dense text in document. they are currently supporting 70+ languages , Arabic language is one of them.
#k-means clustering
k-means clustering is a method of vector quantization, originally from signal processing, that aims to partition n observations into k clusters in which each observation belongs to the cluster with the nearest mean (cluster centers or cluster centroid), serving as a prototype of the cluster.

## Installation

Install using pip,

```bash
pip install easyocr
we tried Arabic-ocr , tesseract  but we did not found a library that read arabic handwritten as we want so we depend on easyocr.
```

## Usage

```python
import numpy as np
import matplotlib.pyplot as plt
from PIL import Image
import cv2
import easyocr
import os
from  os import listdir
import random
from PIL import Image , ImageOps
from random import shuffle
from tqdm import tqdm
import glob
from collections import Counter 
from sklearn.cluster import KMeans
```
1. Define the path of folders contains images.
2. change the path of folder that savingthe clustering.
3. Run the code easier by colab or JupyterLab.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

