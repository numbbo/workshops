
Welcome to the BBOB workshop series!
================================================


The Black-box Optimization Benchmarking (BBOB) workshop series provides an easy-to-use toolchain for
benchmarking black-box optimization algorithms for continuous domains and a place to present, compare, and discuss
the performance of numerical black-box optimization algorithms. The former is realized through the Comparing Continuous
Optimizers platform (Coco).

So far, seven workshops have been held (in 2009, 2010, 2012, 2013, 2015, and 2016 at GECCO and in 2015 at CEC). The next workshop,
`BBOB 2017 <BBOB-2017/index.html>`_, is going to take place at GECCO 2017 with a continued emphasis on our bi-objective test suite(s).

..  with a `new focus on large-scale problems <BBOB-2017/index.html>`_


Generally, four benchmark suites are available:

* ``bbob`` containing 24 noiseless functions
* ``bbob-noisy`` containing 30 noisy functions
* ``bbob-biobj`` containing 55 noiseless, bi-objective functions, generated from the ``bbob`` suite
* ``bbob-biobj-ext`` containing 92 noiseless, bi-objective functions, as an extension of ``bbob-biobj``

.. * ``bbob-largescale`` containing 24 noiseless functions in dimension 20 to 640.

Note that due to the rewriting of the Coco platform, the ``bbob-noisy`` test suite is not yet available in the new code from http://github.com/numbbo/coco . Please use the old code at http://coco.gforge.inria.fr/doku.php?id=downloads instead for running experiments on ``bbob-noisy``.

Table of Contents:
..................

.. toctree::
   :maxdepth: 2

   BBOB-2017/index
   BBOB-2016/index
   bbobbefore2016


.. `new focus on large-scale problems`_ BBOB-2017/index.html
.. `new focus on multi-objective problems`_ BBOB-2016/index.html



.. Indices and tables
   ==================

   * :ref:`genindex`
   * :ref:`modindex`
   * :ref:`search`
