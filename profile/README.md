# MatTools

MatTools is a collection of toolboxes and applications for image processing and scientific computing with Matlab.

### Generic Toolboxes

* [MatGeom](https://github.com/mattools/matGeom): Matlab geometry toolbox for 2D/3D geometric computing.
* [MatImage](https://github.com/mattools/matImage): Image Processing library for Matlab, that extends and complements the Matlab Image Processing toolbox. Provides functions for image fitlering, analysis, generation of phantoms...
* [MatStats](https://github.com/mattools/matStats): Statistical Data Analysis Toolbox for Matlab. Provides a `Table` class similar to R's dataframe, as well as exploratory data analysis tools. Some features require the MatGeom library.
* [Matlab Image Class](https://github.com/mattools/matlab-image-class) (looking for a better name...): an image processing library based on a single `Image` class. Manages various image types and dimensionalities, as well as spatial calibration. Used as basis of the [ImageM](https://github.com/mattools/ImageM) application.
* [MatRegister](https://github.com/mattools/matRegister): a library for 2D/3D image registration, that can also manage registration of geometric data (point clouds, meshes...).

### Standalone applications

* [ImageM](https://github.com/mattools/ImageM): GUI for Image processing with Matlab. Based on [Matlab Image Class](https://github.com/mattools/matlab-image-class), and using [MatGeom](https://github.com/mattools/matGeom) and [MatStats](https://github.com/mattools/matStats).
* [ImageM](https://github.com/mattools/MeshViewer): a GUI for the visualization and manipulation of 3D polygonal meshes, based on [MatGeom](https://github.com/mattools/matGeom). Can be used to check the results of 3D mesh registration algorithms.
* 
### Utility toolboxes

* [matUtils](https://github.com/mattools/matUtils): general purpose utility functions for Matlab
* [matlab-templates](https://github.com/mattools/matlab-templates): a collection of functions for quickly generating pre-edited matlab files for specific use cases (new class file, new test case file...)
* [GenericDialog](https://github.com/mattools/GenericDialog): a simple generic dialog for choosing parameters, mimicking [ImageJ's GenericDialog](https://imagej.net/scripting/generic-dialog) functionalities
* [VersionNumber](https://github.com/mattools/VersionNumber): simple utility to manage version number as string.
* [optim-utils](https://github.com/mattools/optim-utils): some utility functions for working on optimization algorithms

### Incubating toolboxes

* [geometry](https://github.com/mattools/geometry): an object-oriented port of [MatGeom](https://github.com/mattools/matGeom), that defines a class hierarchy for representing 2D/3D geometries.

### Old stuff

* [polynomialCurves](https://github.com/mattools/polynomialCurves): representation of parametric 2D curves using polynomials, allowing to compute easily derivatives or normals.
