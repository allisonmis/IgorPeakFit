# IgorPeakFit
Standalone code for a peak fitting program useful in analyzing high-throughput XRD, Raman, etc. 


This ipf (Igor Procedure File, written for Igor Pro 8) contains a flexible peak-fitting program designed to aid in high-througput analysis. The program takes in a series of similar data sets (e.g. XRD patterns taken at multiple locations on a film with varying composition) and the expected locations of peaks. It cycles through each data set, fitting and returning peak width, height and location for each expected peak on each sample. The peaks can then be compared across the samples, or across multiple sets of data (e.g. multiple growth runs of multi-composition films). Also included are several short utilities for plotting and visualizing the extracted peak fit data.

For more information, or to report a bug, please contact me at allison.mis@gmail.com
