# Bezier-Extraction-Operator
This repository contains the Python code to calculate bezier extraction operator to generate the B-spline/NURBS basis function from Bezier basis functions. Along with the code, detailed documentation is added for better understanding of bezier extraction process.

#### Dependencies:

- In order to open code files, you need to install Jupyter-notebook (Anaconda) package into your laptop or PC.




#### What is Bezier Extraction?

Bezier extraction is clever implementation of Bezier decompositions, which it self application of knot-insertion process of Splines, i.e, B-Splines, NURBS and etc, to follow the Finite element data structure for the computer  implementation of isogeometric analysis. In brief Bezier extraction process converts the Bezier curves defined in any parametric space to the element wise B-spline basis functions in their respective parametric space. The whole process of Bezier to B-spline conversion of basis function can be done by a extraction matrix, which is called as extraction operator.

In a spline of multiple elements (knot vector with internal knot values), will have respective element's extraction operator to map Bezier basis function into particular basis function. In order to explain the whole method of Bezier extraction,  It is important to discuss the basic properties of splines and knot insertion operation and bezier decomposition.



