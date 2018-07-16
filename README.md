CMPT 365 Programming Assignment 2 
 
Objective :  
Learn fundamentals of multimedia manipulation (using libraries such as OpenCV) and user interface design 
 
Background :  
This application is a video-based program to help blind people. By using the sense of hearing this program should help our brain to construct a (gamma-corrected) grey image. We use the loudness to represents the intensity of the color, and the frequency to represent the location of the pixels. 
 
Libraries : 
In the assignment we uses  
 	1.OpenCV for the video 
 	2.JavaFX for the GUI  
 	3.Java Sound API for the sound 
 
Video : 
In the given skeleton code, we can play an image ( with sound.). We have to modified the file so that we can play a video. 
First we modified the open image function, by detecting the extension of the file to see if the selected file is a picture or is it a video. If it is a video, we used the helper function create frame grabber to divide the video into different frames. These frames will later be processed as images and use as inputs for the play image function. 
 
Sound :  
In the given skeleton code , there is one signal for the sound to be create when it “play” the image. We 
![image](https://github.com/KOKIAS/CMPT-365-A2/blob/master/1.jpg?raw=true)
have to modify it so that another signal of sound will play a click sound for every 2 frame. 
 
 
GUI : 
In the given skeleton code, it can only load the one given image, and it only has two buttons on the pop up window. We modified it so that users can chose their own file to be played and we also add an extra button, the stop “button” 
![image](https://github.com/KOKIAS/CMPT-365-A2/blob/master/image.png?raw=true)

We use the JFileChooser to allows users to chose the file they want to play. 
![image](https://github.com/KOKIAS/CMPT-365-A2/blob/master/2.jpg?raw=true)
