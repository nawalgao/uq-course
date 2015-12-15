# Introduction to Uncertainty Quantification

This version of the course is being taught at Purdue University during Spring 2016.
The code for the course is ME 59700.
The instructors are Prof. [Ilias Bilionis](http://www.predictivesciencelab.org/people.html) and
Prof. [Guang Lin](https://www.math.purdue.edu/~lin491/).
The class meets every Tuesday and Thursday 1:30pm-2:45pm at ME 3021.

The goal of this course is to introduce the fundamentals of uncertainty quantification to advanced undergraduates or graduate engineering and science students with research interests in the field of predictive modeling. Upon completion of this course the students should be able to:

+ Represent mathematically the uncertainty in the parameters of physical models.
+ Propagate parametric uncertainty through physical models to quantify the induced uncertainty on quantities of interest.
+ Calibrate the parameters of physical models using experimental data.
+ Combine multiple sources of information to enhance the predictive capabilities of models.
+ Pose and solve design optimization problems under uncertainty involving expensive computer simulations.

## Student Evaluation

+ 10% Participation
+ 60% Homework
+ 30% Final Project

## Lectures

+ [Lecture 1 - Introduction to Uncertainty Quantification](lectures/lec_01.ipynb) on 01/12/2016.

+ [Lecture 2 - Probability Theory](lectures/lec_02.ipynb) on 01/14/2016.

+ [Lecture 3 - Probability Distributions](lectures/lec_03.ipynb) on 01/19/2016.

+ [Lecture 4 - Bayesian Parameter Estimation, Hypothesis Testing, and Model Selection](lectures/lec_04.ipynb) on 01/21/2016.

+ [Lecture 5 - Uncertainty Propagation using Sampling Methods: Monte Carlo](lectures/lec_05.ipynb) on 01/26/2016.

+ [Lecture 6 - Uncertainty Propagation using Sampling Methods: Latin-hypercube designs](lectures/lec_06.ipynb) on 01/28/2016.

+ [Lecture 7 - Representation of Prior Uncertainty: The Maximum Entropy Principle](lectures/lec_07.ipynb) on 02/02/2016.

+ [Lecture 8 - Representation of Prior Uncertainty](lectures/lec_08.ipynb) on 02/04/2016.

+ [Lecture 9](lectures/lec_09.ipynb) on 02/09/2016.

+ [Lecture 10](lectures/lec_10.ipynb) on 02/11/2016.

+ [Lecture 11](lectures/lec_11.ipynb) on 02/16/2016.

+ [Lecture 12](lectures/lec_12.ipynb) on 02/18/2016.

+ [Lecture 13](lectures/lec_13.ipynb) on 02/23/2016.

+ [Lecture 14](lectures/lec_14.ipynb) on 02/25/2016.

+ [Lecture 15](lectures/lec_15.ipynb) on 03/01/2016.

+ [Lecture 16](lectures/lec_16.ipynb) on 03/03/2016.

+ [Lecture 17](lectures/lec_17.ipynb) on 03/08/2016.

+ [Lecture 18](lectures/lec_18.ipynb) on 03/10/2016.

+ [Lecture 19](lectures/lec_19.ipynb) on 03/22/2016.

+ [Lecture 20](lectures/lec_20.ipynb) on 03/24/2016.

+ [Lecture 21](lectures/lec_21.ipynb) on 03/29/2016.

+ [Lecture 22](lectures/lec_22.ipynb) on 03/31/2016.

+ [Lecture 23](lectures/lec_23.ipynb) on 04/05/2016.

+ [Lecture 24](lectures/lec_24.ipynb) on 04/07/2016.

+ [Lecture 25](lectures/lec_25.ipynb) on 04/12/2016.

+ [Lecture 26](lectures/lec_26.ipynb) on 04/14/2016.

+ [Lecture 27](lectures/lec_27.ipynb) on 04/19/2016.

+ [Lecture 28](lectures/lec_28.ipynb) on 04/21/2016.

+ [Lecture 29](lectures/lec_29.ipynb) on 04/26/2016.

+ [Lecture 30](lectures/lec_30.ipynb) on 04/28/2016.


## Homework Sets

+ [Homework 1](hw/hw_01.ipynb) due on 01/26/2016.

+ [Homework 2](hw/hw_02.ipynb) due on 02/09/2016.

+ [Homework 3](hw/hw_03.ipynb) due on 02/23/2016.

+ [Homework 4](hw/hw_04.ipynb) due on 03/08/2016.

+ [Homework 5](hw/hw_05.ipynb) due on 03/29/2016.

+ [Homework 6](hw/hw_06.ipynb) due on 04/12/2016.


## Installation of Required Software for Viewing the Notebookds

+ [Anaconda](https://www.continuum.io/downloads) from Continuum Analytics, is absolutely essential to group the installation of many packages.

+ A working latex distribution. We suggest [MacTex](https://tug.org/mactex/) for OS X users, and [MikTex](http://miktex.org) for Windows users.

+ [Jupyter Notebook Extensions](https://github.com/ipython-contrib/IPython-notebook-extensions)
is required to properly display latex in the document (bibliography and equation numbers).

+ Essential UQ software developed by the [Predictive Science Laboratory](http://www.predictivesciencelab.org):
    
    + [py-orthpol](https://github.com/PredictiveScienceLab/py-orthpol) for generating orthogonal polynomials with respect to arbitrary probability measures. Requires FORTRAN compiler.
    
    + [py-design](https://github.com/PredictiveScienceLab/py-design) for generating designs for computer codes. Requires FORTRAN compiler.

+ [RISE](https://github.com/damianavila/RISE.git) is required only if you want to view the presentation as slides.