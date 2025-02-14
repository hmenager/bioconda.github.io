:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-probatch'
.. highlight: bash

bioconductor-probatch
=====================

.. conda:recipe:: bioconductor-probatch
   :replaces_section_title:

   The proBatch package facilitates batch effects analysis and correction in high\-thoughput experiments. It was developed primarily for mass\-spectrometry proteomics \(DIA\/SWATH\)\, but could also be applicable to most omic data with minor adaptations. The package contains functions for diagnostics \(proteome\/genome\-wide and feature\-level\)\, correction \(normalization and batch effects correction\) and quality control. Non\-linear fitting based approaches were also included to deal with complex\, mass spectrometry\-specific signal drifts.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/proBatch.html
   :license: GPL-3
   :recipe: /`bioconductor-probatch <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-probatch>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-probatch/meta.yaml>`_

   


.. conda:package:: bioconductor-probatch

   |downloads_bioconductor-probatch| |docker_bioconductor-probatch|

   :versions: 1.0.0-1
   
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends bioconductor-preprocesscore: >=1.46.0,<1.47.0
   :depends bioconductor-pvca: >=1.24.0,<1.25.0
   :depends bioconductor-sva: >=3.32.0,<3.33.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-corrplot: 
   :depends r-data.table: 
   :depends r-dplyr: 
   :depends r-ggfortify: 
   :depends r-ggplot2: 
   :depends r-lazyeval: 
   :depends r-lubridate: 
   :depends r-magrittr: 
   :depends r-pheatmap: 
   :depends r-purrr: 
   :depends r-rcolorbrewer: 
   :depends r-readr: 
   :depends r-reshape2: 
   :depends r-rlang: 
   :depends r-scales: 
   :depends r-tibble: 
   :depends r-tidyr: 
   :depends r-viridis: 
   :depends r-wesanderson: 
   :depends r-wgcna: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-probatch

   and update with::

      conda update bioconductor-probatch

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-probatch:<tag>

   (see `bioconductor-probatch/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-probatch| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-probatch.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-probatch
   :alt:   (downloads)
.. |docker_bioconductor-probatch| image:: https://quay.io/repository/biocontainers/bioconductor-probatch/status
   :target: https://quay.io/repository/biocontainers/bioconductor-probatch
.. _`bioconductor-probatch/tags`: https://quay.io/repository/biocontainers/bioconductor-probatch?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-probatch/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-probatch/README.html