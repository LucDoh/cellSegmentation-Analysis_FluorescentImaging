# cellSegmentation-Analysis

This is a cell segmentation and analysis code written in Matlab for obtaining Delta F/F
from a TIF stack of fluorescent images. Running runAll.m will run the scripts in order
to pre-process, segment cells, analyze and plot the resulting estimated DeltaF/F on a
per cell, per frame basis. 

To run:
runAll('../data/6e6ACSF_0ms_3_MMStack.tif',100,2000,0.6

where here the TIF stack to analyze is named "6e6ACSF_0ms_3_MMStack.tif".
*** MUST have a TIF stack in a folder named data in the directory above this one. 