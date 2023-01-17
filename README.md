# Convolution
Convolution between two sounds ( University project )
The first part of thr code consists of the colvolution between two vectots ( vector A is given by the user, and vector B is standard [ 1/5, 1/5, 1/5, 1/5, 1/5].

The second part, which is the most interesting one, involves the convolution between two sound. Firstly, the sounds need to be converted to  vectors. 
The WavFileToArray uss python functions(numpy) and turns the wav files into vectors. After the convolution is done,the ArrayToWavFile, 
does the reverse process and turns the final vector into  a wav file.

The last part, creates a white sound and then performs the same convolution methos as is the previous two parts.

MyConvolve: 
This is the function that is included in every part of the script since it's the once that convolutes the two given vectors each time. The code is based on the 
following formula : 
![image](https://user-images.githubusercontent.com/118728873/212888745-0dc643bd-e42d-40b6-ab62-f40a75a17e8f.png)
