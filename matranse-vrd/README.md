## Basic dependencies

Python version: 3.5

* numpy==1.14.5
* torch==1.0.0
* torchvision==0.2.1


## To run this project

* Clone project and cd project folder
* Run script download_data.sh. This will download the VRD dataset (images and annotations) and merge the folders as necessary.
* Set the environment variables in config.yaml and run prepare_data.py. This will create all necessary files to perform training and/or testing of a model.
* Run main.py to train and test a Multimodal Attentional Embeddings model. The function will first check if a model exists and will train a new one if not. Then, testing on VRD test split is performed.


