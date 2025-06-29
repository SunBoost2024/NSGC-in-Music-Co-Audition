# NSGC-in-Music-Co-Audition

## Structure of EEG data:

EEG data is organized as a 30(participants)x633(epochs)x8(channels)x100(timepoints) matrix. Order of the channels: F3, F4,  T7,  T8, P3, P4, O1, O2. Epochs are valid time period in all music excerpts with correspoding timepoints. 

## Structure of behavioral data:

Behavioral data is organized as a 40x380 matrix. Each row correponds to behavioral data of one participant. Column 1 corresponds to participants' id, column 2 corresponds to participants' group id, column 3 corresponds to participants' gender (1=male), column 4 corresponds to participants' position in each group, column 5 corresponds to whether the participant's EEG data is included in neural analysis, column 6-365 correspond to emotional ratings of each music excerpt (15x24, basic emotion and aesthetic emotion), column 366-368 correspond to the real music order in each group (1=positive, 2=neural, 3=negative), column 369-380 correspond to IOS rating toward other participants (3x4, increasing participants' id and experimental phase).