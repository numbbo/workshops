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


| Submission Deadline: Tuesday, March 27, 2018
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
(COCO, https://github.com/numbbo/coco) ) that
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
submission system (details will follow around the time the submission
window opens on February 27, 2018).

In order to finalize your submission, we kindly ask you to fill outside
the form at http://numbbo.github.io/submit where you are supposed
to provide a link to your data as well if this applies.
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



.. Preliminary Schedule
   --------------------
   Both BBOB-2017 sessions took place on the second day of GECCO (Sunday July 16, 2017) in the Amethyst room. 
   Speakers are highlighted with a star behind the name if known. Please click on the provided links to download the slides.

   .. tabularcolumns:: |l|p{5cm}|

   +---------------+-------------------------------------------------------------------------------------------------------------------+
   | **Session I**                                                                                                                     |
   +---------------+-------------------------------------------------------------------------------------------------------------------+
   | 08:30 - 09:05 | The BBOBies: Introduction to Blackbox Optimization Benchmarking                                                   |
   |               |                                                                                                                   |
   +---------------+-------------------------------------------------------------------------------------------------------------------+
   | 09:05 - 09:30 | Simon Wessing*:                                                                                                   |
   |               | Benchmarking the SMS-EMOA with Self-adaptation on the bbob-biobj Test Suite                                       |
   |               | (`slides <http://coco.gforge.inria.fr/presentation-archive/2017-GECCO/02-Wessing-SMS-EMOA-SA.pdf>`__)             |
   +---------------+-------------------------------------------------------------------------------------------------------------------+
   | 09:30 - 09:55 | Mario García-Valdez* and Juan-J. Merelo:                                                                          |
   |               | Benchmarking a Pool-Based Execution with GA and PSO Workers on the BBOB Noiseless Testbed                         |
   +---------------+-------------------------------------------------------------------------------------------------------------------+
   | 09:55 - 10:20 | Zbynek Pitra*, Lukas Bajer, Jakub Repicky, and Martin Holena:                                                     |
   |               | Comparison of Ordinal and Metric Gaussian Process Regression as Surrogate Models for CMA Evolution Strategy       |
   |               | (`slides <http://coco.gforge.inria.fr/presentation-archive/2017-GECCO/04-Pitra-DTS-CMA.pdf>`__)                   |
   +---------------+-------------------------------------------------------------------------------------------------------------------+
   | **Session II**                                                                                                                    |
   +---------------+-------------------------------------------------------------------------------------------------------------------+
   | 10:40 - 10:50 | The BBOBies: Session Introduction                                                                                 |
   +---------------+-------------------------------------------------------------------------------------------------------------------+
   | 10:50 - 11:15 | Dogan Aydin* and Gurcan Yavuz:                                                                                    |
   |               | Self-adaptive Search Equation-Based Artificial Bee Colony Algorithm with CMA-ES on the Noiseless BBOB Testbed     |
   |               | (`slides <http://coco.gforge.inria.fr/presentation-archive/2017-GECCO/06-Aydin-SSEABC.pdf>`__)                    |
   +---------------+-------------------------------------------------------------------------------------------------------------------+
   | 11:15 - 11:40 | Duc Manh Nguyen and Nikolaus Hansen*:                                                                             |
   |               | Benchmarking CMAES-APOP on the BBOB Noiseless Testbed                                                             |
   +---------------+-------------------------------------------------------------------------------------------------------------------+
   | 11:40 - 12:05 | Takahiro Yamaguchi and Youhei Akimoto*:                                                                           |
   |               | Benchmarking the Novel CMA-ES Restart Strategy Using the Search History on the BBOB Noiseless Testbed             |
   |               | (`slides <http://coco.gforge.inria.fr/presentation-archive/2017-GECCO/08-Akimoto-KL-CMA.pdf>`__)                  |
   +---------------+-------------------------------------------------------------------------------------------------------------------+
   | 12:05 - 12:30 | The BBOBies: Wrap-up and Open Discussion                                                                          |
   +---------------+-------------------------------------------------------------------------------------------------------------------+
   
   .. |               | (`slides <http://coco.gforge.inria.fr/presentation-archive/2016-GECCO/05_Cheryl_MO-DIRECT.pdf>`__)                |


Important Dates
---------------

* **01/05/2018** release 2.2 of the COCO platform: `<https://github.com/numbbo/coco/releases/>`_
* **02/27/2018** paper submission system opens
* **03/27/2018** *paper and data submission deadline*
* **04/10/2018** decision notification
* **04/24/2018** deadline camera-ready papers
* **07/15/2018** or **07/16/2018** workshop



Organizers
----------
* Anne Auger, Inria Saclay - Ile-de-France, France
* Julien Bect, CentraleSupélec, France
* Dimo Brockhoff, Inria Saclay - Ile-de-France, France
* Nikolaus Hansen, Inria Saclay - Ile-de-France, France
* Rodolphe Le Riche, Ecole Nationale Supérieure des Mines de Saint–Etienne, France
* Victor Picheny, INRA Occitanie-Toulouse, France
* Tea Tušar, Jožef Stefan Institute, Ljublana, Slovenia


