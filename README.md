fd169-image-processing-example
==============================

This python script accompagnies the paper "NRas slows the rate at which a model lipid bilayer phase separates" which was part of the 169th Faraday Discussion held at Nottingham, UK, 7-9 May 2014. The paper can be retrieved via its [doi:10.1039/c3fd00131h](http://dx.doi.org/10.1039/c3fd00131h).

## Aim

The paper discusses how applying simple image processing techniques to the results of molecular dynamics simulations can both simplify analyses and make new types of analysis possible. In this case we show how an edge detection algorithm can be used to measure the length of the interface in a phase-separating mixture of lipids.

This script is a deliberately simplified and stripped-down version of the code used to produce the images and figures in the paper to make it easier to understand and use.

## Prerequisities

You will need python2.6 or 2.7.

You will need to have installed the following python modules

- MDAnalysis
- numpy
- scipy
- matplotlib
- scikit-image

On a Mac many of these can be installed using [MacPorts](www.macports.org). [MDAnalysis](https://code.google.com/p/mdanalysis/) must be installed from source.

## Running

Run the python code detect-bilayer-phases.py, for example
```
python detect-bilayer-phases.py
```
The code should take less than a minute to run on a modern laptop.

## Expected output

Sixteen images (eight of each bilayer leaflet) will be produced in the png/ folder. These will resemble (but are not identical to) Fig. 3 in the paper.

Philip W Fowler
6 May 2014



