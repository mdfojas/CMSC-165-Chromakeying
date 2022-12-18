# CMSC-165-Chromakeying
This is my project for CMSC-165 Chromakeying

The outputs can be seen in https://drive.google.com/drive/folders/13h3buA70CRkhMk3c5y1MuYIV9XuOoMVC?usp=share_link

The background output from the background getter is the bg.jpeg
kermit.mp4 is the input video where we will get the background. Its original dimensions are 540by360. I used other program to alter the dimension of the video and fit it to 1280by854.
The converted video resulted in 1282by854 which is still not a good dimension as the dimension we want is 1280by854. The approach used to correct this was to resize the image that would be written as bg to 1280by854.

Kermit_Input.mp4 is the video input of us dancing in a green screen. It was edited and fitted into a 1280by854 frame as our video size also foes not fit dimensions initially used for the bg.

The output folder contains all image sequence produced by the chromakeying code.

output_video.avi is the initial output of the chromakeying cell 3 code. It makes a video from the output image sequence of our program.

The final_output_video_with_sound.mp4 is th final output of this project. The otput_video.avi is edited using Adobe Premiere and added the sound from the kermit.mp4.

Contributors:
Mark Oliver D. Fojas - Created the chromakeying code, background getter, video maker cell, danced in the input
Daniella Vidanes - Found the kermit input video, helped find the bounds of green in the hsv color space, danced in the input, edited the dimensions of the input videos.
Carlos Rayel - Provided the tarpaulin for green screen, danced in the video. Nothing else.
