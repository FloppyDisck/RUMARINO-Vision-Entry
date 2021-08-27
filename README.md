# RUMARINO-Vision-Entry
A simple little entry test that looks for good work understandings.

## Setup
Before starting you must first install some dependencies for this project.
Install [OpenCV](https://www.pyimagesearch.com/2018/08/15/how-to-install-opencv-4-on-ubuntu/).
Note: Avoid installing the pip library opencv-python as it has problems with using video.

Install Alexey's [Darknet](https://github.com/AlexeyAB/darknet).
Note: Read setup instructions as they show different compilations parameters. (CPU flags are also present)

Download [Yolov3-tiny cfg and weights](https://pjreddie.com/darknet/yolo/).

Install Numpy [Using pip](https://packaging.python.org/tutorials/installing-packages/).

The model, along with its pretrained weights can be found in "model", the training data can be found in "images".

## How training works
Each image has a corresponding text file that keeps bounding box information that points the relative location of the object to be detected.
A test and train text file must be created that points to these images, these must be created by you. (You can split the test/train in a 50/50 manner)

Then you must modify the detector.data file found in the models folder to point to train and test text files.

Once this has been done then its time to get pretrained weights and train the provided model with these pretrained weights. HINT: scr folder has the run files.

## What to do?
Read over the files in the repo carefully,
You must create one script that takes care of updating model info and then runs and trains the model.

No prior experience with machine learning is nessesary, you will find that the important parts have already been done, they just need to be placed in the right order.

Send over your cloned repo to guy.garcia@upr.edu.
As long as the training process starts and creates a log this is enough for evaluation.

And as always, feel free to ask me anything or google for solutions, a good engineer is not afraid to ask questions ;)
