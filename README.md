<h1> Hackrf_programs </h1>
<p>This repository contains simple and small programs for hackrf mostly focusing on transmission side of the hackerf One.<br>
You are free to make changes to my code and optimize it.</p>

<h1>Compilation:</h1>
<b>gcc -o mp3_transmit mp3_transmit.c -lm -lmpg123 -lsndfile -lhackrf</b>

<h1> Usage: </h1>
./mp3_transmit Absolute_File_Path
  
<h1> Issues: </h1>
<p>First install all the necessary libraries.<br>
<b>sudo apt install libhackrf-dev mpg123 libsndfile1</b></p>

<h1>Credits:</h1>
Credits to: https://github.com/aricwang88/hackrf_WBFM_Transmit.
