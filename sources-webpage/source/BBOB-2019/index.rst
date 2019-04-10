.. _bbob2019page:

GECCO Workshop on Real-Parameter Black-Box Optimization Benchmarking (BBOB 2019)
================================================================================


Welcome to the web page of the 9th GECCO Workshop on Real-Parameter Black-Box Optimization Benchmarking (BBOB 2019)
taking place during GECCO 2019 in Prague.

    **WORKSHOP ON REAL-PARAMETER BLACK-BOX OPTIMIZATION BENCHMARKING (BBOB 2019)**

    | held as part of the
    |
    | **2019 Genetic and Evolutionary Computation Conference (GECCO-2019)**
    | July 13--17, Prague, Czech Republic
    | http://gecco-2019.sigevo.org


| Submission Deadline: extended to Wednesday, April 10, 2019 (was: April 3, 2019)
|


=======================================================  ========================================================================  =======================================================================================
`register for news <http://numbbo.github.io/register>`_  `COCO quick start (scroll down a bit) <https://github.com/numbbo/coco>`_  `latest COCO release <https://github.com/numbbo/coco/releases/>`_
=======================================================  ========================================================================  =======================================================================================


Quantifying and comparing the performance of optimization algorithms
is a difficult and tedious task. Yet, it is highly
crucial in order to recommend algorithms performing well in practice.
The Black-box Optimization Benchmarking workshop series aims at bringing
together researchers from the optimization field to discuss the latest
achievements in (blackbox) optimization benchmarking as well as at
gathering and sharing data of extensive numerical benchmarking results.

Open to all topics around blackbox optimization benchmarking, 
a substantial portion of the workshops' past success can be attributed
to the Comparing Continuous Optimization benchmarking platform
(COCO, https://github.com/numbbo/coco ) that
builds the basis for all BBOB workshops and that allows 
algorithms to be benchmarked and performance data to be visualized
effortlessly.
Up to now, the BBOB workshops have covered
benchmarking of blackbox optimization algorithms for single- and bi-objective,
unconstrained problems in exact and noisy, as well as expensive and
non-expensive scenarios. 

Celebrating the tenth year anniversary of the first BBOB workshop this year, 
we plan a few extensions of COCO for 2019, in particular in terms of new test 
suites:

   * A large-scale test suite will provide the classical 24 BBOB
     functions in dimensions up to 640.
   * A mixed integer (single-objective) test suite will allow to test algorithms
     on versions of the classical BBOB test functions with some of the variables
     discretized.
   * A bi-objective mixed integer test suite which is a discretized version of
     the previously introduced bbob-biobj suite.


Like for the previous editions of the workshop, we will provide source code in
various languages (C/C++, Matlab/Octave, Java, and Python) to benchmark
algorithms on the various COCO test suites (besides the above, also the
previously introduced single-objective suites with and without noise as well as
a noiseless bi-objective suite). Postprocessing data and comparing
algorithm performance will be equally automatized with COCO (up to
already prepared LaTeX templates for writing papers). 

Analyzing the vast amount of available benchmarking data (from 200+ experiments
collected throughout the years) will be again a special focus of BBOB-2019.
As always, we encourage contributions on all kinds of benchmarking aspects,
in particular:

* benchmarking expensive/Bayesian/surrogate-assisted optimization
* comparisons between deterministic and stochastic approaches
* benchmarking of multiobjective optimization algorithms
* analysis of existing benchmarking data
* the suggestion and analysis of new test functions

Interested participants of the workshop are invited to submit a paper 
which might or might not use the provided
LaTeX templates to visualize the performance of unconstrained single- or
multiobjective black-box optimization algorithms of their choice on any of
the provided test suites. We encourage particularly submissions about
algorithms from outside the evolutionary computation community as well as
any papers related to topics around optimization algorithm benchmarking.

If participants wish to contribute to the BBOB workshop by submitting
data sets, obtained with COCO, the tasks are as usual: run your favorite
single- or multiobjective black-box optimizer (old or new) by using the wrappers
provided (in C/C++, Python, Java, and Matlab/Octave) and run the
post-processing procedure (provided as well) that
will generate automatically all the material for a workshop paper
(ACM compliant LaTeX templates available). A description of the algorithm and the
discussion of the results completes the paper writing.

Note again that any other submission, related to black-box
optimization benchmarking will be welcome
as well. The submission section below gives a few examples of 
subjects of interest.

During the workshop, algorithms, results, and discussions will be presented by
the participants. An overall analysis and comparison of all submitted
algorithm data is going to be accomplished by the organizers and the overall 
process will be critically reviewed.

.. A plenary discussion on future improvements will,
   among others, address the question, of how the testbeds should evolve.


Updates and News
----------------
Get updated about the latest news regarding the workshop and
releases and bugfixes of the supporting NumBBO/COCO platform, by
registering at http://numbbo.github.io/register.


Supporting material
-------------------
The basis of the workshop is the Comparing Continuous Optimizer platform
(https://github.com/numbbo/coco), now rewritten fully in ANSI C with
other languages calling the C code. Languages currently available are
C, Java, MATLAB/Octave, and Python.

Most likely, you want to read the `COCO quick start <https://github.com/numbbo/coco>`_
(scroll down a bit). This page also provides the code for the benchmark functions [1]_, for running the
experiments in C, Java, Matlab, Octave, and Python, and for postprocessing the experiment data
into plots, tables, html pages, and publisher-conform PDFs via provided LaTeX templates.
Please refer to http://numbbo.github.io/coco-doc/experimental-setup/
for more details on the general experimental set-up for black-box optimization benchmarking.

The latest (hopefully) stable release of the COCO software can be downloaded as a whole
`here <https://github.com/numbbo/coco/releases/>`_. Please use at least version v2.2.2 for
running your benchmarking experiments in 2019.

Documentation of the functions used in the ``bbob-biobj`` suite
is provided at http://numbbo.github.io/coco-doc/bbob-biobj/functions/ .

.. [1] Note that the current release of the new COCO platform does not contain the 
   original noisy BBOB testbed yet, such that you must use the old code at 
   http://coco.gforge.inria.fr/doku.php?id=downloads for the time
   being if you want to compare your algorithm on the noisy testbed.



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
until the (extended) deadline on April 10, 2019. ACM-compliant
LaTeX templates are available in the github repository under
`code-postprocessing/latex-templates/ <https://github.com/numbbo/coco/tree/master/code-postprocessing/latex-templates>`_.

In order to finalize your submission, we kindly ask you to fill in
addition the form at http://numbbo.github.io/submit where you are 
supposed to provide a link to your data as well if this applies.
To upload your data to the web, you might want to use
https://zenodo.org/ which 
offers uploads of data sets up to 50GB in size or any other provider
of online data storage.
Please let us know briefly in the mandatory ``Data`` field, why you do
not provide any data for example in case you submit a paper unrelated
to the above BBOB test suites.


.. [2] The data of previously compared algorithms can be found at 
   http://coco.gforge.inria.fr/doku.php?id=algorithms and are easily
   accessible by name in the ``cocopp`` post-processing and from the python
   ``cocopp.archives`` module.





Important Dates
----------------

* **2019-02-27** paper submission system opens
* **2019-03-15** release 2.3 of the COCO platform with the new large-scale and mixed integer suites: `<https://github.com/numbbo/coco/releases/>`_ (originally planned on **2019-03-06**)
* **2019-04-10** *paper and data submission deadline* (not extendable, was: April 3)
* **2019-04-17** decision notification
* **2019-04-24** deadline camera-ready papers
* **2019-04-24** deadline author registration
* **2019-07-13** or **2019-07-14** workshop

All dates are given in ISO 8601 format (yyyy-mm-dd).


Organizers
----------
* Anne Auger, Inria Saclay - Ile-de-France, France
* Dimo Brockhoff, Inria Saclay - Ile-de-France, France
* Nikolaus Hansen, Inria Saclay - Ile-de-France, France
* Tea Tušar, Jožef Stefan Institute, Ljubljana, Slovenia
* Konstantinos Varelas, Thales LAS France SAS - Limours and Inria Saclay - Ile-de-France, France

