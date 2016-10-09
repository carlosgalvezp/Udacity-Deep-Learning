Udacity Deep Learning
=====================
This repository contains the material and projects related to the 
Udacity Deep Learning course

Installation
------------
There are two main options:

### Using a Docker image

1. Install Docker:

		sudo apt-get install docker.io

2. Add the current user to the Docker group
		
		sudo usermod -aG docker $(whoami)

3. Log out and log in again

4. Download the Docker image by running:

		docker run -p 8888:8888 --name tensorflow-udacity -it b.gcr.io/tensorflow-udacity/assignments:0.5.0


5. Navigate through the assigments by browsing:

		http://127.0.0.1:8888

### Full local installation

1. Install TensorFlow [guide](http://textminingonline.com/dive-into-tensorflow-part-iii-gtx-1080-ubuntu16-04-cuda8-0-cudnn5-0-tensorflow)

2. Install required libraries:

		sudo apt-get install python-numpy python-scipy python-matplotlib python-sklearn python-six

2. Install iPython notebook:

		sudo apt-get install ipython ipython-notebook python-numpy python-scipy python-matplotlib

3. Navigate to the folder where you have the assignment you want to work on, 
and simply run:

		ipython notebook


