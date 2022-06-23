# Video-Captioning

Video Captioning is an encoder decoder mode based on sequence to sequence learning.
It takes a video as input and generates a caption describing the event in the video. 

The importance of captioning lies in its ability to make video more accessible in numerous ways. 
Automated video caption generator helps searching of videos in websites better. 
It can be used for clustering of videos based on their content easier.
This is a brief overview of my project.

## Inspiration
I was looking around for some new projects when I came across video captioning and I realised the lack of good resources. 
I hope this project makes it easier for people to implement video captioning.

## SampleResults
Here is a clip of realtime prediction on the testing data.

## Dataset
This project is build on the dataset which 1450 training videos and 100 testing videos.

## Setup
Clone the repository : git clone https://github.com/DARK-art108/Video-Captioning-Using-LSTM.git

Video Caption Generator: cd Video-Captioning-Using-LSTM

Create environment: conda create -n video_caption python=3.7

Activate environment: conda activate video_caption

Install requirements: pip install -r requirements.txt

## Usage
To use the models that have already been trained

Add a video to **data/testing_data/video** folder and run the predict realtime file as <code>python predict_realtime.py</code>

For faster results extract the features of the video and save it in feat folder of the testing_data.

To convert into features run the extract_features.py file as <code>python extract_features.py</code>

Run train.py for local training or use the Video_Captioning.ipynb notebook 

## References
 
 [SV2T paper 2015](https://arxiv.org/abs/1505.00487)
 
 [Keras implementation](https://github.com/CryoliteZ/Video2Text)
 
[Intelligent-Projects-Using-Python](https://github.com/PacktPublishing/Intelligent-Projects-Using-Python/blob/master/Chapter05) 

