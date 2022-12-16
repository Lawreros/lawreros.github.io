---
title: "Neuroparc"
excerpt: "Consolidation of a multitude of common parcellation methods for the human brain. Each method is stored as a '.nii.gz' file parcellation map in 1,2, and 4 mm^3 voxel resolutions <br/><img src='/images/custom/neuro_atlas.png' width='500' height='300'>"
collection: projects
date: 2021-03-01
---

## What are Brain Parcellations?
A parcellation method (in this case for brains), is a method by which the different areas in the brain can be broken into differnet parcels (or sets of distinct ideally spatially contiguous locations). What decides the boundaries for these regions of interest (ROIs) is highly dependent on phenomena of interest. ROIs can be defined by their architecture, their pattern of connectivity to other ROIs, the functional activity they exhibit, or their topographical representation.

## Why Create This?
[`neuroparc`](https://github.com/neurodata/neuroparc) is a repository for a wide variaty of common parcellation methods for the human brain. This repository was made to address the problem that there are many different parcellation methods used across different publications, with no "best" method for all analyses. Thus, if you want to compare how the different methods perform on your particular research, you have track down and download the parcellations one at a time. On top of that, once you found these files, you still would have to map them into a shared standardized space in order to compare.

The `neuroparc` repository was a simple solution to this problem by having all the parcellation methods in one location, registered to a standardized space (MNI152 6th generation), and at different resolutions.

## How to Use
The link to the repository can be found [here](https://github.com/neurodata/neuroparc). All you need to do is clone/download the repository to have access to all of the parcellation methods. For more information, see the published [article](https://www.nature.com/articles/s41597-021-00849-3).
