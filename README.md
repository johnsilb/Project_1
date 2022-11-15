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
There is not correlation between song length and and populatiry. The r-value clear shows that other factors are responsible for popularity of a song. Song length is distributed around 3.5 minutes is due to the technology of recording media. Before the advent of digital media, radio stations used 78 rpm 
records and then 45 rpm records which had play times of between 3 and 4 minutes. If a song was longer than the play length of the media, then it would not be played on the radio and consequently nobody would be exposed to the song. Even with the advent of digital media, average song lengths have maxed out at under 5 minutes in 1992 and has dropped to around 4:50 minutes currently. (source on current song length: https://www.vox.com/2014/8/18/6003271/why-are-songs-3-minutes-long )

Question 3: Is there a correlation b/w popularity and time since song release?

**Conclusion**
Yes, but not linear - the most popular songs are those which were recently released, as expected. However, the dataset does not have enough information to determine whether songs on Spotify overall have been growing in popularity. The same dataset over an expanded range of time would be useful for further analysis, as would total number of streams. (Because the "popularity" score only accounts for a song's position on the charts and the duration of its stay, there is no way of knowing whether more listens would be needed to maintain a chart position at different points of time.)

Question 4: What is the relationship between genre and popularity?

**Conclusion:**
We hypothesized that pop, rap, rock, and possibly R&B would be the most popular genres. While these genres do tend to contain the most popular songs, such songs are outliers. The most popular genres on aggregate are Latin and Reggae. The songs in the dataset were broken into 8 main genres, plus an additional category for "other" genres. Latin and Reggae were by far the most popular, with relatively "unpopular" songs in these genres being more popular than the "unpopular" songs of other genres. (All analyzed songs were in the top 200 at some point and therefore are objectively popular.) The "Latin" category does not include songs of other genres - for example a "Latin Pop" or "Latin Rap" song is classified as "Pop" or "Rap", respectively. The samples size for reggae is rather small, so more data points would be helpful.

The one-way ANOVA statistic between these groups is 17.65, with a negligible p-value. This shows a significant difference in the popularity of various genres that could not have happened randomly.


Question 5: Is there a difference in popularity by song release type? 

**Conclusion**
To understand if there was a statistically significant difference in popularity between songs released as singles, albums, or compilations, the data was grouped by release type and an ANOVA was conducted. The ANOVA found a p-value of 5.7e-221, indicating a strong significant difference between at least one of the groups. Digging further, independent t-tests were run between each of the three groups. All three groups showed significant statistical differences in popularity. To showcase this clearly, popularity medians by subroup were calculated. Songs released as singles were significantly more popular than those released as albums (p-value = 1.9e-206) or compilations (p-value = 3.4e-53), with a median popularity score of 980.65. Songs released within an album, while less popular than singles, were also significantly more popular than songs released as compilations (p-value = 3.3e-09), with a median popularity score of 388.80. Songs released as compilations had a mean popularity score of 320.99.

Question 6: Is there a difference in popularity by whether a song is explicit or clean? 

**Conclusion**
To understand if there was a statistically significant difference in popularity between songs that are explicit and clean, the data was grouped into two groups (explicit, not explicit) and an independent t-test. The independent t-test showed songs that are explicit are significantly different from those that are not (p-value = 2.84e-161). Popularity medians by subroup were calculated. Explicit songs had a median popularity score of 572, while non-explicit songs had a mean popularity score of 528. This information shows that explicit songs are significantly more popular than non-explicit, or clean songs. 
