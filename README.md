# GeoTracker
Star Tracking System for Robotic Telescopes

The software developed in this project uses four data files ( hip main.dat , star list.dat ,
ra dec.dat , and cat dist.dat ) for catalogue re-processing, geometric voting and attitude
determination. 
Three pre-processing scripts, namely: ref cat.ipynb , eci coord.ipynb and cat dist.ipynb are used to generate
the reduced catalogue information based on the user's requirements for use with the geometric
voting algorithm. The only source file that needs to be stored on the processing
computer is geo att.ipynb, it performs the star extraction, identification and attitude
determination. This code reads in and manipulates the data files created by the preprocessing
scripts.

The program makes use of multiple open source packages for various purposes. These
are:
https://github.com/astropy/astropy
https://github.com/astropy/photutils
https://github.com/opencv/opencv
https://github.com/numpy/numpy
https://github.com/scipy/scipy
http://kieranwynn.github.io/pyquaternion/
https://github.com/numba/numba


