.. _bbob2021page:

GECCO Workshop on Black-Box Optimization Benchmarking (BBOB 2021)  - focus on mixed-integer problems
=====================================================================================================


Welcome to the web page of the 10th GECCO Workshop on Black-Box Optimization Benchmarking (BBOB 2021)
taking place online during GECCO 2021.

    **WORKSHOP ON BLACK-BOX OPTIMIZATION BENCHMARKING (BBOB 2021)**

    | held as part of the
    |
    | **2021 Genetic and Evolutionary Computation Conference (GECCO-2021)**
    | July 10--14, Lille, France
    | http://gecco-2021.sigevo.org


| Submission opening: February 11, 2021
| Submission deadline: April 12, 2021
| Notification: April 26, 2021
| Camera-ready: May 3, 2021 


=======================================================  ========================================================================  =======================================================================================
`register for news <http://numbbo.github.io/register>`_  `COCO quick start (scroll down a bit) <https://github.com/numbbo/coco>`_  `latest COCO release <https://github.com/numbbo/coco/releases/>`_
=======================================================  ========================================================================  =======================================================================================


Benchmarking of optimization algorithms is a crucial part in their design and
application in practice. The Comparing Continuous Optimizers platform (COCO, 
https://github.com/numbbo/coco) has been developed in the past decade to
support algorithm developers and practitioners alike by automating
benchmarking experiments for blackbox optimization algorithms in single- and 
bi-objective, unconstrained continuous problems in exact and noisy, as well as
expensive and non-expensive scenarios.

For the 11th Blackbox Optimization Benchmarking workshop 
(BBOB 2021) and the 10th edition at GECCO (1 workshop was held at CEC), 
we plan to widen our focus towards mixed-integer benchmark problems.
Concretely, we highly encourage submissions describing the benchmarking 
results from blackbox optimization algorithms on the single-objective 
bbob-mixint and the bi-objective bbob-biobj-mixint suites previously released 
at GECCO-2019.

Any other submission discussing other aspects of (blackbox) benchmarking, 
especially on the other available bbob, bbob-noisy, bbob-biobj, and
bbob-largescale test suites are welcome as well. We encourage particularly
submissions about algorithms from outside the evolutionary computation
community and papers analyzing the large amount of already publicly available
algorithm data of COCO (see https://numbbo.github.io/data-archive/).

Like for the previous editions of the workshop, we will provide source code in 
various languages (C/C++, Matlab/Octave, Java, and Python) to benchmark 
algorithms on the various test suites mentioned. Postprocessing data and 
comparing algorithm performance will be equally automatized with COCO
(up to already prepared ACM-compliant LaTeX templates for writing papers).

For details, please see below.



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
until the (extended) deadline on April 12, 2021. ACM-compliant
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
   https://numbbo.github.io/data-archive/ and are easily
   accessible by name in the ``cocopp`` post-processing and from the python
   ``cocopp.archives`` module.



.. Accepted Papers
  ---------------
  Out of nice submissions, the following seven papers have been accepted after peer-review:




.. Schedule
  --------------------
  This year, the BBOB-2021 workshop got assigned the very first two sessions at GECCO (on July 13, 2019) 
  in which the talks are scheduled according
  to the table below. 
  The room is called "Club A".
  Speakers are highlighted with a star behind the name. 
  Please click on the provided links to download the slides if available.

  .. tabularcolumns:: |l|p{5cm}|

  +---------------+-------------------------------------------------------------------------------------------------------------------+
  | **BBOB-2019 Session I**: Introduction, large-scale and multiobjective optimization                                                |
  +---------------+-------------------------------------------------------------------------------------------------------------------+
  | 08:30 - 09:15 | The BBOBies: Introduction to Blackbox Optimization Benchmarking                                                   |
  |               | (`slides <https://numbbo.github.io/gforge/presentation-archive/2019-GECCO/01_Dimo_bbob-2019-intro.pdf>`__)        |
  +---------------+-------------------------------------------------------------------------------------------------------------------+
  | 09:15 - 09:40 | |                                                                                                                 |
  |               | | Konstantinos Varelas*:                                                                                          |
  |               | | Benchmarking Large Scale Variants of CMA-ES and L-BFGS-B on the bbob-largescale Testbed                         |
  +---------------+-------------------------------------------------------------------------------------------------------------------+
  | 09:40 - 10:05 | | Paul Dufossé* and Cheikh Touré:                                                                                 |
  |               | | Benchmarking MO-CMA-ES and COMO-CMA-ES on the Bi-objective bbob-biobj Testbed                                   |
  +---------------+-------------------------------------------------------------------------------------------------------------------+
  | 10:05 – 10:20 | | Dimo Brockhoff* and Tea Tušar:                                                                                  |
  |               | | Benchmarking Algorithms from the platypus Framework on the Biobjective bbob-biobj Testbed                       |
  |               | | (`slides <https://numbbo.github.io/gforge/presentation-archive/2019-GECCO/04_Dimo_playtpus.pdf>`__)             |
  +---------------+-------------------------------------------------------------------------------------------------------------------+



  +---------------+-----------------------------------------------------------------------------------------------------------------------+
  | **BBOB-2019 Session II**: noiseless, unconstrained optimization                                                                       |
  +---------------+-----------------------------------------------------------------------------------------------------------------------+
  | 10:40 - 10:45 | The BBOBies: Introduction to Blackbox Optimization Benchmarking                                                       |
  |               | (`slides <https://numbbo.github.io/gforge/presentation-archive/2019-GECCO/05_Dimo_bbob-2019-miniintroAndRS.pdf>`__)   |
  +---------------+-----------------------------------------------------------------------------------------------------------------------+
  | 10:45 - 10:55 | | Dimo Brockhoff* and Nikolaus Hansen:                                                                                |
  |               | | The Impact of Sample Volume in Random Search on the bbob Test Suite                                                 |
  |               | | (`slides <https://numbbo.github.io/gforge/presentation-archive/2019-GECCO/05_Dimo_bbob-2019-miniintroAndRS.pdf>`__) |
  +---------------+-----------------------------------------------------------------------------------------------------------------------+
  | 10:55 - 11:20 | | Benjamin Bodner*:                                                                                                   |
  |               | | Benchmarking the ATM Algorithm on the BBOB 2009 Noiseless Function Testbed                                          |                           
  |               | | (`slides <https://numbbo.github.io/gforge/presentation-archive/2019-GECCO/07_Bodner_ATM.pdf>`__)                    |
  +---------------+-----------------------------------------------------------------------------------------------------------------------+
  | 11:20 – 11:45 | | Louis Faury*, Clément Calauzènes, and Olivier Fercoq:                                                               |
  |               | | Benchmarking GNN-CMA-ES on the BBOB noiseless testbed                                                               |
  +---------------+-----------------------------------------------------------------------------------------------------------------------+
  | 11:45 - 12:10 | | Konstantinos Varelas and Marie-Ange Dahito*:                                                                        |
  |               | | Benchmarking Multivariate Solvers of SciPy on the Noiseless Testbed                                                 |
  +---------------+-----------------------------------------------------------------------------------------------------------------------+
  | 12:10 - 12:20 | | Nikolaus Hansen*:                                                                                                   |
  |               | | The COCO data archive and This Year's Results                                                                       |
  +---------------+-----------------------------------------------------------------------------------------------------------------------+
  | 12:20 - 12:30 | The BBOBies: Wrap-up and Open Discussion                                                                              |
  +---------------+-----------------------------------------------------------------------------------------------------------------------+

   

..
  Links to Algorithm Data
  -----------------------
  The data of all submitted experiments can be found in the
  `list of data sets <https://numbbo.github.io/data-archive/>`_.

   


Supporting material
-------------------
The basis of the workshop is the Comparing Continuous Optimizer platform
(https://github.com/numbbo/coco), written in ANSI C with
other languages calling the C code. Languages currently available are
C, Java, MATLAB/Octave, and Python.

Most likely, you want to read the `COCO quick start <https://github.com/numbbo/coco>`_
(scroll down a bit). This page also provides the code for the benchmark functions [1]_, for running the
experiments in C, Java, Matlab, Octave, and Python, and for postprocessing the experiment data
into plots, tables, html pages, and publisher-conform PDFs via provided LaTeX templates.
Please refer to http://numbbo.github.io/coco-doc/experimental-setup/
for more details on the general experimental set-up for black-box optimization benchmarking.

The latest (hopefully) stable release of the COCO software can be downloaded as a whole
`here <https://github.com/numbbo/coco/releases/>`_. Please use at least version v2.4 for
running your benchmarking experiments in 2021.

Documentation of the functions used in the different test suites can be found here:

* ``bbob`` suite at https://numbbo.github.io/gforge/downloads/download16.00/bbobdocfunctions.pdf
* ``bbob-noisy`` suite at http://coco.lri.fr/downloads/download15.03/bbobdocnoisyfunctions.pdf
* ``bbob-biobj`` suite at http://numbbo.github.io/coco-doc/bbob-biobj/functions/
* ``bbob-largescale`` suite at http://numbbo.github.io/coco-doc/bbob-largescale/functions/
* ``bbob-mixint`` and ``bbob-biobj-mixint`` suites at https://hal.inria.fr/hal-02067932/document and at https://numbbo.github.io/gforge/preliminary-bbob-mixint-documentation/bbob-mixint-doc.pdf



.. [1] Note that the current release of the new COCO platform does not contain the 
   original noisy BBOB testbed yet, such that you must use the old code at 
   https://numbbo.github.io/coco/oldcode/bboball15.03.tar.gz for the time
   being if you want to compare your algorithm on the noisy testbed.







Important Dates
----------------

* **2020-12-15** release 2.4 of the COCO platform `<https://github.com/numbbo/coco/releases/>`_ 
* **2021-02-11** paper submission system opens
* **2021-04-12** *paper and data submission deadline*
* **2021-04-26** decision notification
* **2021-05-03** deadline camera-ready papers
* **2021-05-03** deadline author registration
* **2021-07-10** or **2021-07-11** workshop

All dates are given in ISO 8601 format (yyyy-mm-dd).


Organizers
----------
* Anne Auger, Inria and CMAP, Ecole Polytechnique, Institut Polytechnique de Paris, France
* Peter A. N. Bosman,  Centrum Wiskunde & Informatica (CWI) and TU Delft, The Netherlands
* Dimo Brockhoff, Inria and CMAP, Ecole Polytechnique, Institut Polytechnique de Paris, France
* Tobias Glasmachers, Ruhr-Universität Bochum, Germany
* Nikolaus Hansen, Inria and CMAP, Ecole Polytechnique, Institut Polytechnique de Paris, France
* Petr Pošík, Czech Technical University, Czech Republic
* Tea Tušar, Jozef Stefan Institute (JSI), Slovenia