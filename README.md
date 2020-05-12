# CDTT-CCNA
CDTT data from CCNA participants

The Rmd file contains the code I used for merging three datasets: CCNA Phase 1b data, CCNA Phase 1a data, and the full CDTT dataset (with both original and recalculated SRTs, and digit position data). I used the participant list in the Phase 1b dataset as the "master" list, pulling in corresponding rows from Phase 1a and CDTT that have matching participant IDs.

Warning: If there are rows of NAs in the merged dataset, it means that there was a typo in the participant IDs (typos can include an additional blank space after the ID) and the script couldn't find an ID that matched between 1b, 1a, and/or CDTT.
