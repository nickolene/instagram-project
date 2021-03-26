# instagram-project

This folder outlines most of the analyses that were helpful to me as a graduate student working with fMRI data. This is meant for someone who has little to no 
programming experience and is stuck running analyses with limited resources. 

The "preprocessingpipeline" document will outline and include scripts to use for (MAC USERS):


1. Download all data from XNAT to a local computer
2. Install docker and fsl
3. Convert all raw data to BIDS format using heudiconv
4. Creating a code folder under "bids" (to store stuff like this) derivatives folder under "bids" folder (for mriqc, fmriprep, and fsl files)
5. Running MRIQC on bids data to check for quality assurance
6. Run fMRIPrep on bids data
7. Check the data from MRIQC and fMRIPREP to make sure you have no outliers.



Additional AMAZING tutorials can be found by Dr. Andy Jahn and Dr. Jeannette Mumford. Here are the links I used:

For fMRIPrep:https://andysbrainbook.readthedocs.io/en/latest/OpenScience/OS/fMRIPrep.html
For MRIQC: https://andysbrainbook.readthedocs.io/en/latest/OpenScience/OS/MRIQC.html 
^You'll notice our scripts are a little different than Andy's. It's just what worked for us. 

For FSL: https://www.youtube.com/watch?v=lCwewJJPd5U&t=12s
