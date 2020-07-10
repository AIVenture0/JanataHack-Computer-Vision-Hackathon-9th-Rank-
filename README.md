# [JanataHack-Computer-Vision-Hackathon (9th Private Leaderboard Rank)](https://datahack.analyticsvidhya.com/contest/janatahack-computer-vision-hackathon/#LeaderBoard)


___

<center><img src="https://datahack-prod.s3.ap-south-1.amazonaws.com/__sized__/contest_cover/cover_FJJYomD-thumbnail-1200x1200-90.jpg"/>

<center>15 Day Hackathon From Analytics Vidhya</center>

Emergency vs Non-Emergency Vehicle Classification

## About the Hackathon
__Fatalities__ due to traffic delays of emergency vehicles such as __ambulance & fire brigade__ is a huge problem. In daily life, we often see that emergency vehicles face difficulty in passing through traffic. So differentiating a vehicle into an emergency and non emergency category can be an important component in __traffic monitoring__ as well as self drive car systems as reaching on time to their destination is critical for these services.

______

## Task 

In this problem, you will be working on __classifying vehicle images__ as either belonging to the ```emergency vehicle or non-emergency vehicle category```. 

- For the same, you are provided with the __train__ and the __test dataset__. Emergency vehicles usually includes ```police cars, ambulance and fire brigades```.

## Sample Images

<center><img src="https://s3-ap-south-1.amazonaws.com/av-blog-media/wp-content/uploads/2018/08/Emgen.jpg"/></center>

<center><img src="https://github.com/saikrithik/JanataHack-Computer-Vision-Hackathon/raw/master/Data_Photos.png"/></center>


## Data Description
- ```train.zip```: contains 2 csvs and 1 folder containing image data
- ```train.csv``` – [‘image_names’, ‘emergency_or_not’] contains the image name and correct class for 1646 (70%) train images.

- ```images``` – contains __2352__ images for both train and test sets

- ```test.csv```: [‘image_names’] contains just the image names for the 706 (30%) test images

- ```sample_submission.csv```: [‘image_names’,’emergency_or_not­’] contains the exact format for a valid submission (1 - For Emergency Vehicle, 0 - For Non Emergency Vehicle)
 


## Evaluation Metric
- The evaluation metric for this competition is ```Accuracy```.

## Approach
- OpenCV for reading the images and stuff.
- Regular Transformation and data augmentation.
- Used Fastai Densenet201 model.

## Logsheet sample to track model progress

<img src="https://raw.githubusercontent.com/AIVenture0/JanataHack-Computer-Vision-Hackathon-21st-Rank-/master/logsheet.jpg"/>

## Competition Result
Rank:  9th on private LB
[Check LeaderBoard Ranking](https://datahack.analyticsvidhya.com/contest/janatahack-computer-vision-hackathon/#LeaderBoard)
