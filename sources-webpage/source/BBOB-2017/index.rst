.. _bbob2017page:

GECCO Workshop on Real-Parameter Black-Box Optimization Benchmarking (BBOB 2017)
================================================================================


Welcome to the web page of the 7th GECCO Workshop on Real-Parameter Black-Box Optimization Benchmarking (BBOB 2017)
with a continued focus on bi-objective problems and which took place during GECCO 2017.

    **WORKSHOP ON REAL-PARAMETER BLACK-BOX OPTIMIZATION BENCHMARKING (BBOB 2017)**

    | held as part of the
    |
    | **2017 Genetic and Evolutionary Computation Conference (GECCO-2017)**
    | July 15--19, Berlin, Germany
    | http://gecco-2017.sigevo.org


| Submission Deadline: extended to Tuesday, April 11, 2017 (from Friday, March 31, 2017)
|


=======================================================  ========================================================================  =======================================================================================
`register for news <http://numbbo.github.io/register>`_  `Coco quick start (scroll down a bit) <https://github.com/numbbo/coco>`_  `latest Coco release <https://github.com/numbbo/coco/releases/>`_
=======================================================  ========================================================================  =======================================================================================


Quantifying and comparing the performance of optimization algorithms
is a difficult and tedious task to achieve. The Coco
platform provides tools to ease this process for *single-objective*
noiseless and noisy problems and for *bi-objective* noiseless
problems by: (1) an implemented, well-motivated benchmark function
testbed, (2) a simple and sound experimental set-up, (3) the 
generation of output data and (4) the post-processing and presentation
of the results in graphs and tables.


.. In 2017, we provide a new extension of the 2016 bi-objective test
   suite to 92 problems overall---addressing certain issues raised at
   last year's BBOB workshop---and continue to support all previously
   known ones. 
   
Overall, we provide the following test suites:

* ``bbob`` containing 24 noiseless functions,
* ``bbob-noisy`` containing 30 noisy functions [^1],
* ``bbob-biobj`` containing 55 noiseless, bi-objective functions, and

.. * ``bbob-biobj-ext`` containing 92 noiseless, bi-objective functions
   * ``bbob-largescale`` containing 24 noiseless functions in dimension 20 to 640.

Note that the previously announced extended version of the ``bbob-biobj``
test suite has unfortunately not been fully supported early enough in 2017
but that we will make it available later on this summer.
   
The tasks for participants are as usual: run your favorite
single- or multiobjective black-box optimizer (old or new) by using the wrappers
provided (in C/C++, Python, Java, and Matlab/Octave) and run the
post-processing procedure (provided as well) that
will generate automatically all the material for a workshop paper
(ACM compliant LaTeX templates available). A description of the algorithm and the
discussion of the results completes the paper writing.

We encourage particularly submissions 
on *algorithms from outside the evolutionary computation community*. 
Please note that any other submission, related to black-box
optimization benchmarking of continuous optimizers will be welcome
as well. The submission section below gives a few examples of 
subjects of interest.

.. Submissions related to
   the previously available ``bbob``, ``bbob-noisy``, and ``bbob-biobj`` testbeds
   are more than welcome.


During the workshop, algorithms, results, and discussions will be presented by
the participants. An overall analysis and comparison of all submitted
algorithm data is going to be accomplished by the organizers and the overall 
process will be critically reviewed.

.. A plenary discussion on future improvements will,
   among others, address the question, of how the testbeds should evolve.


Updates and News
----------------
Get updated about the latest news regarding the workshop and
releases and bugfixes of the supporting NumBBO/Coco platform, by
registering at http://numbbo.github.io/register.


Supporting material
-------------------
Basis of the workshop is the Comparing Continuous Optimizer platform
(https://github.com/numbbo/coco), now rewritten fully in ANSI C with
other languages calling the C code. Languages currently available are
C, Java, MATLAB/Octave, and Python.

Most likely, you want to read the `Coco quick start <https://github.com/numbbo/coco>`_
(scroll down a bit). This page also provides the code for the benchmark functions, for running the
experiments in C, Java, Matlab, Octave, and Python, and for postprocessing the experiment data
into plots, tables, html pages, and publisher-conform PDFs via provided LaTeX templates.
Please refer to http://numbbo.github.io/coco-doc/experimental-setup/
for more details on the general experimental set-up for black-box optimization benchmarking.

The latest (hopefully) stable release of the Coco software can be downloaded as a whole
`here <https://github.com/numbbo/coco/releases/>`_. Please use at least version v2.0 for
running your benchmarking experiments in 2017.

Documentation of the functions used in the ``bbob-biobj`` and ``bbob-biobj-ext`` suites 
are provided at http://numbbo.github.io/coco-doc/bbob-biobj/functions/ .

[^1] Note that the current release of the new Coco platform does not contain the 
original noisy BBOB testbed yet, such that you must use the old code at 
https://numbbo.github.io/coco/oldcode/bboball15.03.tar.gz for the time
being if you want to compare your algorithm on the noisy testbed.



Submissions
-----------
We encourage any submission that is concerned with black-box optimization 
benchmarking of continuous optimizers, for example papers that:

* describe and benchmark new or not-so-new algorithms on one of the
  above testbeds,
* compare new or existing algorithms from the COCO/BBOB database[^2], 
* analyze the data obtained in previous editions of BBOB[^2], or
* discuss, compare, and improve upon any benchmarking methodology
  for continuous optimizers such as design of experiments,
  performance measures, presentation methods, benchmarking frameworks,
  test functions, ...

    
Submissions are expected to be done through the submission form at:
http://numbbo.github.io/submit.

To upload your data, you might want to use https://zenodo.org/ which 
offers uploads of data sets up to 50GB in size or any other provider
of online data storage.
Please let us know briefly in the mandatory ``Data`` field, why you do
not provide any data in case you submit a paper unrelated to the above
BBOB test suites.


[^2] The data of previously compared algorithms can be found at 
https://numbbo.github.io/data-archive/bbob-biobj/ for the
``bbob-biobj`` test suite and at https://numbbo.github.io/data-archive/bbob/
and https://numbbo.github.io/data-archive/bbob-noisy/
for the ``bbob`` and ``bbob-noisy`` test suites respectively.


Accepted Papers
---------------
- Mario García-Valdez and Juan-J. Merelo: **Benchmarking a Pool-Based Execution with GA and PSO Workers on the BBOB Noiseless Testbed**
- Duc Manh Nguyen and Nikolaus Hansen: **Benchmarking CMAES-APOP on the BBOB Noiseless Testbed**
- Takahiro Yamaguchi and Youhei Akimoto: **Benchmarking the Novel CMA-ES Restart Strategy Using the Search History on the BBOB Noiseless Testbed**
- Simon Wessing: **Benchmarking the SMS-EMOA with Self-adaptation on the bbob-biobj Test Suite**
- Zbynek Pitra, Lukas Bajer, Jakub Repicky, and Martin Holena: **Comparison of Ordinal and Metric Gaussian Process Regression as Surrogate Models for CMA Evolution Strategy**
- Dogan Aydin and Gurcan Yavuz: **Self-adaptive Search Equation-Based Artificial Bee Colony Algorithm with CMA-ES on the Noiseless BBOB Testbed**


Links to Algorithm Data
-----------------------
The data of Simon's self-adaptive SMS-EMOA can be found in the
`list of biobjective data sets <https://numbbo.github.io/data-archive/bbob-biobj>`_
and all other single-objective data sets at the 
`list of bbob data sets <https://numbbo.github.io/data-archive/bbob/>`_.


Schedule
--------------------
Both BBOB-2017 sessions took place on the second day of GECCO (Sunday July 16, 2017) in the Amethyst room. 
Speakers are highlighted with a star behind the name if known. Please click on the provided links to download the slides.

.. tabularcolumns:: |l|p{5cm}|

+---------------+-----------------------------------------------------------------------------------------------------------------------+
| **Session I**                                                                                                                         |
+---------------+-----------------------------------------------------------------------------------------------------------------------+
| 08:30 - 09:05 | The BBOBies: Introduction to Blackbox Optimization Benchmarking                                                       |
|               |                                                                                                                       |
+---------------+-----------------------------------------------------------------------------------------------------------------------+
| 09:05 - 09:30 | Simon Wessing*:                                                                                                       |
|               | Benchmarking the SMS-EMOA with Self-adaptation on the bbob-biobj Test Suite                                           |
|               | (`slides <https://numbbo.github.io/gforge/presentation-archive/2017-GECCO/02-Wessing-SMS-EMOA-SA.pdf>`__)             |
+---------------+-----------------------------------------------------------------------------------------------------------------------+
| 09:30 - 09:55 | Mario García-Valdez* and Juan-J. Merelo:                                                                              |
|               | Benchmarking a Pool-Based Execution with GA and PSO Workers on the BBOB Noiseless Testbed                             |
+---------------+-----------------------------------------------------------------------------------------------------------------------+
| 09:55 - 10:20 | Zbynek Pitra*, Lukas Bajer, Jakub Repicky, and Martin Holena:                                                         |
|               | Comparison of Ordinal and Metric Gaussian Process Regression as Surrogate Models for CMA Evolution Strategy           |
|               | (`slides <https://numbbo.github.io/gforge/presentation-archive/2017-GECCO/04-Pitra-DTS-CMA.pdf>`__)                   |
+---------------+-----------------------------------------------------------------------------------------------------------------------+
| **Session II**                                                                                                                        |
+---------------+-----------------------------------------------------------------------------------------------------------------------+
| 10:40 - 10:50 | The BBOBies: Session Introduction                                                                                     |
+---------------+-----------------------------------------------------------------------------------------------------------------------+
| 10:50 - 11:15 | Dogan Aydin* and Gurcan Yavuz:                                                                                        |
|               | Self-adaptive Search Equation-Based Artificial Bee Colony Algorithm with CMA-ES on the Noiseless BBOB Testbed         |
|               | (`slides <https://numbbo.github.io/gforge/presentation-archive/2017-GECCO/06-Aydin-SSEABC.pdf>`__)                    |
+---------------+-----------------------------------------------------------------------------------------------------------------------+
| 11:15 - 11:40 | Duc Manh Nguyen and Nikolaus Hansen*:                                                                                 |
|               | Benchmarking CMAES-APOP on the BBOB Noiseless Testbed                                                                 |
+---------------+-----------------------------------------------------------------------------------------------------------------------+
| 11:40 - 12:05 | Takahiro Yamaguchi and Youhei Akimoto*:                                                                               |
|               | Benchmarking the Novel CMA-ES Restart Strategy Using the Search History on the BBOB Noiseless Testbed                 |
|               | (`slides <https://numbbo.github.io/gforge/presentation-archive/2017-GECCO/08-Akimoto-KL-CMA.pdf>`__)                  |
+---------------+-----------------------------------------------------------------------------------------------------------------------+
| 12:05 - 12:30 | The BBOBies: Wrap-up and Open Discussion                                                                              |
+---------------+-----------------------------------------------------------------------------------------------------------------------+

.. |               | (`slides <https://numbbo.github.io/gforge/presentation-archive/2016-GECCO/05_Cheryl_MO-DIRECT.pdf>`__)                |


Important Dates
---------------

* **01/28/2017** release 2.0 of the Coco platform for first tests: `<https://github.com/numbbo/coco/releases/>`_
* **03/07/2017** expected release of the Coco software with the final functionality to run experiments
* **04/11/2017** *paper and data submission deadline* (extended from 03/31/2017)
* **04/17/2017** decision notification
* **04/27/2017** deadline camera-ready papers (extended from 04/24/2017)
* **07/16/2017** workshop


Organizers
----------
* Anne Auger, Inria Saclay - Ile-de-France, France
* Dimo Brockhoff, Inria Saclay - Ile-de-France, France
* Nikolaus Hansen, Inria Saclay - Ile-de-France, France
* Dejan Tušar, Inria Saclay - Ile-de-France, France
* Tea Tušar, Jozef Stefan Institute, Ljublana, Slovenia
