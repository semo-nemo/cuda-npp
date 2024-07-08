# laplaceFilterNPP - Laplace Filter with NPP

## Description

A NPP CUDA Sample that demonstrates how to use NPP LaplaceBox function to perform a Laplace Filter.

## Key Concepts

Performance Strategies, Image Processing, NPP Library
  
## Build and Run
 
### Linux
The Linux samples are built using makefiles. To use the makefiles, change the current directory to the sample directory you wish to build, and run make:
```
$ cd <sample_dir>
$ make clean build
$ make run
```
![Original photo in colors](https://github.com/semo-nemo/cuda-npp/blob/main/semonemo_original.JPG?raw=true) 

![Black and White image, which is an input to the NPP Filter](https://github.com/semo-nemo/cuda-npp/blob/main/semonemo_bw.jpg?raw=true) 

![Output image converted using Laplace Filter](https://github.com/semo-nemo/cuda-npp/blob/main/semonemo_filterLaplaceBorder.jpg?raw=true) 

![Output image converted using Box Filter, code given in the lab](https://github.com/semo-nemo/cuda-npp/blob/main/semonemo_boxFilter.jpg?raw=true) 
