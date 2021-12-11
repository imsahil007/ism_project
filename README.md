# Building and Analysis of Facial data from YouTube
A tool for creating an analysis of video fetched from YouTube to distinguish video containing human-speech data.
The tool will fetch multiple YouTube videos asynchronously and detect objects using Real-Time Object Detection YOLO(You Only Look Once). Using deep learning techniques, the accuracy for object detection has increased drastically. This led us to detect a person and even other objects in our visual feed input in real-time with very high accuracy.

The apparatus will bring numerous YouTube recordings non-concurrently and distinguish objects utilizing Real-Time Object Detection YOLO(You Only Look Once). Utilizing profound learning strategies, the exactness for object recognition has expanded definitely. This drove us to recognize an individual and surprisingly different articles in our visual feed input continuously with extremely high precision. 



## Dependencies
*  OpenCV
*  Python
* YOLO(Including weight files)
* pytube( Downloading videos from YouTube)


## Steps:
1. Download video through a link
2. Load yolo weight files and initialize a list from `coco.names` which contains a list of all classes yolo can distinguish.
3. Detect objects and normalize each pixel with a scaling factor of 0.00392 which can be changed as per your video input quality. We also convert the image from BGR to RGB here.
4. Draw labels and bounding boxes in case you want to distinguish the person in the video. This feature can be omitted in case you just want to save the videos in a different path.
5. Generate the output.



## Team Members

1. Sahil (19MCMC46)
2. Yogesh Kumar Gupta (19MCMC45)
3. Amandeep Singh (19MCMC14)
4. Yash Gupta (19MCMC47)
5. Shivam Bishen (19MCMC70)