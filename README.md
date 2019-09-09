# Exercise 2

This assignment is due by 11:59PM ET 9/14.

# Submission Instructions

1. Fork this repository from the GitHub page.
2. Clone the repository to your computer using git so that you have your own copy to edit and submit.
3. Add the Singularity command line you used to the `sbatch.sh` file
4. Add your `bidsmap.yaml` file to this repository
5. Recursively list the files in the `bids` directory you create and add this as `filelist.txt`
5. Using git, commit your changes (remember to git add your files first).
6. Using git, push your code to your forked repository.
7. On GitHub, create a pull request to submit your work.

# Exercise

Convert the DICOM data provided at `/scratch/psyc5171/exercises/ex2/NIDB-865.zip` to BIDS format. You must include a command for converting a directory of DICOMs to BIDS form (i.e. the very last command of the BIDScoin process) that can be run on the HPC system using Singularity, but you are not required to perform the other steps on the cluster.


## Overview of the experiment

The following scans were collected:

- An MPRAGE anatomical
- 2 runs of the **prosody** fMRI task
- 1 run of the **music** fMRI task

# Reading

Read the [Lindquist 2008 paper](https://drive.google.com/drive/folders/1k_z_ZGM14KMywg4sRymFHIKSWqdDGd5t) on Google Drive.


