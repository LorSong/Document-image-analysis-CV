# Document-image-analysis-CV
Working with textual images using computer vision for solving document-related tasks

Recommended - open this repository in colab

https://colab.research.google.com/github/LorSong/Document-image-analysis-CV/blob/master/

Work description <br/>
Global goal of this work is to create efficient pipelines for processing textual images. These pipelines will perform:

*   Image preprocessing
*   Text detection
*   Text recognition
*   Stamp recognition
*   And potentially more tasks

First part:
Text detection.<br/>

  * 1_Load_Process_Experiments: <br/>
    In this notebook I'm preparing data for tf.data API and trying simple approaches to preprocessing images.

  * 2_Slicing_images_Experiments: <br/>
    Here I'm experimenting with slicing and recovering a big image to reduce memory load. And visualisation of labels (locations of text) for the upcoming text detection task.
  
  * 3_Yolov3_Text_detection: <br/>
    Using YoloV3 architecture on DDI-100 dataset for text detection. Preparing data, preprocessing and postprocessing it.
    Preprocessing includes previous slicing experiments - cutting 2700x2000 image into 416x416 overlapping pieces along with boxes labels.
    Results were pretty good. Though postprocessing step requires a bit fine tuning.
    

Datasets used in this work
* DDI-100 dataset


