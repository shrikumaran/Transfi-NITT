# Deep learning based occupants counter
This repo contains code for the YOLO implementation to count number of humans in a room.
We implement a method to count the number of occupants in room, from the given video feed of the room. We use a YOLOv3 model as our backbone. The model detects humans in the room and we count the number of predictions in each frame to give out the final count.

<br>
<img src="result.jpeg">
<br>
Video.py is the code for running predictions
