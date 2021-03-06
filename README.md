# ASTERICS - An Open Toolbox for Sophisticated FPGA-Based Image Processing

Image processing on embedded platforms is a challenging task, especially when implementing extensive computer vision applications. Field-programmable gate arrays (FPGAs) offer a suitable technology to accelerate image processing by customized hardware.

*ASTERICS* ("Augsburg Sophisticated Toolbox for Embedded Real-time Image Crunching Systems") is a modular framwork to perform various real-time image processing tasks. It offers modules and interfaces to perform various image processing including support for complex operations such as natural feature detection based on the *SURF* algorithm or variants of the *Generalized Hough Transform*.

This repository contains the core and free components of the *ASTERICS* framework. A list of publications and further information on the project can be found on the home page of the [Efficient Embedded Systems](http://ees.hs-augsburg.de) group at the University of Applied Sciences Augsburg.

---

## Getting Started

To get a fast introduction on how to use the ASTERICS framework, 
we advise you to take a look at the [ASTERICS manual](https://raw.githubusercontent.com/hsa-ees/asterics/master/doc/asterics-manual.pdf).

Chapter 2 "Using ASTERICS" gives information on 
 * how to setup ASTERICS (2.1) and
 * how to get startet with the reference demo design (2.2).


## Licensing and Additonal Modules

Files distributed with the ASTERICS (GitHub) repository generally refer to
the free and publicly available part of ASTERICS. This part is generally
licensed under the LPGL (see LICENSE for details).

However, there are more ASTERICS modules available, which are presently not
published under an open source license, but that can be made available
individually on a per-project basis. These include modules for:

* the Generalized Hough Transform and other variants of the Hough Transform
  [1, 2]

* low latency lense distortion removal and stereo rectification (NITRA) [4, 5]

* efficient, on-the-fly point feature extraction (SURF algorithm) [3]

Please contact the Efficient Embedded Systems (EES) group at the University of
Applied Sciences Augsburg (see the authors section in the ASTERICS manual) for
further information on using these modules and collaborating with the EES group.

## Acknowledgments

Parts of this work have been supported by the German Federal Ministry for
Economic Affairs and Energy (BMWi), grant number ZF4102001KM5 (2015-2018).

Parts of this work have been supported by the German Federal Ministry of
Education and Research (BMBF), grant number 17N3709 (2009-2013).

## References

##### [1] 
Julian Sarcher, Christian Scheglmann, Alexander Zoellner, Tim Dolereit,
Michael Schaeferling, Matthias Vahl, Gundolf Kiefer: "A Configurable
Framework for Hough-Transform-Based Embedded Object Recognition Systems",
IEEE International Conference on Application-specific Systems, Architectures
and Processors (ASAP) 2018, Mailand, 10. Juli 2018
    
##### [2] 
Gundolf Kiefer, Matthias Vahl, Julian Sarcher, Michael Schäferling: "A
Configurable Architecture for the Generalized Hough Transform Applied to the
Analysis of Huge Aerial Images and to Traffic Sign Detection",
IEEE International Conference on ReConFigurable Computing and FPGAs
(ReConFig), 2016, DOI: 10.1109/ReConFig.2016.7857143.

##### [3]
Matthias Pohl, Michael Schäferling, Gundolf Kiefer: "An Efficient FPGA-based
Hardware Framework for Natural Feature Extraction and Related Computer
Vision Tasks", 24th International Conference on Field Programmable Logic and
Applications (FPL), 2014, DOI: 10.1109/FPL.2014.6927463

##### [4]
Matthias Pohl, Michael Schäferling, Gundolf Kiefer, Plamen Petrow, Egmont
Woitzel, Frank Papenfuß: "Leveraging polynomial approximation for non-linear
image transformations in real time", Computers & Electrical Engineering,
Available online 23 January 2014, ISSN 0045-7906,
DOI: 10.1016/j.compeleceng.2013.12.011
    
##### [5]
Matthias Pohl, Michael Schäferling, Gundolf Kiefer, Plamen Petrow, Egmont
Woitzel, Frank Papenfuß: "An Efficient and Scalable Architecture for
Real-Time Distortion Removal and Rectification of Live Camera Images",
IEEE International Conference on ReConFigurable Computing and FPGAs
(ReConFig), 2012, DOI: 10.1109/ReConFig.2012.6416730.
