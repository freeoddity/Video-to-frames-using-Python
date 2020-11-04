All Credit goes to PyMoondra
YT : PyMoondra
GitHub: https://github.com/moondra2017

He created the code but i couldn't find it on github so i rewrote it and wanted to share it :)


THIS REQUIRES OPENCV
You can install it using: 
pip install opencv-python 

To check if it was properly installed open python and enter 
import cv2
It should send you to the next line.
You can check the version of opencv by using:
print(cv2.__version__)

I am currently using python 3.7.5 and opencv 4.4.0 

This is a simple template to capture every "x" frame of a video using python 



extracting frames args:
    video_path : path to video
    save_path : save directory for extracted images
    skip _frames : save every 'x' frames

For the simplest and no hassle frame extraction follow these steps (assuming you have opencv installed):
1.) Create a folder, name it whatever, place it wherever. I named mine Video_to_images, and placed it on my desktop
2.) place the script (video_to_image.py) in the the folder created on step 1
3.) Create another folder name it "output" (excluding the quotation marks) the script is already set up to spit the individual frames to this folder
4.) place your video in the same folder (aka the folder created on step 1) as the script.
5.) open the script. At the end (line 104-106) assign public_movies with the name of your video, including the .mp4, .mov, etc...
7.) Assign skip_frames a value 
6.) Then you're good to run

All the frames will be named randomly but it will be in chronological order

Notes:
I have not tested many other video format, I will soon though and update this.

GitHub: https://github.com/freeoddity
This repository: https://github.com/freeoddity/Video-to-frames-using-Python
 


 