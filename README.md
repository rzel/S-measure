# [S-measure: A new way to evaluate foreground maps](http://dpfan.net/smeasure/)

![alt tag](http://dpfan.net/wp-content/uploads/2017/07/S-measure.png)

## Abstract

Foreground map evaluation is crucial for gauging the progress of object segmentation algorithms, in particular in the field of salient object detection where the purpose is to accurately detect and segment the most salient object in a scene. Several widely-used measures such as Area Under the Curve (AUC), Average Precision (AP) and the recently proposed Fbw have been used to evaluate the similarity between a non-binary saliency map (SM) and a ground-truth (GT) map. These measures are based on pixel-wise errors and often ignore the structural similarities. Behavioral vision studies, however, have shown that the human visual system is highly sensitive to structures in scenes. Here, we propose a novel, efficient, and easy to calculate measure known as structural similarity measure (Structure-measure) to evaluate non-binary foreground maps. Our new measure simultaneously evaluates region-aware and object-aware structural similarity between a SM and a GT map. We demonstrate superiority of our measure over existing ones using 5 meta-measures on 5 benchmark datasets.

## Usage

Requirement:
  
    You should install Matlab first.
    
Matlab Example:
    
    You can just run the demo.m to see the usage of the code.

## Citations

If you are using the code provided here in a publication, please consider citing our paper:

    @inproceedings{FanStructMeasureICCV17,
      title={Structure-measure: A New Way to Evaluate Foreground Maps},
      author={Deng-Ping Fan and Ming-Ming Cheng and Yun Liu and Tao Li and Ali Borji},
      booktitle={IEEE International Conference on Computer Vision},
      year={2017}
    }
