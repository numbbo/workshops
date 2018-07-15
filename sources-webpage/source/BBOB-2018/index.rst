.. _bbob2018page:

GECCO Workshop on Real-Parameter Black-Box Optimization Benchmarking (BBOB 2018)
================================================================================


Welcome to the web page of the 8th GECCO Workshop on Real-Parameter Black-Box Optimization Benchmarking (BBOB 2018)
taking place during GECCO 2018 in Kyoto, Japan.

    **WORKSHOP ON REAL-PARAMETER BLACK-BOX OPTIMIZATION BENCHMARKING (BBOB 2018)**

    | held as part of the
    |
    | **2018 Genetic and Evolutionary Computation Conference (GECCO-2018)**
    | July 15--19, Kyoto, Japan
    | http://gecco-2018.sigevo.org


| Submission Deadline: Tuesday, March 27, 2018 (not extendable!)
|


=======================================================  ========================================================================  =======================================================================================
`register for news <http://numbbo.github.io/register>`_  `COCO quick start (scroll down a bit) <https://github.com/numbbo/coco>`_  `latest COCO release <https://github.com/numbbo/coco/releases/>`_
=======================================================  ========================================================================  =======================================================================================


Quantifying and comparing the performance of optimization algorithms
is a difficult and tedious task to achieve. Yet, it is highly
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

Like for the previous editions of the workshop, we provide source code in
various languages (C/C++, Matlab/Octave, Java, and Python) to benchmark
algorithms on three different test suites (single-objective with and without
noise a well as a noiseless bi-objective suite). Postprocessing data and comparing
algorithm performance is equally automatized with COCO (up to
already prepared LaTeX templates for writing papers). As a new feature
for the 2018 edition, we provide significantly easier access to the already 
benchmarked data sets such that the analysis of already available COCO data
becomes simple(r).

Analyzing the vast amount of available benchmarking data (from 200+ experiments
collected throughout the years) will be therefore one special focus of BBOB-2018.
Given that the field of (multiobjective) Bayesian optimization received 
renewed interest in the recent past, we would also like to re-focus our
efforts towards benchmarking algorithms for expensive problems (aka
surrogate-assisted algorithms developed for limited budgets). Moreover,
several classical multiobjective optimization algorithms have not yet been
benchmarked on the bbob-biobj test suite, provided since 2016, such that
we encourage contributions on these three following topics in particular:

* expensive/Bayesian/surrogate-assisted optimization
* multiobjective optimization
* analysis of existing benchmarking data

Interested participants of the workshop are invited to submit any paper
around the topic of (blackbox) optimization benchmarking. These contributions
might or might not use the provided
LaTeX templates to visualize the performance of unconstrained single- or
multiobjective black-box optimization algorithms of their choice on any of
the provided testbeds. We particularly encourage submissions about
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
optimization benchmarking of continuous optimizers will be welcome
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
Basis of the workshop is the Comparing Continuous Optimizer platform
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
`here <https://github.com/numbbo/coco/releases/>`_. Please use at least version v2.2 for
running your benchmarking experiments in 2018.

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
until the deadline on February 27, 2018.

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
   http://coco.gforge.inria.fr/doku.php?id=algorithms and is easily
   accessible from the python ``cocopp`` module via its ``data_archive``
   sub-module.


Accepted Papers
---------------
Out of six submissions, the following four papers have been accepted after peer-review:

* Kouhei Nishida and Youhei Akimoto: "Benchmarking the PSA-CMA-ES on the BBOB Noiseless Testbed"
* Duc Manh Nguyen: "Benchmarking a Variant of the CMAES-APOP on the BBOB Noiseless Testbed"
* Aurore Blelly, Matheus Felipe-Gomes, Anne Auger, and Dimo Brockhoff*: "Stopping Criteria, Initialization, and Implementations of BFGS and their Effect on the BBOB Test Suite"
* Aljoša Vodopija, Tea Tušar, Bogdan Filipič: "Comparing Black-Box Differential Evolution and Classic Differential Evolution"


   
Links to Algorithm Data
-----------------------
The data of all submitted experiments can be found in the
`list of data sets <http://coco.gforge.inria.fr/doku.php?id=algorithms>`_.

   
   

Schedule
--------------------
This year, the BBOB-2018 workshop got assigned a single session at GECCO in which the talks are scheduled according
to the below table. Speakers are highlighted with a star behind the name if known. 
Please click on the provided links to download the slides.

.. tabularcolumns:: |l|p{5cm}|

+---------------+-------------------------------------------------------------------------------------------------------------------+
| **BBOB-2018**                                                                                                                     |
+---------------+-------------------------------------------------------------------------------------------------------------------+
| 09:30 - 09:45 | The BBOBies: Introduction to Blackbox Optimization Benchmarking                                                   |
|               | (`slides <http://coco.gforge.inria.fr/presentation-archive/2018-GECCO/01_Dimo_bbob-2018-intro.pdf>`__)            |
+---------------+-------------------------------------------------------------------------------------------------------------------+
| 09:45 - 10:05 | Kouhei Nishida* and Youhei Akimoto:                                                                               |
|               | Benchmarking the PSA-CMA-ES on the BBOB Noiseless Testbed                                                         |
|               | (`slides <http://coco.gforge.inria.fr/presentation-archive/2018-GECCO/02_Kohei_psa.pdf>`__)                       |
+---------------+-------------------------------------------------------------------------------------------------------------------+
| 10:05 - 10:25 | Duc Manh Nguyen*:                                                                                                 |
|               | Benchmarking a Variant of the CMAES-APOP on the BBOB Noiseless Testbed                                            |
|               | (`slides <http://coco.gforge.inria.fr/presentation-archive/2018-GECCO/03_Manh_cmaesapop.pdf>`__)                  |
+---------------+-------------------------------------------------------------------------------------------------------------------+
| 10:25 – 10:40 | Aurore Blelly, Matheus Felipe-Gomes, Anne Auger, and Dimo Brockhoff*:                                             |
|               | Stopping Criteria, Initialization, and Implementations of BFGS and their Effect on the BBOB Test Suite            |
|               | (`slides <http://coco.gforge.inria.fr/presentation-archive/2018-GECCO/04_bfgs.pdf>`__)                            |
+---------------+-------------------------------------------------------------------------------------------------------------------+
| 10:40 - 11:00 | Aljoša Vodopija, Tea Tušar*, Bogdan Filipič:                                                                      |
|               | Comparing Black-Box Differential Evolution and Classic Differential Evolution                                     |
|               | (`slides <http://coco.gforge.inria.fr/presentation-archive/2018-GECCO/05_tea_de.pdf>`__)                          |
+---------------+-------------------------------------------------------------------------------------------------------------------+
| 11:00 - 11:10 | The BBOBies: Wrap-up and Discussion                                                                               |
|               | (`slides <http://coco.gforge.inria.fr/presentation-archive/2018-GECCO/06_Dimo_bbob-2018-wrapup.pdf>`__)           |
+---------------+-------------------------------------------------------------------------------------------------------------------+
   



Important Dates
----------------

* **2018-02-27** paper submission system opened
* **2018-03-01** release 2.2 of the COCO platform: `<https://github.com/numbbo/coco/releases/>`_ (originally planned on **2018-01-05**)
* **2018-03-27** *paper and data submission deadline* (not extendable!)
* **2018-04-10** decision notification
* **2018-04-24** deadline camera-ready papers
* **2018-07-15** workshop

All dates are given in ISO 8601 format (yyyy-mm-dd).


Organizers
----------
* Anne Auger, Inria Saclay - Ile-de-France, France
* Julien Bect, CentraleSupélec, France
* Dimo Brockhoff, Inria Saclay - Ile-de-France, France
* Nikolaus Hansen, Inria Saclay - Ile-de-France, France
* Rodolphe Le Riche, Ecole Nationale Supérieure des Mines de Saint–Etienne, France
* Victor Picheny, INRA Occitanie-Toulouse, France
* Tea Tušar, Jožef Stefan Institute, Ljubljana, Slovenia


