
# CS570_Project_HAR
This project is designed to classify between Human Activities using VGG16 model.

Due to limited size of RAM, we are only using two classes. It might affect performance, but it is enough in this context. 
We are using these two activities:

 1. CricketBowling 
 2. BodyWeightSquad

We are doing video classification on these two activities. 


## Images
Cricket Bowling
![CricketBowling](https://upload.wikimedia.org/wikipedia/commons/6/69/Muralitharan_bowling_to_Adam_Gilchrist.jpg)

BodyWeightsquad
![BodyWeightsquad](https://www.fitstream.com/images/bodyweight-training/bodyweight-exercises/bodyweight-squat.jpeg)

## Video Classification
To classify between those two videos (activities) is very similar to image classification. A video is just a sequence of frames. To perform this task we did:

 1. Stored the video names and their labels
 2. Run a loop on each video and save the frames in a folder.
 3. When all the frames are stored then we have sequence of images on which we extract features and train our model on these frames.
 
