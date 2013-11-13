
Information
===========

This package is from Stanford University. It implmented the root
filter of deformable part model using HOG features.

Basic Usage
===========

1. Download VOC Dataset and put it into the VOCtoolkit
2. Type "make" in Terminal
3. Open Matlab
4. Run the 'compile' script to compile the helper functions.
   (you may need to edit compile.m to use a different convolution 
    routine depending on your system)
5. Run pascal('person',2) and see the AP (in a range of 0.07-0.13)

References
===========
[1] Course webpage. http://vision.stanford.edu/teaching/cs231b_spring1213/project.html
