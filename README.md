# Deep learning based occupants counter
We implement a method to count the number of occupants in room, from the given video feed of the room. We use a YOLOv3 model as our backbone. The model detects humans in the room and we count the number of predictions in each frame to give out the final count.

# Running locally
* Download YOLOv3 weights and it's config files from the below link.
https://pjreddie.com/darknet/yolo/
*
<br>
<img src="result.jpeg">
<br>
Video.py is the code for running predictions
