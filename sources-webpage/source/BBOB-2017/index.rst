.. _bbob2016page:

GECCO Workshop on Real-Parameter Black-Box Optimization Benchmarking (BBOB 2017)
================================================================================


Welcome to the web page of the 7th GECCO Workshop on Real-Parameter Black-Box Optimization Benchmarking (BBOB 2017)
with focus on large-scale problems and continued emphasis on bi-objective problems which will take place during GECCO 2017.

    **WORKSHOP ON REAL-PARAMETER BLACK-BOX OPTIMIZATION BENCHMARKING (BBOB 2017)**

    | hold as part of the
    |
    | **2017 Genetic and Evolutionary Computation Conference (GECCO-2017)**
    | July 15--19, Berlin, Germany
    | http://gecco-2017.sigevo.org


| Submission Deadline: Tuesday, March 28, 2017
|


=======================================================  ========================================================================  =======================================================================================
`register for news <http://numbbo.github.io/register>`_  `Coco quick start (scroll down a bit) <https://github.com/numbbo/coco>`_  `latest Coco release <https://github.com/numbbo/coco/releases/>`_
=======================================================  ========================================================================  =======================================================================================


Quantifying and comparing the performance of optimization algorithms
is a difficult and tedious task to achieve. Previously, the Coco
platform has provided tools to ease this process for *single-objective*
noiseless and noisy problems and for *bi-objective* noiseless problems
by: (1) an implemented, well-motivated benchmark function
testbed, (2) a simple and sound experimental set-up, (3) the generation
of output data and (4) the post-processing and presentation of the
results in graphs and tables. All test functions, so far, have been
provided in low to medium dimension with 2 to 40 variables.
In 2017, we provide, for the first time, 
an extension of the Coco platform towards a *large-scale testbed*
with up to 640 variables and the same procedure as in
previous BBOB workshops. Addressing issues with the biobjective
``bbob-biobj`` suite from 2016, we also provide an extension of it
to 92 problems. Overall, we now provide the following test suites:

* ``bbob`` containing 24 noiseless functions
* ``bbob-noisy`` containing 30 noisy functions
* ``bbob-biobj`` containing 55 noiseless, bi-objective functions, 
* ``bbob-biobj-ext`` containing 92 noiseless, bi-objective functions, and
* ``bbob-largescale`` containing 24 noiseless functions in dimension 20 to 640.

The tasks for participants are as usual: run your favorite
single- or multiobjective black-box optimizer (old or new) by using the wrappers
provided (in C/C++, Python, Java, and Matlab/Octave) and run the
post-processing procedure (provided as well) that
will generate automatically all the material for a workshop paper
(ACM compliant LaTeX templates available). A description of the algorithm and the
discussion of the results completes the paper writing.

We encourage particularly submissions related to the new large-scale testbed
and algorithms for handling large-scale problems including also *algorithms
from outside the evolutionary computation community*. Submissions related to
the previously available ``bbob``, ``bbob-noisy``, and ``bbob-biobj`` testbeds,
and the new extended biobjective ``bbob-biobj-ext`` testbed, however, are more 
than welcome.

During the workshop, algorithms and results will be presented by
the participants. An overall analysis and comparison is going to be
accomplished by the organizers and the overall process will be
critically reviewed.

.. A plenary discussion on future improvements will,
   among others, address the question, of how the testbeds should evolve.


Updates and News
----------------
Get updated about the latest news regarding the workshop and
releases and bugfixes of the supporting NumBBO/Coco plateform, by
registering at http://numbbo.github.io/register.


Supporting material
-------------------
Most likely, you want to read the `Coco quick start <https://github.com/numbbo/coco>`_
(scroll down a bit). This page also provides the code for the benchmark functions, for running the
experiments in C, Java, Matlab, Octave, and Python, and for postprocessing the experiment data
into plots, tables, html pages, and publisher-conform PDFs via provided LaTeX templates.
Please refer to http://numbbo.github.io/coco-doc/experimental-setup/
for more details on the general experimental set-up for black-box optimization benchmarking.

The latest (hopefully) stable release of the Coco software can be downloaded as a whole
`here <https://github.com/numbbo/coco/releases/>`_. Please use at least version v2.0 for
running your benchmarking experiments.

Documentation of the functions used in the ``bbob-biobj`` and ``bbob-bobj-ext`` suites 
for BBOB 2017 are provided at http://numbbo.github.io/coco-doc/bbob-biobj/functions/ .

Note that the current release of the new Coco platform does not contain the original noisy BBOB testbed,
such that you must use the old code at http://coco.gforge.inria.fr/doku.php?id=downloads for the time
being if you want to compare your algorithm on the noisy testbed.


Submissions
-----------
Submissions of benchmarking results of new or existing numerical optimization algorithms in terms
of single- or bi-objective optimization are welcome and should be done through the
following form at http://numbbo.github.io/submit. To upload your data, you might want to use
https://zenodo.org/ which offers uploads of data sets up to 50GB in size or any other provider
of online data storage.



Important Dates
---------------

* **01/27/2017** release 2.0 of the Coco platform available: <https://github.com/numbbo/coco/releases/>`_
* **02/28/2017** release of the Coco software with the final functionality to run experiments
* **03/31/2017** *paper and data submission deadline*
* **04/17/2017** decision notification
* **04/24/2017** deadline camera-ready papers
* **07/15/2017** workshop


Organizers
----------
* Anne Auger, Inria Saclay - Ile-de-France, France
* Dimo Brockhoff, Inria Saclay - Ile-de-France, France
* Nikolaus Hansen, Inria Saclay - Ile-de-France, France
* Dejan Tušar, Inria Saclay - Ile-de-France, France
* Tea Tušar, Jozef Stefan Institute, Ljublana, Slovenia
