# Semantic-segmentation-to-detect-lanes-carla-dataset

The dataset is from the lyft udacity challange in Kaggle.
This dataset provides data images and labeled semantic segmentations captured via CARLA self-driving car simulator. The data was generated as part of the Lyft Udacity Challenge . This dataset can be used to train ML algorithms to identify semantic segmentation of cars, roads etc in an image.

The data has 5 sets of 1000 images and corresponding labels.

#Content
The data set contains sets of RGB and the corresponding semantic segments.
See link below for details
http://carla.readthedocs.io/en/latest/camerasandsensors/#camera-semantic-segmentation

#Acknowledgements
CARLA Self Driving Cars Simulator

Some of the data come from
https://github.com/ongchinkiat/LyftPerceptionChallenge/releases/download/v0.1/carla-capture-20180513A.zip

Encoder Decoder network(segnet) is implemented with the help of tensorflow keras for semantic segemntation.
