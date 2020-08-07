# Object-Detection-Avoidance-Robot
This robot is capable of detecting any objects in front of it, and can find the best possible path to travel after the detection is done.
When the robot detects an object in front of it, it does the following:
- It stops moving atleast 10-15 cm before the detected object
- It moves back a bit.
- It turns left and right, in order to scan for the nearest object that it can detect
- It then turns to the side which it detected as having an object the farthest away.
- Continues travelling along that direction until it detects another object, in which case, the entire process starts again.
