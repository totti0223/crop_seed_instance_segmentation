# Learning from Synthetic Images for Crop Seed Instance Segmentation

![image-20191204160204190](README.assets/image-20191204160204190.png)

A Mask RCNN network trained with synthetic images to segment crop seed shape.





## Data included in this repository

- Images
  - Synthetic Images and Masks of Test Data -> [here](./data/synthetic_test)
  - Real World Images of Test Data -> [here](./data/realworld_test/image)
    - The annotation of Real World Images is in JSON file -> [here](data/realworld_test/metadata.json)
- Codes in Jupyter Notebooks
  - [Mask RCNN Inference](./Mask_RCNN.ipynb)
  - [Array of Multivariate Analysis](multivariate_analysis.ipynb)



## Dependencies

- [Mask RCNN](https://github.com/matterport/Mask_RCNN) implemented with Keras/Tensorflow provided by matterport.
- Keras==2.2.4
- Tensorflow-gpu==1.13.1
- pyefd==1.4.1 (for EFD analysis)
- other general packages such as sklearn, scikit-image, opencv3, etc..



Yosuke Toda

JST PRESTO

ITbM, Nagoya Univ.

