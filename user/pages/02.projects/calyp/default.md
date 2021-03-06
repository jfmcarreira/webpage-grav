---
title: Calyp
author:
    username: jfmcarreira
process:
    markdown: true
    twig: false
markdown:
    extra: true
---


# [Calyp](https://github.com/pixlra/calyp)
## Enhanced YUV video player based on Qt focusing on image/video analysis


## Features
- Support for FFmpeg’s Libavformat and Libavcodec;
- Support for wide range of raw video formats;
- Support up to 16 bits per pixel
- Support for OpenCV image/video processing library
- Advanced frame zoom with easy to use pan function
- Synchronized zoom across several videos (perfect for comparison operations)
- Useful information in status bar, *e.g.*, pixel information
    Useful sidebars with frame information, *e.g.*, frame histogram
- Constant growing libs for stream and frame processing (CalypStream and CalypFrame)
- Advanced API for frame/video processing algorithms
- Frame level quality measurement API based on the CalypFrame class
- Powefull command-line tool for quality and frame processing algorithms (uses the referred APIs)

## Modules
- CalypLib: Low level library to handle streams and frames
- CalypModules: Abstract interface for frame processing modules
- CalypApp: High level graphical interface
- CalypTools: High level command line interface

## Frame Processing Modules
- Component filtering
- Frame difference, crop, shift, binarization
- Sub-sampling operations
- Measuring modules
- Modules based on Opencv:
    - Disparity estimation
    - Motion estimation

##  Supported Quality Metrics
- PSNR
- SSIM
- MSE

## Supported Formats
- Supports for the following pixel formats:
    * YUV: 420, 44, 422, 400
    * RGB
    * Gray
- Support containers:
    * Raw video (yuv,rgb,gray)
    * Portable Network Graphics (png)
    * Joint Photographic Experts Group (jpeg)
    * Windows Bitmap (bmp)
    * Tagged Image File Format (tiff)
    * Portable Map (ppm,pgm,pbm)

## Screenshots
![](calyp_several_sequences.png?cropResize=800)

## Developers
- **Joao Carreira**     (jfmcarreira@gmail.com)
- **Lui­s Lucas**        (luisfrlucas@gmail.com)

### Where is it?
* **Daily builds** available for Windows and Linux on [SourceForge page](https://sourceforge.net/projects/playuver/)
* **Source code** available on [Github](https://github.com/pixlra/calyp)

### Documentation
* [Doxygen](http://www.calyp.jfmcarreira.pt/)
