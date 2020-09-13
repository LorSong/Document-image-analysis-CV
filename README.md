# Document-image-analysis-CV
Working with textual images using computer vision for solving document-related tasks

Recommended - open this repository in colab

https://colab.research.google.com/github/LorSong/Document-image-analysis-CV/blob/master/

Work description
Global goal of this work is to create efficient pipelines for processing textual images. These pipelines will perform:

*   Image preprocessing
*   Text detection
*   Text recognition
*   Stamp recognition
*   And potentially more tasks

First part:
Exploratory work on textual image recognition

  * 1_Load_Process_Experiments: 
    In this notebook I'm preparing data for tf.data API and trying simple approaches to preprocessing images.

  * 2_Slicing_images_Experiments:
    Here I'm experimenting with slicing and recovering a big image to reduce memory load. And visualisation of labels (locations of text) for the upcoming text detection task.
  
  * Upcoming. Implementing YoloV3 architecture on DDI-100 dataset for text detection. 
    

Datasets used in this work
* DDI-100 dataset


