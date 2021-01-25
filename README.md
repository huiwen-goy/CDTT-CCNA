
#### About this project
 
These were ~300 participants from the CCNA study; the three sub-datasets were Phase 1a, Phase 1b, and detailed CDTT data compiled from the raw Excel files.
 
#### About the code
 
The Rmd file "...merging" contains the code for merging the three datasets, based on participants' unique IDs. I used the participant list in the Phase 1b dataset as the "master" list, pulling in corresponding rows from Phase 1a and CDTT that had matching participant IDs. Note: Rows of NAs in the merged dataset likely indicate a typo or other issue in the participant IDs. One of the most common problems is an extra space after the participant ID, in the same cell. 

The Rmd file "...segmented_regression" contains code for a segmented regression analysis for SRT and PTA.

#### Results

The segmented regression analysis can be viewed here: [https://huiwen-goy.github.io/CDTT-CCNA/CDTT_CCNA_segmented_regression.html](https://huiwen-goy.github.io/CDTT-CCNA/CDTT_CCNA_segmented_regression.html)

The original regression and plots can be viewed here: [https://huiwen-goy.github.io/CDTT-CCNA/CDTT_CCNA_simple_regression.html](https://huiwen-goy.github.io/CDTT-CCNA/CDTT_CCNA_simple_regression.html)
