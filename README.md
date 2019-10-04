# classify_farm_crop_from_satellite_images

This work was done during this competition where data scientists were asked to build a model that can classify crop types based on sentinel-2 satellite images.

To first understand the data you can take a look at [this notebook](https://github.com/firou1925/classify_farm_crop_from_satellite_images/blob/master/notebooks/farm-crop-detection-explore-data.ipynb)

Teckniques tried in this challenge.

* gradient boosting algorithms: - Lightgbm
                                - XGBoost
                                - Catboost
Extracted statistics from the images of each farm of the different bands and other feature engineered layers taken from this [research paper](https://docs.google.com/document/d/1GOn8MPL2s-TovjiX2rcXmVUqRqRg2Vo7-8scIisrrKE/edit?usp=sharing)
                           
                               
* Convolutional neural networks: (CNN): since the data is composed of images

* Recurrent neural networks (RNN): since the data given is for 11 dates so building a model based on the temporal transformation is legitimate.

* Multilayer neural network : NN: 

* CNNLSTM architechtures: based on this [research paper](https://arxiv.org/pdf/1901.10503.pdf)
