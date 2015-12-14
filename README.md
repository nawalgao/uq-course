# Introduction to Uncertainty Quantification

The goal of this course is to introduce the fundamentals of uncertainty quantification to advanced undergraduates or graduate engineering and science students with research interests in the field of predictive modeling. Upon completion of this course the students should be able to:

+ Represent mathematically the uncertainty in the parameters of physical models.
+ Propagate parametric uncertainty through physical models to quantify the induced uncertainty on quantities of interest.
+ Calibrate the parameters of physical models using experimental data.
+ Combine multiple sources of information to enhance the predictive capabilities of models.
+ Pose and solve design optimization problems under uncertainty involving expensive computer simulations.

## Installation

+ [Anaconda](https://www.continuum.io/downloads) from Continuum Analytics, is absolutely essential to group the installation of many packages.

+ [Jupyter Notebook Extensions](https://github.com/ipython-contrib/IPython-notebook-extensions)
is required to properly display latex in the document (bibliography and equation numbers).

+ Essential UQ software developed by the [Predictive Science Laboratory](http://www.predictivesciencelab.org):
    
    + [py-orthpol](https://github.com/PredictiveScienceLab/py-orthpol) for generating orthogonal polynomials with respect to arbitrary probability measures. Requires FORTRAN compiler.
    
    + [py-design](https://github.com/PredictiveScienceLab/py-design) for generating designs for computer codes. Requires FORTRAN compiler.

+ [RISE](https://github.com/damianavila/RISE.git) is required only if you want to view the presentation as slides.

## Lectures

+ [Lecture 1 - Introduction to Uncertainty Quantification](lec_01.ipynb)

+ [Lecture 2 - Introduction to Probability Theory](lec_02.ipynb)

+ [Lecture 3 - Probability Distributions](lec_03.ipynb)