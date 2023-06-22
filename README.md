# Principles-of-Biomedical-Imaging

## Project 1: Effects of Motion on CT Imaging
This project focuses on simulate the process and analyze the effects of performing CT image reconstruction using the Radon Transform on the image when undergoing motion. The MATLAB 
program performs a simulation using motion blur where an image of a high contrast circle is blurred in random orientations for a specified number of frames. The Radon Transform is computed
as if the CT machine is rotating around the object 360 degrees. We observe that the precision of image reconstruction increases and SNR decreaseswith a larger number of frames, which 
indicates that a longer imaging duration is needed to avoid the effects of motion blur. 

## Project 2: Partial Fourier Reconstruction of MRI Images
This project focuses on implementing the partial Fourier reconstruction algorithm of brain MRI images. Partial Fourier reconstruction relies on the concept that information in the Fourier
space is symmetrical and thus you only need half of the data to reconstruct the entire image. As such, we experimented with the Zero-filling process which removes a specified fraction 
greater than 0.5 of the k-space data and reconstruct the image using the partial Fourier algorithm. We saw that a partial fraction of 0.75 was the lowest value that reconstructed the 
image with the highest precision. Thus, MRI imaging processes can be optimized by only collecting 75% of the spatial frequency information. 
