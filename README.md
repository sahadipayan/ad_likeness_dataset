The degree to which advertisements are successful is of prime concern for vendors in highly competitive global markets. Given the astounding growth of multimedia content on the internet, online marketing has become another form of advertising. Researchers consider advertisement likeability a major predictor of effective market penetration. A data set named the ‘BUET Advertisement Likeness Data Set’, containing annotations of frame‐wise likeability scores for various categories of advertisements, is introduced here.

# Contents of the dataset
The dataset includes 25 Bangladeshi advertisement clips that are annotated by raters. These clips are publicly available on YouTube and televised on over 20 TV channels in Bangladesh. The advertisement clips are classiﬁed into ﬁve different categories - Entertaining, Creative, Emotional, Humorous, and Miscellaneous, each having unique characteristics. 
A video is categorized based on the overall impression obtained from the raters. Each category has a number of videos ranging from 4 to 6. Frame-rate of the videos varies between 25 fps and 30 fps. 
The total number of frames in each category ranges from 5850 to 9550, with a duration of 224 seconds to 370 seconds, respectively. The resolution of a frame of these videos is 1280×720. 
The folder 'ADVERTISEMENT CLIPS' contains 25 Bangladeshi advertisement video clips.
The folder 'Reaction Video' has 20 sub-folders. Each subfolder is titled 'Person N,' where 'N' indicates the annotator serial number. Each sub-folder contains 25 reaction videos against advertisement video clips.
For example, 'person20_25.mp4' indicates that this is the facial response of the 20th annotator against the 25th advertisement clip. 'annotation.xlsx' contains both ground truth and individual frame-by-frame annotations of raters against each video.

# Where you can find the full dataset? 
Due to the absence of a publicly available data set containing annotation of frame‐wise likeability scores for advertisement
clips, a new data set is compiled. The data set is named as ‘BUET Advertisement Likeability Data set’, which can be accessed from https://urlzs.com/uMm9S with the password `BUETSMMR’.

# Annotation Process
There were 30 raters who participated in the annotation process.
Each rater watched each advertisement clip with sound in a quiet
environment. With permission, their reaction video to each
advertisement was recorded using a web camera. Then, each
rater was asked to watch the video again and to give any real
number as a score of likeability in the range between 1 and 5 for
every 2 s of the video scene. Based on the significant change in
their facial expression in response videos, the best 20 raters were
chosen. The final likeability score of a particular 2 s shot was
obtained by averaging the annotations of these 20 raters. Such
annotation process was inspired by Title‐based Video Summarization (TVSum) data set that is a benchmark data set for video
summarization techniques.

