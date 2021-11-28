# IIITD Social Distancing Monitor (Computer Vision)

## About
Code for my internship at IIIT Delhi (June 2020 - July 2020) under the supervision of Professor [Koteswar Rao](https://sites.google.com/site/koteswarraojerripothula).  
The aim of the project was to monitor social distancing through CCTV cameras in 3-dimensional setting. The files available in the repository are codes for my part of the project.

## Execution
1. Apply alpha pose to a video using `Alpha_Pose_Works` file.
      1. Download duc_se.pth from [here](https://drive.google.com/file/d/1RoOB5ukKNavINgUuAtIIHReK_HAUU4ir/view?usp=sharing)
      2. Download yolov3-spp.weights from [here](https://drive.google.com/file/d/13DhywizS2UoC7JKPFS81u5ig4RMEfyfx/view?usp=sharing)
2. Convert video to frames and store at infile using segment of `Depth and Converted to csv` file.
3. Use the points to mark red dots on the frames using a segment of `Print Pixel Intensity and mark` file.
4. Apply depth estimation model on these frames using segment of `Depth and Converted to csv` file.
      1. Use the `Extract info average` file at this point to mark centroid of specific keypoints.
5. Convert the frames in outfile back to a video.


## Author
[Vansh Gupta](https://github.com/V-G-spec)  
Undergraduate student, Electrical Engineering Department  
Indian Institute of Technology, Delhi
