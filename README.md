Team 5 Readme.md


Is there a correlation between BPM and the popularity of a song?

Critical Terminology: 
BPM = Beats Per Minute. 

Analysis: 
The dataset analyzed included 170,610 songs, of which 163,528 (95.8%) were suitable for analysis and had data for all relevant fields. One song had a reported 0 beats per minute (BPM), which the analyst opined to be a data error. That song was removed from the analysis. 

The most popular BPM (mode) of this dataset was 100BPM, with 5816 occurrences within the dataset. The mean (average) BPM was 121.06, and the median was 120 BPM. Out of the 174 different BPMs which occurred in the dataset, the top 10 most popular BPMs accounted for nearly 25% of all songs, while the bottom 50% accounted for merely 8.39% of songs. 

The top 50% most popular BPMs were analyzed to avoid the analysis being significantly swayed by a small subset of data. It is important to note that 92.05% of all songs in the dataset are represented by the top 50% most popular BPMs, so this subset still uses a large majority of the available data. 

The analyst then determined the correlation between the median popularity, and the number of songs for a given BPM. This resulted in a pearson r-value of 0.283; a weak positive correlation. The analyst used median popularity to avoid the data being swayed by a small number of hyper-popular songs. 

__Conclusion:__ 
There is a weak positive correlation between the popularity of a tempo, and the popularity of a song. 
Songs based upon popular tempos are marginally more popular on average compared to songs based upon less popular tempos. 
