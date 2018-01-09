# UFDW Java Library

This is a GitHub fork of the UFDW Java library from the University of Florida Digital Worls Institute.

It includes the Java for Kinect (J4K) bindings for the Microsoft Kinect SDK.

More information can be found here:

- http://research.dwi.ufl.edu/ufdw/index.php

## Supported Platforms

We are currently only vendoring the native components for both Kinect models on 64-bit Windows.

## OpenGL Support

This fork/build of UFDW does *NOT* support OpenGL; many of the method calls and classes have been removed entirely.

JOGL is incompatible with many of our own 3D libraries and having it on the classpath is problematic.

You should use the UFDW download from the UFDW website if you need OpenGL/JOGL support.

## Disclaimers

Copied verbatim from the DWI Website:

Disclaimer: The names JAVA and KINECT and their associated logos are trademarks of their respective copyright owners Oracle and Microsoft. None of these companies endorse, fund, or are in any way associated with the UFDW library. 

Disclaimer: This software is provided for free without any warranty expressed or implied for academic, research, and strictly non commercial purposes only. By downloading this library you accept the [Terms and Conditions](http://research.dwi.ufl.edu/ufdw/terms.html).