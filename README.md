


# Computational Physics II: computational quantum mechanics

## Introduction 

This repository contain lecture slides, programs, exercises and
projects for a more advanced course in computational physics, with an
emphasis on quantum mechanical problems with many interacting
particles. The applications and the computational methods are relevant
for research problems in such diverse areas as nuclear, atomic,
molecular and solid-state physics, quantum chemistry and materials
science.

A theoretical understanding of the behavior of quantum-mechanical
many-body systems - that is, systems containing many interacting
particles - is a considerable challenge in that no exact solution can
be found; instead, reliable methods are needed for approximate but
accurate simulations of such systems on modern computers. New insights
and a better understanding of complicated quantum mechanical systems
can only be obtained via large-scale simulations. The capability to
study such systems is of high relevance for both fundamental research
and industrial and technological advances.

The aim of this course is to present applications of, through various
computational projects, some of the most widely used many-body methods
with pertinent algorithms and high-performance computing topics such
as advanced parallelization techniques and object
orientation. Furthermore, Machine Learning and quantum
computing may be presented if of interest. 
The methods and algorithms that will be studied
may vary from year to year depending on the interests of the
participants, but the main focus will be on systems from computational
material science, solid-state physics, atomic and molecular physics,
nuclear physics and quantum chemistry. The most relevant algorithms
and methods are microscopic mean-field theories (Hartree-Fock and
Kohn-Sham theories and density functional theories), large-scale
diagonalization methods, coupled-cluster theory, similarity
renormalization methods, and quantum Monte Carlo like Variational
Monte Carlo and Diffusion Monte Carlo approaches. Methods to study
phase transitions for both fermionic and bosonic systems can also be
studied.

## Textbooks

The textbooks we will use, in addition to our lecture notes, are 
- Federico Becca and Sandro Sorella, Quantum Monte Carlo Approaches for Correlated Systems, see https://www.cambridge.org/core/books/quantum-monte-carlo-approaches-for-correlated-systems/EB88C86BD9553A0738BDAE400D0B2900. This book is fully accessible from the university of Oslo library, log in to https://bibsys-almaprimo.hosted.exlibrisgroup.com/primo-explore/search?vid=BIBSYS. This book is going to be our main text.
- B. L. Hammond, W. A. Lester, Jr., and P. J. Reynolds, Monte Carlo Methods in Ab Initio Quantum Chemistry, see https://www.worldscientific.com/worldscibooks/10.1142/1170?srsltid=AfmBOorrVkCMZdlyIElZIyR5o4f59PKsCf-DN1DYqOFQ0nSWrEexSS9W#t=aboutBook 


### Useful Python libraries
Here we list several useful Python libraries we strongly recommend (if you use anaconda many of these are already there)

* _NumPy_:https://www.numpy.org/ is a highly popular library for large, multi-dimensional arrays and matrices, along with a large collection of high-level mathematical functions to operate on these arrays
* _The pandas_:https://pandas.pydata.org/ library provides high-performance, easy-to-use data structures and data analysis tools 
* _Xarray_:http://xarray.pydata.org/en/stable/ is a Python package that makes working with labelled multi-dimensional arrays simple, efficient, and fun!
* _Scipy_:https://www.scipy.org/ (pronounced “Sigh Pie”) is a Python-based ecosystem of open-source software for mathematics, science, and engineering. 
* _Matplotlib_:https://matplotlib.org/ is a Python 2D plotting library which produces publication quality figures in a variety of hardcopy formats and interactive environments across platforms.
* _Autograd_:https://github.com/HIPS/autograd can automatically differentiate native Python and Numpy code. It can handle a large subset of Python's features, including loops, ifs, recursion and closures, and it can even take derivatives of derivatives of derivatives
* _SymPy_:https://www.sympy.org/en/index.html is a Python library for symbolic mathematics. 
* _scikit-learn_:https://scikit-learn.org/stable/ has simple and efficient tools for machine learning, data mining and data analysis
* _TensorFlow_:https://www.tensorflow.org/ is a Python library for fast numerical computing created and released by Google
* _Keras_:https://keras.io/ is a high-level neural networks API, written in Python and capable of running on top of TensorFlow, CNTK, or Theano
* And many more such as _pytorch_:https://pytorch.org/,  _Theano_:https://pypi.org/project/Theano/ etc 

###  Useful C++ libraries

* _Armadillo_: http://arma.sourceforge.net/ Armadillo is a high quality linear algebra library (matrix maths) for the C++ language, aiming towards a good balance between speed and ease of use
* _Eigen_: http://eigen.tuxfamily.org/index.php?title=Main_Page Eigen is a C++ template library for linear algebra: matrices, vectors, numerical solvers, and related algorithms.
* _Scythe_: http://scythe.lsa.umich.edu/ The Scythe Statistical Library is an open source C++ library for statistical computation
* _Autodiff_: https://autodiff.github.io/ autodiff is a C++17 library that uses modern and advanced programming techniques to enable automatic computation of derivatives in an efficient and easy way.
* _Optmilib_: https://www.kthohr.com/optimlib.html OptimLib is a lightweight C++ library of numerical optimization methods for nonlinear functions.

