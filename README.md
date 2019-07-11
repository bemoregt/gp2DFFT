# ofx2DFFT
2d fft of image using Openframeworks &amp; ofxCv

![fft2 example]( https://github.com/bemoregt/ofx2DFFT/blob/master/fft2.jpg "example")

![fft2 example2]( https://github.com/bemoregt/ofx2DFFT/blob/master/test2.png "example2")

![fft3 example2]( https://github.com/bemoregt/ofx2DFFT/blob/master/test3.png "example3")

![fft4 example2]( https://github.com/bemoregt/ofx2DFFT/blob/master/test4.png "example4")

![fft6 example6]( https://github.com/bemoregt/ofx2DFFT/blob/master/test6.png "example6")

### Algorithm
- Like the Fourier space, Phase space, and Hough space, Thess second spaces are very important to get more detailed features by post processing. But most vision libraries(OpenCV, etc) does not give 2nd spaces.
- This Second space is also images. so image processing for this 2nd space is very important. but most people just satisfied to get automatic (some imcomplet and many) output from libraries.
- In addition, This second spaces can be used to datasets for Deep learning to get invariantness, data compression, domain converting, etc.

### Dependency
- OpenFrameworks 0.10.1
- ofxCv
- ofxOpenCv
- ofxGUI
- XCode 10.12.x
- OSX Mojave

### Next Plan
- 2D FFTShift: Finished
- Pseudo Coloring for image spectrum.
- Video realtime FFT
- Mouse masking for 2D Notch Filtering
- Elapsed Time Display per resolution
- Radon Transform of Spectrum.
