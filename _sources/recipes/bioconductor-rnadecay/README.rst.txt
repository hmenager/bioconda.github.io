:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-rnadecay'
.. highlight: bash

bioconductor-rnadecay
=====================

.. conda:recipe:: bioconductor-rnadecay
   :replaces_section_title:

   RNA degradation is monitored through measurement of RNA abundance after inhibiting RNA synthesis. This package has functions and example scripts to facilitate \(1\) data normalization\, \(2\) data modeling using constant decay rate or time\-dependent decay rate models\, \(3\) the evaluation of treatment or genotype effects\, and \(4\) plotting of the data and models. Data Normalization\: functions and scripts make easy the normalization to the initial \(T0\) RNA abundance\, as well as a method to correct for artificial inflation of Reads per Million \(RPM\) abundance in global assessments as the total size of the RNA pool decreases. Modeling\: Normalized data is then modeled using maximum likelihood to fit parameters. For making treatment or genotype comparisons \(up to four\)\, the modeling step models all possible treatment effects on each gene by repeating the modeling with constraints on the model parameters \(i.e.\, the decay rate of treatments A and B are modeled once with them being equal and again allowing them to both vary independently\). Model Selection\: The AICc value is calculated for each model\, and the model with the lowest AICc is chosen. Modeling results of selected models are then compiled into a single data frame. Graphical Plotting\: a function is provided to easily visualize the data and the selected model using ggplot2 package functions.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/RNAdecay.html
   :license: GPL-2
   :recipe: /`bioconductor-rnadecay <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-rnadecay>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-rnadecay/meta.yaml>`_

   


.. conda:package:: bioconductor-rnadecay

   |downloads_bioconductor-rnadecay| |docker_bioconductor-rnadecay|

   :versions: 1.4.0-1, 1.4.0-0, 1.2.1-0, 1.2.0-0
   
   :depends libgcc-ng: >=7.3.0
   :depends libstdcxx-ng: >=7.3.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-ggplot2: 
   :depends r-gplots: 
   :depends r-nloptr: 
   :depends r-tmb: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-rnadecay

   and update with::

      conda update bioconductor-rnadecay

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-rnadecay:<tag>

   (see `bioconductor-rnadecay/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-rnadecay| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-rnadecay.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-rnadecay
   :alt:   (downloads)
.. |docker_bioconductor-rnadecay| image:: https://quay.io/repository/biocontainers/bioconductor-rnadecay/status
   :target: https://quay.io/repository/biocontainers/bioconductor-rnadecay
.. _`bioconductor-rnadecay/tags`: https://quay.io/repository/biocontainers/bioconductor-rnadecay?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-rnadecay/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-rnadecay/README.html