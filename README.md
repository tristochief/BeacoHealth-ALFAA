# BeacoHealth-ALFAA
The Automated Lab For Artificial intelligence Annotations is an apparatus for automatically capturing, and annotating valuable data for image recognition and object detection

# Motivation
Annotating hundreds and thousands of images for object recognition is a laborious, technical task that takes human beings too much time, and is too repetitive for a human to not make errors. Automating this process would increase productivity by 10 fold for companies that require it. 

Specifically for teams that are doing object recognition tasks involving moving objects inside a small space, or physically interacting with a small space through collisions of some sort, we are providing an automated laboratory setup for those teams that require such tasks.

# Principles for the Project
1. Code is elegant, neat and maintainable
2. The apparatus is cheap
3. Easy to setup
4. Precise with its annotation abilities
5. Provides as much labelling data as possible
6. Is as self maintained as possible
7. Has the lowest amount of intrusion as possible to the environment it will be operating on
7. Is fully autonomous once set up

# General Idea
We will use physical sensors, carefully positioned in a way so that it can coordinate precise annotating of images. A camera will be setup in some specific location. Pressure matts will be placed on the floor, and sensors will be placed in devices that will be interacted with. A camera's view will be dissected into segments, each segment represents a region where a sensor is positioned. A raspberry pi will retrieve all of the signals from the sensors with the date. The camera will constantly record. When A sensor is pressed, this will be saved in a database on the raspberry pi, with all the necessary metadata. At the end of the lab work, the dates of the sensors, along with their corresponding segments of the image will be used to automatically annotate each image. This will be done at the end by a computer inside the lab or alternatively it will be done live by the raspberry pi depending on the size of the imgs. 
