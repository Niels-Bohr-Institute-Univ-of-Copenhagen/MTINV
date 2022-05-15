    :::Regional Moment Tensor Inversion (RMTI) Time-Domain:::
   -----------------------------------------------------------

The MTINV is a collection of codes written to invert for the moment tensor of an earthquake given the three components of ground motion recorded at regional seismic stations (e.g., Ichinose et al., 2003).

These codes are organized to generate moment tensor solutions for a range of source depths and origin times (because of the trade-off between these two quantities).

Selection criteria can be developed or a built-in default fitness functions can be used for near-real time notification purposes but typically requires human review below some magnitude threshold. Version 3.0.3 also includes signal to noise ratios are computed and stored to be used as guide to define stations for use in the inversion.

The codes are also modularized for allowing flexibility for customization and upgrades. An online man pages are available and they are in HTML format.

Thanks to Gene Ichinose for proving such beautiful codes!! (Mohammad Youssof, NBI/KU)

Inversion toolkit written in C. Greens Function F-K Reflectivity in Fortran. It requires/optional text editor, Ghostscript, GMT, PDF/JPG viewers, (+C&F77 compilers)

Requires: C and Fortran compiler Tested Systems: MacOSX and Linux Instructions: Type make clean; make

Do not forget to set ./mtinv.3.x.x/bin directory to your executable PATH shell variables. See file environmental_variables.csh for additional required and optional environmental variables.

-- Gene Ichinose (Email: ichinose1@llnl.gov, Webpage: https://people.llnl.gov/ichinose1)
