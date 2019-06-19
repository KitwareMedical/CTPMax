# CTPMax
Repository for composite making of registered CTA and CTP .nrrd files.

PixelMax.ipynb is made in Linux using ITK. The registration of files is done using terminal commands with ITKTubeTK Registration through Jupyter Notebook.

Terminal commands do not handle spaces as part of the same file name, so NameChange.ipynb changes every space, double-space, or triple space into a single hyphen.

The masks used in PixelMax.ipynb were created using ITKTubeTK using ImageMath.

If no registration appears to be needed, PixelMaxNoRegistration.ipynb can be used, working much faster than PixelMax.ipynb, but this comes at the cost of accuracy.

The datasets used in this project are available at https://data.kitware.com/#collection/560022808d777f6ddc3da1ea/folder/560022808d777f6ddc3da1eb
