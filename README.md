# PatternFlow
Pattern recognition and image processing library for Tensorflow (TF)

This library is created and maintained by The University of Queensland [COMP3710](https://my.uq.edu.au/programs-courses/course.html?course_code=comp3710) students.

The library includes the following implemented in Tensorflow:
* fractals 
* algorithms
* recognition problems

In the algorithms, you will find many image processing algorithms ported to TF
* denoise algorithms 
* image processing algorithms 
* transform algorithms 
* metrics
* histograms
etc.

In the recognition folder, you will find many recognition problems solved including:
* OASIS brain segmentation
* Classification
etc.

# Improved Unet
Improved Unet is an improved form of the U-net network. The architecture is similar to the unet network our architecture comprises a context aggregation pathway that encodes increasingly abstract representations of the input as we progress deeper into the network, followed by a localization pathway that recombines these representations with shallower features to precisely localize the structures of interest. We refer to the vertical depth (the depth in the U shape) as level, with higher levels being lower spatial resolution, but higher dimensional feature representations.The main difference is the in improved u-net, is that gradient signals are injected deep into the network using deep super vision.
