# Distraction-Detection
A YOLO_V5 implementation of a distraction detection system using a manually generated dataset.
## Inspiration
The inspiration of this project was the news that I heard of many manufacturers including drowsiness detection systems in their cars. However, there have been many cases when drowsiness alone is not the cause of the accident. In fact with so many notifications on our cellphones or the usage of sunglasses while driving as popularized by Movies and the classic case of drinking and driving are all major causes of accidents.
Hence I decided to build this software.
The only issue involved was the **need to create my own dataset with YOLO labels as such an idea wasn't implemented before**.

## What it does
Simply put it is a software that is able to detect the following things:
* Whether a driver is drowsy or awake
* Whether a driver is wearing headphones
* Whether a driver is wearing sunglasses
* Whether a driver is using a cellphone
## How I built it
I used the following libraries/packages/tools to build my software
* Google Colab (training)
* PyTorch
* YOLOV5 (ultralytics)
* Labelimg (to label the images)
## Challenges we ran into
The major challenge that I ran into was to create a dataset that was labeled as per YOLO requirements.
As there were no datasets available online i decided to create my own that would work and can later be expanded to work with other people.
Another challenge was to train the dataset , even though google colab sped up my work I had to use the first run directly as the time taken to train was exceeding the time allotted.
The final challenge that i ran into was to ensure the model could make live detection using camera feed. However I wasn't able to achieve the same due to lack of required hardware.

## Accomplishments that I'm proud of
The fact that such an idea could be implemented easily using such simple yet powerful techniques which works quickly makes me proud about created a piece of software that can have usage in the real world and endless potential.
Not only can it be used for drivers but it can also be used as a study monitoring tool or a meditation assistance tool as it helps to build focus by alerting us of potential distractions such as cellphones/headphones.

## What I learned
My learning's are as follows:
1. I learnt how to create datasets and label the images.
2. I learnt how to generate a model that is capable of being used.
3. I learnt about how to fine tune and adjust dataset parameters and how to create a good dataset.
4. Lastly i learnt about the endless possibilities that can be done using custom datasets.
## What's next for Distraction detection system
Of Course the first goal would be to create a model that is capable of working with all different types of people with different facial features. In order to do so one must collect high quality scenario based images with people of different races and/or create datasets unique to countries based on population metrics so that predictions can be made best.
Then this system can also find its applications in study monitoring systems/ focus enhancing/ meditation assistance tool as it alerts us of potential distractions such as cellphones/headphones or are we drowsy or awake etc.