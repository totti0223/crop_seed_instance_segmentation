# Learning from Synthetic Images for Crop Seed Instance Segmentation

![image-20191204160204190](README.assets/image-20191204160204190.png)

**Overview of the proposed training process of crop seed instance segmentation.**



## Data included in this repository

- Codes in Jupyter Notebook format

  - [Mask RCNN Inference of crop seed images](./Mask_RCNN.ipynb)

  - [Multivariate Analysis and Visualization](multivariate_analysis.ipynb)

    

## Large Size Files are stored at Google Drive

https://drive.google.com/file/d/1g8bg9ter9DlKWgs0lfPZMQemRlzRVOQr/view?usp=sharing



### Contents

- Barley data
  - Synthetic Images and Masks of Test Data
  - Real World Images of Test Data (19 barley cultivar)
    - The annotation of Real World Images formated in JSON
  - Trained Model Weight
- Other crops
  - Model Weights and Image of Rice seeds
  - Model Weights and Images of 4 Wheat cultivars. One model can infer 4.



## Howto

1. Clone the repository

2. Install Dependencies (See below)

3. Download the data.zip from google drive and place it into the top directory (replace the empty "data" folder) of this repository

4. Run the notebook



## Dependencies

- [Mask RCNN](https://github.com/matterport/Mask_RCNN) implemented with Keras/Tensorflow provided by matterport.
- Keras==2.2.4
- Tensorflow-gpu==1.13.1
- pyefd==1.4.1 (for EFD analysis)
- other general packages such as sklearn, scikit-image, opencv3, etc..



## Author

Yosuke Toda

JST PRESTO / ITbM, Nagoya Univ.

