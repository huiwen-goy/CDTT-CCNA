
#### About this project
 
These were ~300 participants from the CCNA study; the three sub-datasets were Phase 1a, Phase 1b, and detailed CDTT data compiled from the raw Excel files.
 
#### About the code
 
The Rmd file "...merging" contains the code for merging the three datasets, based on participants' unique IDs. I used the participant list in the Phase 1b dataset as the "master" list, pulling in corresponding rows from Phase 1a and CDTT that had matching participant IDs. Note: Rows of NAs in the merged dataset likely indicate a typo or other issue in the participant IDs. One of the most common problems is an extra space after the participant ID, in the same cell. 

The Rmd file "...analysis" contains code for visualizing the relationships between age, cognition, hearing and CDTT test performance, and code for analyses looking at how cognition potentially moderates the relationship between PTA and SRT.

#### Results

The analyses and results can be viewed here: [https://huiwen-goy.github.io/CDTT-CCNA/CDTT_CCNA_analysis.html](https://huiwen-goy.github.io/CDTT-CCNA/CDTT_CCNA_analysis.html)
