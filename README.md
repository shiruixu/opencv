Instructions:

Download "detect_faces_video.py"

When using OpenCV’s deep neural network module with Caffe models, you’ll need two sets of files:

	The .prototxt file(s) which define the model architecture (i.e., the layers themselves)
	The .caffemodel file which contains the weights for the actual layers

You need to install openCV first:

	pip3 install opencv-python

If you don’t have imutils  in your virtual environment, you can install it via:

	pip install imutils

Command line: 

	python detect_faces_video.py --prototxt deploy.prototxt.txt \
	--model res10_300x300_ssd_iter_140000.caffemodel

Exit realtime vedio:

	press 'q'
