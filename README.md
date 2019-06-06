# Comparing longitudinal registration tools for 2D MRI

## Project Description

Clinical neuroimaging data often include 2D MRI scans, taken across several points in time (i.e. longitudinally), in contrast to the cross-sectional 3D MRI typically found in research studies. Longitudinal brain imaging can be particularly useful in the analysis of volumetric changes or lesion burden for patients under clinical observation. Both SPM and FreeSurfer now offer tools for longitudinal registration and, as with most image processing tools, these have naturally been developed with research-quality data in mind. As researchers are increasingly gaining access to clinical data, however, it would be timely to determine how current longitudinal processing tools perform on lower-quality 2D MRI scans.  

Using the publicly-available OASIS dataset, we would like to investigate the performance of the SPM and FreeSurfer longitudinal registration tools. The OASIS-3 (Longitudinal Neuroimaging, Clinical, and Cognitive Dataset for Normal Aging and Alzheimer’s Disease) dataset consists of images from c.1000 subjects, many of which are accompanied by volumetric segmentation files produced through FreeSurfer. Using these files as a 'gold-standard', we plan to assess the longitudinal registration based on downsampled 2D data of the original 3D scans.

## Skills required to participate
Any of the following:

- Experience in programming (mainly Matlab, C or C++)  

- Experience with FreeSurfer or SPM12  

- Experience with structural image analysis

## Integration

Contributions towards any of the following milestones would be very welcome!

### Milestones

1. Downsample OASIS T1 3D data to lower-resolution 2D images  

2. Isolate the longitudinal registration codebase from FreeSurfer  

3. Longitudinal registration of 2D images in SPM and FreeSurfer  

4. Assessment of segmentation performance to original 3D images

## Preparation material

[The OASIS project](https://www.oasis-brains.org/)  
Chapter 27 (Longitudinal registration) of the [SPM 12 manual](https://www.fil.ion.ucl.ac.uk/spm/doc/spm12_manual.pdf)  
[FSL longitudinal processing](https://surfer.nmr.mgh.harvard.edu/fswiki/LongitudinalProcessing)

#### Papers
- M. Reuter, N.J. Schmansky, H.D. Rosas, B. Fisch (2012): [Within-subject template estimation for unbiased longitudinal image analysis](https://doi.org/10.1016/j.neuroimage.2012.02.084)  
- J. Ashburner, G.R. Ridgeway (2013): [Symmetric diffeomorphic modeling of longitudinal structural MRI](https://doi.org/10.3389/fnins.2012.00197)

## Communication
Join the chat in our [mattermost channel](https://mattermost.brainhack.org/brainhack/channels/longitudinal_2dmri) :)