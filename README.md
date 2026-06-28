The .inp file contains the script for the sequential refinement in Topas v.6. 

It generates two output text files: a .res file containing all parameters required for data analysis and a .txt containing the raw and fitted data. 
The .res file includes cell parameters, Rwp, temperature in K and °C, volume and phase weight. The output can be modified in the local.inp file where the macro is defined.
The .txt file contains the observed pattern, the calculated one and the difference between them.

Both .txt and .res file are given as examples.

Each .ipynb notebook contains a Python script to visualise the outputs.
1) Plot_parameters.ipynb reads the .res file and plot the selected parameters;
2) Plot_patterns_Ref.ipynb provides scripts for single-pattern visualisation and for generating a waterfall plot of selected patterns.
