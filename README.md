# Learning from Synthetic Images for Crop Seed Instance Segmentation

![image-20191204160204190](README.assets/image-20191204160204190.png)

**Overview of the proposed training process of crop seed instance segmentation.**



## Data included in this repository

- Images
  - Barley
    - Synthetic Images and Masks of Test Data
    - Real World Images of Test Data
      - The annotation of Real World Images formated in JSON
- Codes in Jupyter Notebooks
  - [Mask RCNN Inference of crop seed images](./Mask_RCNN.ipynb)
  - [Multivariate Analysis and Visualization](multivariate_analysis.ipynb)



## Dependencies

- [Mask RCNN](https://github.com/matterport/Mask_RCNN) implemented with Keras/Tensorflow provided by matterport.
- Keras==2.2.4
- Tensorflow-gpu==1.13.1
- pyefd==1.4.1 (for EFD analysis)
- other general packages such as sklearn, scikit-image, opencv3, etc..



Yosuke Toda

JST PRESTO

ITbM, Nagoya Univ.

