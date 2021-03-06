# MmaSurfer ####################################################################

A Mathematica library that facilitates interaction with the FreeSurfer fMRI 
tool.

## Contents ####################################################################

This repository contains four Mathematica package files:
 * **CorticalSurface.m** - A collection of functions for dealing with triangle
   meshes that compose the cortical surface of a brain hemisphere.
 * **CorticalVolume.m** - A collection of functions for dealing with cortical 
   volumes.
 * **FreeSurfer.m** - The core interop library between FreeSurfer and 
   Mathematica. Defines several functions that allow for easy access to subject
   data.
 * **VisualCortex.m** - A small set of functions for examining fMRI data 
   specifically relating to the occipital pole.

There is additionally a notebook file, **tutorial.nb**, which contains 
instructions and walkthroughs for installing and using the library.

## Notes #######################################################################

This library is currently undergoing many rapid changes; the tutorial notebook
is largely out of date, though many of the principles are correct. Expect the
contents to change over the next couple of months.

Additionally, this library will soon be depricated and replaced by the Neurotica
library, which will incorporate all of the MmaSurfer functionality as well as
additional functionality.

## License #####################################################################

The MmaSurfer library is copyright (C) 2013-2014 by Noah C. Benson and is 
provided under the terms of Eclipse Public License, version 1.0. See the file
LICENSE in the root of this repository for more information.
