# Content-Based Image Retrieval using Multi Feature
Content Based Image Retrieval (CBIR) is a technique which retrieves the images within a dataset using their visual content rather than text description. The requirement for reliable image retrieval in practical application has increased due to abundance of the availability of numerous images in different domains.

The project is a classical CBIR system which will retrieve similar images based on colour, texture and shape features in combination with feature fusion methods.

## Dataset Domains

The project is tested on images from multiple domains collected from Kaggle sources:

Natural Images
Brain MRI Images
Paintings Images

Each domain contains images with different visual characteristics which requires domain specific preprocessing.

## Project Workflow

The CBIR system uses a multi stage processing pipeline comprising of:
- Image preprocessing based on image domains
- Colour, texture and shape descriptors feature extraction
- Feature fusion to combine multiple features
- Similarity computation to compare dataset and query images
- Ranking and retrieval of most similar images

## Setup
Install required libraries
- pip install requirements.txt

Run the notebooks within the notebooks folder to execute preprocessing and retrieval pipelines.

The query image should be given in data/query folder to test retrieval.

This project demonstrates that a Content Based Image Retrieval system based on classical image processing techniques can be developed to retrieve visually similar images from different domains.