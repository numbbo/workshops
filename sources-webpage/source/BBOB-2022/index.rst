.. _bbob2022page:

GECCO Workshop on Black-Box Optimization Benchmarking (BBOB 2022)
=====================================================================================================


Welcome to the web page of the 11th GECCO Workshop on Black-Box Optimization Benchmarking (BBOB 2022)
taking place online during GECCO 2022.

    **WORKSHOP ON BLACK-BOX OPTIMIZATION BENCHMARKING (BBOB 2022)**

    | held as part of the
    |
    | **2022 Genetic and Evolutionary Computation Conference (GECCO-2022)**
    | July 9--13, Boston, MA, USA
    | http://gecco-2022.sigevo.org


| Submission opening: February 11, 2022
| Submission deadline: April 11, 2022
| Notification: April 25, 2022
| Camera-ready: May 2, 2022 
| Presenter mandatory registration: May 2, 2022 

=======================================================  ========================================================================  =======================================================================================
`register for news <http://numbbo.github.io/register>`_  `COCO quick start (scroll down a bit) <https://github.com/numbbo/coco>`_  `latest COCO release <https://github.com/numbbo/coco/releases/>`_
=======================================================  ========================================================================  =======================================================================================

Benchmarking optimization algorithms is a crucial part in the design and
application of them in practice. Since 2009, the Blackbox Optimization
Benchmarking Workshop at GECCO has been a place to discuss general recent
advances of benchmarking practices and the concrete results from actual
benchmarking experiments with a large variety of (blackbox) optimizers.

The Comparing Continuous Optimizers platform (COCO [1]_,
https://github.com/numbbo/coco) has been developed in this context to
support algorithm developers and practicioners alike by
automating benchmarking experiments for blackbox optimization algorithms 
in single- and bi-objective, unconstrained continuous problems in exact 
and noisy, as well as expensive and non-expensive scenarios. In 2022,
we plan to provide, for the first time, a new
bbob-constrained test suite (work still in progress).

For the next BBOB 2022 edition of the workshop, we invite participants 
to discuss all kind of aspects of (blackbox) benchmarking but welcome
in particular contributions related to constrained optimization. As in
previous years, presenting benchmarking results on the supported test
suites of COCO are a focus, but submissions are not limited to those
topics:


* single-objective unconstrained problems (bbob)
* single-objective unconstrained problems with noise (bbob-noisy)
* biobjective unconstrained problems (bbob-biobj)
* large-scale single-objective problems (bbob-largescale) and
* mixed-integer single- and bi-objective problems (bbob-mixint and bbob-biobj-mixint)
* constrained optimization (bbob-constrained)

 
We encourage particularly submissions about algorithms from outside the 
evolutionary computation community and papers analyzing the large amount
of already publicly available algorithm data of COCO (see 
https://numbbo.github.io/data-archive/). Like for the previous editions,
we will provide source code in various languages (C/C++, Matlab/Octave,
Java, and Python) to benchmark algorithms on the various test suites
mentioned. Postprocessing data and comparing algorithm performance will 
be equally automatized with COCO (up to already prepared ACM-compliant 
LaTeX templates for writing papers). 

For more details, please see below.

.. [1] Nikolaus Hansen, Anne Auger, Raymond Ros, Olaf Mersmann, Tea Tušar, and 
   Dimo Brockhoff. "COCO: A platform for comparing continuous optimizers in 
   a black-box setting." Optimization Methods and Software (2020): 1-31.





Updates and News
----------------
Get updated about the latest news regarding the workshop and
releases and bugfixes of the supporting NumBBO/COCO platform, by
registering at http://numbbo.github.io/register.



Submissions
-----------
We encourage any submission that is concerned with black-box optimization 
benchmarking of continuous optimizers, for example papers that:

* describe and benchmark new or not-so-new algorithms on one of the
  above testbeds,
* compare new or existing algorithms from the COCO/BBOB database [2]_, 
* analyze the data obtained in previous editions of BBOB [2]_, or
* discuss, compare, and improve upon any benchmarking methodology
  for continuous optimizers such as design of experiments,
  performance measures, presentation methods, benchmarking frameworks,
  test functions, ...

    
Paper submissions are expected to be done through the official GECCO
submission system at  https://ssl.linklings.net/conferences/gecco/ 
until the deadline. ACM-compliant
LaTeX templates are available in the github repository under
`code-postprocessing/latex-templates/ <https://github.com/numbbo/coco/tree/master/code-postprocessing/latex-templates>`_.

In order to finalize your submission, we kindly ask you to submit
your data files if this applies by clicking on "Submit a COCO data set"
here: https://github.com/numbbo/coco/issues/new/choose.
To upload your data to the web, you might want to use
https://zenodo.org/ which 
offers uploads of data sets up to 50GB in size or any other provider
of online data storage.


.. [2] The data of previously compared algorithms can be found at 
   https://numbbo.github.io/data-archive and are easily
   accessible by name in the ``cocopp`` post-processing and from the python
   ``cocopp.archives`` module or in (fixed) html form at
   https://numbbo.github.io/ppdata-archive.


   


Supporting material
-------------------
The basis of the workshop is the Comparing Continuous Optimizer platform
(https://github.com/numbbo/coco), written in ANSI C with
other languages calling the C code. Languages currently available are
C, Java, MATLAB/Octave, and Python.

Most likely, you want to read the `COCO quick start <https://github.com/numbbo/coco>`_
(scroll down a bit). This page also provides the code for the benchmark functions [3]_, for running the
experiments in C, Java, Matlab, Octave, and Python, and for postprocessing the experiment data
into plots, tables, html pages, and publisher-conform PDFs via provided LaTeX templates.
Please refer to http://numbbo.github.io/coco-doc/experimental-setup/
for more details on the general experimental set-up for black-box optimization benchmarking.

The latest (hopefully) stable release of the COCO software can be downloaded as a whole
`here <https://github.com/numbbo/coco/releases/>`_. Please use at least version v2.5 for
running your benchmarking experiments in 2022.

Documentation of the functions used in the different test suites can be found here:

* ``bbob`` suite at https://numbbo.github.io/gforge/downloads/download16.00/bbobdocfunctions.pdf
* ``bbob-noisy`` suite at http://coco.lri.fr/downloads/download15.03/bbobdocnoisyfunctions.pdf
* ``bbob-biobj`` suite at https://numbbo.github.io/bbob-biobj/
* ``bbob-largescale`` suite at https://arxiv.org/pdf/1903.06396.pdf
* ``bbob-mixint`` and ``bbob-biobj-mixint`` suites at https://hal.inria.fr/hal-02067932/document and at https://numbbo.github.io/gforge/preliminary-bbob-mixint-documentation/bbob-mixint-doc.pdf
* ``bbob-constrained`` (in progress): http://numbbo.github.io/coco-doc/bbob-constrained/functions/



.. [3] Note that the current release of the new COCO platform does not contain the 
   original noisy BBOB testbed yet, such that you must use the old code at 
   https://numbbo.github.io/coco/oldcode/bboball15.03.tar.gz for the time
   being if you want to compare your algorithm on the noisy testbed.







Important Dates
----------------

* **2022-04-11** *paper and data submission deadline*
* **2022-04-25** decision notification
* **2022-05-02** deadline camera-ready papers
* **2022-05-02** deadline author registration
* **2022-07-09** or **2022-07-10** workshop

All dates are given in ISO 8601 format (yyyy-mm-dd).


Organizers
----------
* Anne Auger, Inria and CMAP, Ecole Polytechnique, Institut Polytechnique de Paris, France
* Dimo Brockhoff, Inria and CMAP, Ecole Polytechnique, Institut Polytechnique de Paris, France
* Konstantin Dietrich, TU Köln, Germany
* Paul Dufoss&eacute;, Inria and Thales, France
* Tobias Glasmachers, Ruhr-Universität Bochum, Germany
* Nikolaus Hansen, Inria and CMAP, Ecole Polytechnique, Institut Polytechnique de Paris, France
* Olaf Mersmann, , TU Köln, Germany
* Petr Pošík, Czech Technical University, Czech Republic
* Tea Tušar, Jozef Stefan Institute (JSI), Slovenia