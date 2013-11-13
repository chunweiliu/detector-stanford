
Information
===========

This package is a skeleton which implemented the root
filter of the deformable part model using HOG features.

# Basic Usage

1. Download the VOC 2007 Dataset and extract it into the VOCtoolkit folder.
2. Type "make" in Terminal to compile the HOG and SVM code.
3. Run the "compile" script to compile the helper functions.
   (you may need to edit compile.m to use a different convolution 
    routine depending on your system)
4. Run the "pascal('person',2)" to train and evaluate the baseline.
   (in a range of 0.06-0.13)

# References

[1] Stanford course webpage. http://vision.stanford.edu/teaching/cs231b_spring1213/project.html
