
#### About this project
 
There were about 300 participants who did a three-part study, with one dataset collected per study. The three datasets needed to be merged into one final dataset.
 
#### About the code
 
The Rmd file contains the code for merging the three datasets, based on participants' unique IDs. I used the participant list in the Phase 1b dataset as the "master" list, pulling in corresponding rows from Phase 1a and CDTT that had matching participant IDs.
 
Note of caution:
 
Any rows of NAs in the merged dataset means there was probably a typo or other issue in the participant IDs. One of the most common problems is an extra space after the participant ID, in the same cell. 