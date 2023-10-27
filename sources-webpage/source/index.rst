
Welcome to the BBOB workshop series!
================================================


The Black-box Optimization Benchmarking (BBOB) workshop series provides an easy-to-use toolchain for
benchmarking black-box optimization algorithms for continuous and mixed-integer domains and a place to present, compare, and discuss
the performance of numerical black-box optimization algorithms. The former is realized through the Comparing Continuous
Optimizers platform (Coco).

So far, twelve workshops have been held (in 2009, 2010, 2012, 2013, 2015, `2016`_, `2017`_, `2018`_, `2019`_, `2021`_, `2022`_, and in `2023`_ at GECCO and in 2015 at CEC). 

The next workshop, `BBOB 2023 <BBOB-2023/index.html>`_, will take place at GECCO'2023.

.. _`2023`: BBOB-2023/index.html
.. _`2022`: BBOB-2022/index.html
.. _`2021`: BBOB-2021/index.html
.. _`2019`: BBOB-2019/index.html
.. _`2018`: BBOB-2018/index.html
.. _`2017`: BBOB-2017/index.html
.. _`2016`: BBOB-2016/index.html


..  with a `new focus on large-scale problems <BBOB-2017/index.html>`_


Generally, seven benchmark suites are available:

* ``bbob`` containing 24 noiseless functions
* ``bbob-noisy`` containing 30 noisy functions
* ``bbob-biobj`` containing 55 noiseless, bi-objective functions, generated from the ``bbob`` suite
* ``bbob-largescale`` containing 24 noiseless functions in dimension 20 to 640
* ``bbob-mixint`` containing 24 noiseless mixed-integer functions
* ``bbob-biobj-mixint`` containing 92 noiseless, bi-objective, mixed-integer functions
* ``bbob-constrained`` containing 10 noiseless functions with varying number of constraints.



.. * ``bbob-biobj-ext`` containing 92 noiseless, bi-objective functions, as an extension of ``bbob-biobj``

Note that due to the rewriting of the Coco platform, the ``bbob-noisy`` test suite is not yet available in the new code from http://github.com/numbbo/coco . Please use the old code at https://numbbo.github.io/coco/oldcode/bboball15.03.tar.gz instead for running experiments on ``bbob-noisy``.



Continuous Submission of Benchmarking Data
-------------------------------------------
Since 2020, we also welcome submissions of data from benchmarking experiments on the above test suites throughout the year. Please open a submission issue at https://github.com/numbbo/coco/issues/new/choose .


Table of Contents:
..................

.. toctree::
   :maxdepth: 2

   BBOB-2023/index
   BBOB-2022/index
   BBOB-2021/index
   BBOB-2019/index
   BBOB-2018/index
   BBOB-2017/index
   BBOB-2016/index
   bbobbefore2016


.. `new focus on mixed-integer problems`_ BBOB-2021/index.html
.. `new focus on large-scale problems`_ BBOB-2017/index.html
.. `new focus on multi-objective problems`_ BBOB-2016/index.html



.. Indices and tables
   ==================

   * :ref:`genindex`
   * :ref:`modindex`
   * :ref:`search`
