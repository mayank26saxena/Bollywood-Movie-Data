## Bollywood Movie Data 

This repository contains the data for all Bollywood Movie Trailers released from 2008 to 2017. 

The following dataset includes 2 folders :
- frames: It has the corresponding frames for each second for all the trailers downloaded from YouTube.
- data: It has the corresponding information of gender and emotion detected at each frame for the video.

The dataset also includes the following files :
- complete-data.csv: It has gender and emotion information for each of the trailers in the data folder. It has the following columns :
(1) frame_number - the frame number of the trailer in which emotion and gender detection occurred
(2) man/woman - whether the detected person was a man or a woman
(3) emotion - the emotion potrayed by the man/woman detected in the image
(4) year - the year in which the movie was released
(5) movie_name - the name of the movie

### Example:
- The movie Raees (released in the year 2017) has a folder by the name 2017-raees in the frames folder. This folder has all the frames from the trailer of the movie. (Eg - frames/2017-raees/frame0.jpg , frames/2017-raees/frame1.jpg ....)
- The gender and emotion information for each frame whenever the detection was successful can be found in the folder by the name 2017-raees in the data folder. This folder has a .csv file which has all the data. (Eg - data/2017-raees/2017-raees.csv)

### More information
- 880 frames folder for each trailer
- 880 data files for each trailer
