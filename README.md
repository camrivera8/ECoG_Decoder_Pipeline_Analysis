# ECoG_Decoder_Pipeline_Analysis
ECoG Decoder Pipeline Analysis
This file is the 


**This file requires the use of the GitHub package git+https://github.com/umnil/preprocessing-pipeline.git
...Either load from !pip or download for offline use




Method 1: Power Spectral Density
This script windows, labels, and Fourier Transforms packets of data per trial
Data is analyzed across 8 frequency bands and pushed through a machine-learning analysis

Method 2: Mean Amplitude
This script windows, labels, and filters data to maintain time (t) on the x-axis
Amplitude relative to 0 is averaged across 8 frequency bands per trial and pushed through a machine-learning analysis



This script uses .pickle files to save progress and skip steps when resuming.
Loading of pickle files indicats no need to re-run code before this step. 
