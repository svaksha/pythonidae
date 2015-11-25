+ [CRYPTOGRAPHY](#cryptography)
+ [MATH](#math)
+ [Algebra](#algebra)
+ [Calculus & Applied Math](#calculus-&-applied-math)
+ [Geometry](#geometry)
+ [Numerical Analysis](#numerical-analysis)
   + [Numerical Linear Algebra](#numerical-linear-algebra)
+ [RESOURCES](#resources)

----

# CRYPTOGRAPHY
+ [Cryptography](https://cryptography.io/) :: A package designed to expose cryptographic primitives and recipes to Python developers. [Source code](https://github.com/pyca/cryptography)
+ [ed25519](https://github.com/pyca/ed25519) :: Optimized version of the reference implementation of Ed25519.

----

# MATH
+ [bcolz](https://blosc.org) :: A columnar data container that can be compressed. [Source code and bug tracker](https://github.com/Blosc/bcolz)
   + Notebook showing the [Benchmark for querying the MovieLens dataset using pandas and bcolz](http://nbviewer.ipython.org/github/Blosc/movielens-bench/blob/master/querying-ep14.ipynb)
+ [beta_ntf](https://github.com/nils-werner/beta_ntf) :: Nonnegative Matrix and Tensor Factorization in Python. https://code.google.com/p/beta-ntf/
+ [bquery](https://github.com/visualfabriq/bquery) :: A query and aggregation framework for Bcolz.
+ [complex-numbers](https://github.com/j2kun/complex-numbers) :: The code respository for the post "Learning to Love Complex Numbers".
+ [impyla](https://github.com/cloudera/impyla) :: A Python client and Numba-based UDFs for Cloudera Impala, which allows you to rapidly analyze large, distributed data sets, but doesn't integrate easily with your ad hoc (Python) analytical tools (pandas, scikit-learn), which impyla aims to remedy.
+ [Smolyak](https://github.com/EconForge/Smolyak) :: Efficient implementations of Smolyak's algorithm for function approxmation in Python and Julia.
+ [symengine.py](https://github.com/symengine/symengine.py) :: Python wrappers for SymEngine.
+ [zero-modform](https://github.com/haochenuw/zero-modform) :: Polynomials satisfied by j-invariants of zeros of atkin-lehner eigenforms.

###### Resources
+ [Elementary Number Theory](https://github.com/williamstein/ent) :: Primes, Congruences, and Secrets.

----

# Algebra
+ [Mathics](https://github.com/mathics/Mathics) :: A general-purpose computer algebra system (CAS). It is meant to be a free, light-weight alternative to Mathematica.
+ [pykrylov](http://dpo.github.com/pykrylov) ::  A library of Krylov methods in pure Python.
+ [Sympy](http://sympy.org/) :: A computer algebra system for symbolic mathematics written in pure Python. [Source code](https://github.com/sympy/sympy).
+ [Thea](https://github.com/SciTools/thea):: Python GUI to visualise a cube.

#### Non-Linear Equations
+ [pyneqsys](https://github.com/bjodah/pyneqsys) :: Solving of symbolic systems of non-linear equations numerically.

###### Resources
+ [adeles](https://github.com/williamstein/adeles) :: Ideles adeles algebraic number theory.
+ Learn the [theory of linear algebra](https://github.com/ULAFF/notebooks) hand-in-hand with the practice of [software library development](https://www.edx.org/course/linear-algebra-foundations-frontiers-utaustinx-ut-5-02x)
+ Dr. Juan H Klopper has created an IPython notebook for each MIT-OCW lecture on [Linear Algebra (18.06)](http://www.juanklopper.com/opencourseware/mathematics-2/ipython-lecture-notes/) by [Prof. Gilbert Strang](http://www-math.mit.edu/~gs/).
+ [Coding_the_matrix](https://github.com/branner-courses/coding_the_matrix) is a self-Study of Linear Algebra Using Philip Klein's Materials.

----

# Calculus & Applied Math
+ [finitediff](https://github.com/bjodah/finitediff) → A Fortran-90 version of Begnt Fornberg's formulae for optimized inter-/extrapolation of data series for up to N-th order derivative with C/C++/Python bindings.
+ [HyperPython](https://github.com/ketch/HyperPython) :: A brief and practical introduction to the solution of [hyperbolic conservation laws](http://en.wikipedia.org/wiki/Hyperbolic_partial_differential_equation)

###### Resources
+ [Riemann Hypothesis book](http://wstein.org/rh/) with the [source code on github](https://github.com/williamstein/rh).

----

# Geometry
* [functional-differential-geometry](https://github.com/jtauber/functional-differential-geometry) :: Sussman and Wisdom's Functional Differential Geometry in Python.
* [Shapely](https://github.com/Toblerity/Shapely) :: Python package for manipulation and analysis of geometric objects in the Cartesian plane. [Documentation](http://toblerity.github.com/shapely/)


----

# [Numerical Analysis](https://en.wikipedia.org/wiki/Category:Numerical_analysis)

+ [Blaze](http://blaze.pydata.org) :: The next-generation of NumPy and Pandas for BigData.
   + [Multiuserblazeserver](https://github.com/ContinuumIO/multiuserblazeserver)
   **Resources**
   + [Benchmarking HDF5 and BLZ for genotype data storage and access](http://nbviewer.ipython.org/gist/alimanfoo/67fdcf58e364763fd0b6/benchmark_hdf5_blz.ipynb)
   + Matthew Rocklin's blog post on the [`into` function](http://matthewrocklin.com/blog/work/2015/02/03/Into/) being spun off into (pun intended) a separate project that encodes the conversions explicitly as a network.
   + [scipy2015-blaze-bokeh](https://github.com/chdoig/scipy2015-blaze-bokeh) :: Building Python Data Applications with Blaze and Bokeh Tutorial, SciPy 2015.
+ [Boost.NumPy](https://github.com/ndarray/Boost.NumPy) :: The Boost.Python interface for NumPy; in preparation for eventual proposal to Boost (manual mirror of Boost Sandbox SVN).
+ [ignition](https://github.com/IgnitionProject/ignition) :: A python automation project producing low-level optimized scientific code from high level language descriptions. A [numerical code generator](http://ignitionproject.github.io/ignition/).
+ [irlbpy](https://github.com/bwlewis/irlbpy) :: Truncated SVD by implicitly restarted Lanczos bidiagonalization for Python Numpy.
+ [LASS](https://github.com/cvxgrp/lass) :: Linear Algebra for Structured Sparse Matrices.
+ [La](http://pypi.python.org/pypi/la) :: Larry, the labeled numpy array. The main class of the la package is a labeled array, larry. A larry consists of data and labels. The data is stored as a NumPy array and the labels as a list of lists (one list per dimension). [Source Code](https://github.com/kwgoodman/la).
+ [Numba](http://numba.pydata.org/) → is a pure Python JIT(ted) complier to LLVM to improve and optimize NumPy.
+ [numexpr](https://github.com/pydata/numexpr) is a fast numerical array expression evaluator for Python, NumPy, PyTables, pandas, BLZ.
+ [NumPy](http://www.numpy.org) has support for linear algebra, large multi-dimensional arrays and matrices, along with a large library of high-level mathematical functions to operate on these arrays.
   + __Blogs, Books, Cookbooks, IPYNB's, Slides, Talks, Tutorials, Videos__
   + [CS231n Convolutional Neural Networks for Visual Recognition](https://cs231n.github.io/python-numpy-tutorial/)
   + [100 Numpy tricks](http://www.loria.fr/~rougier/teaching/numpy.100/index.html)
   + A quick reference guide to the commonly used [NumPy functions](http://people.duke.edu/~ccc14/pcfb/numpympl/NumpyBasics.html).
+ [Proteus](http://proteus.usace.army.mil) :: A Python package for rapidly developing computer models and numeric simulation methods. Get the [source code](https://github.com/erdc-cm/proteus) from github.
   + [IPython notebooks involving proteus](https://github.com/erdc-cm/proteus-notebooks).
+ [pyeq2](https://github.com/zunzun/pyeq2) :: A large collection of Python equations that can fit themselves to 2D and 3D data sets, output source code in several computing languages, and run a genetic algorithm for initial parameter estimation. Comes with cluster, parallel processing, GUI, NodeJS, and web-based graphical examples. Includes orthogonal distance and relative error regressions.
+ [python-flint/](http://fredrik-johansson.github.com/python-flint/) :: Python bindings for FLINT (Fast Library for Number Theory).
+ [SAGE](http://www.sagemath.org) → System for Algebra and Geometry Experimentation, is a mathematical software with features covering many aspects of mathematics, including algebra, combinatorics, numerical mathematics, number theory, and calculus. [Source code on github](https://github.com/sagemath/sage)
+ [SciPy](http://www.scipy.org) is a signal and image processing library that contains modules for optimization, linear algebra, integration, interpolation, special functions, FFT, signal and image processing, ODE solvers and other tasks common in science and engineering.
   + [Official Documentation](http://www.scipy.org/docs.html)
   + [scipy-lectures](http://scipy-lectures.github.io) :: Tutorial material on the scientific Python ecosystem.
+ [Tinynumpy](https://github.com/wadetb/tinynumpy) :: A lightweight, pure Python, numpy compliant ndarray class.

### Numerical Linear Algebra (NLA)
+ [cvxpy](https://github.com/cvxgrp/cvxpy) :: A Python-embedded modeling language for convex optimization problems. [Elemental](http://libelemental.org) is a distributed-memory dense and sparse-direct linear algebra and optimization library with third-party Python interfaces. [Source code](https://github.com/elemental/Elemental).

----

# RESOURCES
+ [Teaching numerical methods with IPython notebooks](https://github.com/ketch/teaching-numerics-with-notebooks) :: a tutorial prepared for Scipy 2014.
+ IPython Notebooks training material for [ML, Numpy, Pandas and IPython](https://github.com/addfor/tutorials) distributed by Addfor s.r.l.
+ [PyData Seattle 2015](https://github.com/wrobstory/pydataseattle2015) :: Python Data Bikeshed.

### Coursera.org
+ [High Performance Scientific Computing](https://www.coursera.org/course/scicomp)

