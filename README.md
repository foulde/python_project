
# Data Analysis of youtube transcoding measurements


## File description

The repository contains following files:

- `model_transcoding_mesurment.ipynb` contain the models and training and their accuracy score along some plots. 
- `transcoding_mesurment.tsv` contain the dataset we will be using to predict transcoding time .
- `transcoding_mesurment_vizualisation.ipynb` contains the data analysis of the dataset through plots and the data preprocessing later used in `model_transcoding_mesurment.ipynb`.
- `image_presentation_python` contains interestings plot save for the ppt .
- `youtube_videos_vizualisation.ipynb` contain the data vizualisation for the other dataset `youtube_videos.tsv`. 
- `Python_project_presentation.pptx` contain the presentation of the project. 
- `README.md` this file 

## Data description

This section is about the `transcoding_mesurment.tsv` dataset:

- `id` video id of the video . 
- `duration` duration of the video in seconds.
- `codec` coding standard used for the video .
- `width` width of the video in pixel.
- `bitrate` bitrate bitrate(video) = video bitrate . 
- `framerate` height of the video in pixel. . 
- `i`  number of i frames in the video  . 
- `p`  number of p frames in the video . 
- `b`  number of b frames in the video . 
- `frames`  number of frames in the video . 
- `i_size` total size in byte of i videos . 
- `p_size` total size in byte of p videos . 
- `b_size` total size in byte of b videos . 
- `size` total size in byte of videos . 
- `o_codec` output codec used for transcoding  . 
- `o_bitrate` output bitrate used for transcoding . 
- `o_framerate` output framerate used for transcoding. 
- `o_width` output width in pixel used for transcoding. 
- `o_height` output height in pixel used for transcoding. 
- `umem` total codec allocated memory for transcoding . 
- `utime` total transcoding time for transcoding the data we try to predict





