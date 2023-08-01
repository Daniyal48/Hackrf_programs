<h1> Hackrf_programs </h1>
This repository ciontains simple and small programs for hackrf mostly focusing on transmission side of the hackerf One
Credits to: https://github.com/aricwang88/hackrf_WBFM_Transmit.
I made changes to this code and added some additional functions.
You are free to make changes to my code and optimize it.
###### Compilation:
gcc -o mp3_transmit mp3_transmit.c -lm -lmpg123 -lsndfile -lhackrf

#### Usage:
./mp3_transmit <Absolute File Path>

##### Issues:
First install all the necessary libraries
sudo apt install libhackrf-dev mpg123 libsndfile1
