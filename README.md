# Reflection and transmission coefficients at a solid-solid interface
Created by Cornelis Weemstra, May 7 2020. 

## Brief description

Jupyter notebooks (Python) that allow one to compute the reflection and transmission coefficients associated with a P-wave arriving at solid-solid interface. These notebooks are created for the purpose of a practical of the course _Physics for geosystems_ (Course of TU Delft's M.Sc. track _GeoEnergy Engineering_). Details of the three individual notebooks are given below. 

## Notebooks

* **Refl_Trans_coef.ipynb**:   
Most important notebook. Computation of reflection and transmission coefficients for an interface between a porous sandstone filled with gas and that same sandstone filled with water. The velocities and densities of these two different "solids" are computed by means of _Gassmann's equation_ for fluid substitution. Should run out of the box. The theory and system of equations are described in more detail in https://www.kweemstra.com/.

* **Refl_Trans_coef_students.ipynb**:
Trimmed down version of 'Refl_Trans_coef.ipynb'. The students are expected to write the missing pieces of code. This notebook can be run as a [Jupyter notebook on Microsoft Azure](https://notebooks.azure.com/kweemstra/projects "Notebook on Azure")

* **Reflection_Transmission_ammon.ipynb**:   
Notebook in which the reflection and transmission coefficients are computed based on the formulations in Aki & Richards (2nd edition; Section 5.2.4). The code is a translation of the [Matlab code posted by Charles J. Ammon on his personal page](https://sites.psu.edu/charlesammon/2017/01/19/seismic-reflectiontransmission-coefficients-with-matlab/ "Link to Charles J. Ammons's post"). The notebook merely served to validate the results obtained in 'Refl_Trans_coef.ipynb'.   
