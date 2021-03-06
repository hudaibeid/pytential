pytential: 2D/3D Layer Potential Evaluation
===========================================

.. image:: https://gitlab.tiker.net/inducer/pytential/badges/master/pipeline.svg
   :target: https://gitlab.tiker.net/inducer/pytential/commits/master
.. image:: https://badge.fury.io/py/pytential.png
    :target: http://pypi.python.org/pypi/pytential

pytential helps you accurately evaluate layer
potentials (and, sooner or later, volume potentials).
It also knows how to set up meshes and solve integral
equations.

It relies on

* `numpy <http://pypi.python.org/pypi/numpy>`_ for arrays
* `boxtree <http://pypi.python.org/pypi/boxtree>`_ for FMM tree building
* `sumpy <http://pypi.python.org/pypi/sumpy>`_ for expansions and analytical routines
* `modepy <http://pypi.python.org/pypi/modepy>`_ for modes and nodes on simplices
* `meshmode <http://pypi.python.org/pypi/meshmode>`_ for modes and nodes on simplices
* `loopy <http://pypi.python.org/pypi/loo.py>`_ for fast array operations
* `pytest <http://pypi.python.org/pypi/pytest>`_ for automated testing

and, indirectly,

* `PyOpenCL <http://pypi.python.org/pypi/pyopencl>`_ as computational infrastructure

PyOpenCL is likely the only package you'll have to install
by hand, all the others will be installed automatically.

Resources:

* `documentation <http://documen.tician.de/pytential>`_
* `wiki home page <http://wiki.tiker.net/Pytential>`_
* `source code via git <http://github.com/inducer/pytential>`_
