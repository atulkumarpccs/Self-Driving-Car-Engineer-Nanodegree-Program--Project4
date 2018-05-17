# Project 4 : Advanced Lane Finding 
[![Udacity - Self-Driving Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)

The fourth  assignement project  in Term 1 for submission. 


[Udacity Self-Driving Car Engineer Nanodegree](https://www.udacity.com/course/self-driving-car-engineer-nanodegree--nd013)

In this project, your goal is to write a software pipeline to identify the lane boundaries in a video from a front-facing camera on a car. The camera calibration images, test road images, and project videos are available in 
<https://github.com/udacity/CarND-Advanced-Lane-Lines>

## Submission Requirment :
 1.Writeup
 
 2.Code (or a Jupyter notebook)
 
 3.Example output images. 
 
 4.Output Video.
 
 ### Acceptance Criteria :
 <https://review.udacity.com/#!/rubrics/322/view>
 
 ### Setup Environmet :
 1. Set up `Starter Kit Installation`
 
   setup by using Anaconda
   <https://github.com/udacity/CarND-Term1-Starter-Kit/blob/master/README.md>
   
 2. TensorFlow
If you have access to a GPU, you should follow the TensorFlow instructions for installing TensorFlow with GPU support.

Once you've installed all of the necessary dependencies, you can install the tensorflow-gpu package:
```sh
pip install tensorflow-gpu
```
 ```sh
3. Open the Anaconda Command Prompt.
   example C:\Users\Atul\Anaconda3>
  
4. Run command >>activate carnd-term1

5. Go to the project_submission directory

6. Run >>jupyter notebook P4.ipynb

7. Run shell one by one 

8. Output video take time wait :)

```

Amazon Web Services
Instead of a local GPU, you could use Amazon Web Services to launch an EC2 GPU instance. (This costs money.)

Follow the Udacity instructions to launch an EC2 GPU instance with the udacity-carnd AMI.
Complete the Setup instructions. 

 ### Build Steps :
 ```sh
 1.All steps are based on windows 10 environement.
 
 2.Compute the camera calibration matrix and distortion coefficients given a set of chessboard images.
 
 3.Apply a distortion correction to raw images.
 
 4.Use color transforms, gradients, etc., to create a thresholded binary image.
 
 5.Apply a perspective transform to rectify binary image ("birds-eye view").
 
 6.Detect lane pixels and fit to find the lane boundary.
 
 7.Determine the curvature of the lane and vehicle position with respect to center.
 
 8.Warp the detected lane boundaries back onto the original image.
 
 9.Output visual display of the lane boundaries and numerical estimation of lane curvature and vehicle position.
 
 ```  
   
 ### Known Issues :
 ```sh
 1.Set up is not done for personal Linux environment.
 
 2.Some of package for python are installed manually.
 
 3. AWS setup is not working as per support project so done locally.
 ```
 
  ### From Git to Github :
 
 1. Cloning the repository by using command ```git clone Self-Driving-Car-Engineer-Nanodegree-Program--Project3 ```.
 
 2. Make changes and run the command ```git status``` for changed in local repository.
 
 3. Add all files in one command  ```git add .```
 
 4. Commit the code base by ```git commit -m "your comment" ```
 
 5. Check the github repository if you done change on github ```git pull origin master```
 
 6. Push your code by ```git push origin master```
 

