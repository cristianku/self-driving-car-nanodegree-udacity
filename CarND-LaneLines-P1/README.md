**Udacity Self Driving Car Nanodegree Program. September 2017 .**

 

**Finding Lane Lines on the Road**
==================================

<http://www.udacity.com/drive>

Overview
--------

This project is part of the Udacity Self Driving Car Nanodegree Program.

This is the first project, and the deadline for this project is

**Thursday, September 14, 2017 at 11:59 PM PST**..

 

The aim is to **detect the road lane lines** using **Python** and **OpenCV**.

 

OpenCV means "Open-Source Computer Vision", which is a package that has many
useful tools for analyzing images.

 

Please check the **writeup.md**, where the steps toward the final result are
explained in details.

 

List of the files
-----------------

**P1.ipynb** contains the Program code to run ( how to run see below )

**writeup.md** contains the explanation how the solutions to the problem has
been resolved.

 

List of the folders
-------------------

**Test_images** contains the input images for the processing of lane detection

**Test_images_output** is the folder containing the processed images using
**P1.ipynb**

 

**Test_videos** contains the input videos for the processing of lane detection

**Test_videos_output** contains the processed videos using **P1.ipynb**

 

**Writeup_images** contains the images for the writeup.md document

 

**How to run the code**
-----------------------

 

**Step 1:** Set up the [CarND Term1 Starter
Kit](https://classroom.udacity.com/nanodegrees/nd013/parts/fbf77062-5703-404e-b60c-95b78b2f3f9e/modules/83ec35ee-1e02-48a5-bdb7-d244bd47c2dc/lessons/8c82408b-a217-4d09-b81d-1bda4c6380ef/concepts/4f1870e0-3849-43e4-b670-12e6f2d4b7a7)
if you haven't already.

**Step 2:** Open a command line in the **Project folder** ( CarND-LaneLines-P1 )

**Step 3:** Open Jupyter Notebook

`> jupyter notebook`**P1.ipynb**

A browser window will appear showing the contents of the current directory.

**Step 3:** Run the code using SHIFT+ ENTER

 

If you don’t have Python / Jupyter Notebook installed, you can download Anaconda
Package:<https://www.anaconda.com/download/>

 

**Project requirements check​**
------------------------------

 

| Have all project files been included with the submission?                                                                                                                                                                                                  | **yes**, The project submission includes all required files                                                                                                       |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Does the pipeline for line identification take road images from a video as input and return an annotated video stream as output?                                                                                                                           | **Yes, **The output video is an annotated version of the input video.                                                                                             |
| Has a pipeline been implemented that uses the helper functions and / or other code to roughly identify the left and right lane lines with either line segments or solid lines? (example solution included in the repository output: raw-lines-example.mp4) | **Yes, **In a rough sense, the left and right lane lines are accurately annotated throughout almost all of the video. Annotations can be segmented or solid lines |
| Have detected line segments been filtered / averaged / extrapolated to map out the full extent of the left and right lane boundaries? (example solution included in the repository: P1_example.mp4)                                                        | **Yes, **Visually, the left and right lane lines are accurately annotated by solid lines throughout most of the video.                                            |
