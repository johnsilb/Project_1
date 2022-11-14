Team 5 Readme.md

Question 1: 
Is there a correlation between BPM and the popularity of a song?

Analysis: 
The dataset analyzed included 170,610 songs, of which 163,528 (95.8%) were suitable for analysis and had data for all relevant fields. One song had a reported 0 beats per minute (BPM), which the analyst opined to be a data error. That song was removed from the analysis. 

The most popular BPM (mode) of this dataset was 100BPM, with 5816 occurrences within the dataset. The mean (average) BPM was 121.06, and the median was 120 BPM. Out of the 174 different BPMs which occurred in the dataset, the top 10 most popular BPMs accounted for nearly 25% of all songs, while the bottom 50% accounted for merely 8.39% of songs. 

The top 50% most popular BPMs were analyzed to avoid the analysis being significantly swayed by a small subset of data. It is important to note that 92.05% of all songs in the dataset are represented by the top 50% most popular BPMs, so this subset still uses a large majority of the available data. 

The analyst then determined the correlation between the median popularity, and the number of songs for a given BPM. This resulted in a pearson r-value of 0.283; a weak positive correlation. The analyst used median popularity to avoid the data being swayed by a small number of hyper-popular songs. 

__Conclusion:__ 
There is a weak positive correlation between the popularity of a tempo, and the popularity of a song. 
Songs based upon popular tempos are marginally more popular on average compared to songs based upon less popular tempos. 

Question 2:
Is there a correlation between song length and the popularity of a song?

Analysis:
The is analysis used the same data set as above. 

The population mean, median and mode is roughly around 3.5 minutes. When I ran the r value of the data, there was  an r-value of .018.  The graph has been truncated at 600 secs/10 minutes because there are few songs that are longer and none of them have very significant popularity numbers. 

__Conclusion__
There is not correltaion between song length and and populatiry. The r-value clear shows that other factors are responsible for popularity of a song. Song length is distributed around 3.5 minutes is due to the technology of recording media. Before the advent of digital media, radio stations used 78 rpm records and then 45 rpm records which had play times of between 3 and 4 minutes. If a song was longer than the play length of the media, then it would not be played on the radio and consequently nobody would be exposed to the song. Even with the advent of digital media, average song lengths have maxed out at under 5 minutes in 1992 and has dropped to around 4:50 minutes currently. (source on current song length: https://www.vox.com/2014/8/18/6003271/why-are-songs-3-minutes-long )


Question 3:
How do emotions detected in English speaking songs in the top 200 correlate with popularity of a song and genre?

Analysis:
The emotions detected in the dataset were: anger, anticipation, disgust, fear, joy, sadness, surprise and trust. The data for each title was grouped for all 35 countries + global. The popularity was summed in order to take into consideration multiple entries, whereas the rates for each emotion were averaged. 

__Conclusion__
There was no recognizable trend of preponderant emotions in most popular songs, the measured emotions were dispersed throughout the data sample.
The most detected emotion in the sample was joy, followed by trust, anticipation, fear, sadness, anger, surprise and, lastly, disgust was the least detected emotion. Overall, positive emotions were predominant over negative emotions.
There is significant difference in how emotions are expressed throughout popular genres. The distribution of the emotions can be considered counter intuitive, showing modern rock, for instance, as noticeably less emotional than edm (electronic dance music).

