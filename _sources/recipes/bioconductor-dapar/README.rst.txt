:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-dapar'
.. highlight: bash

bioconductor-dapar
==================

.. conda:recipe:: bioconductor-dapar
   :replaces_section_title:

   This package contains a collection of functions for the visualisation and the statistical analysis of proteomic data.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/DAPAR.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-dapar <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-dapar>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-dapar/meta.yaml>`_

   


.. conda:package:: bioconductor-dapar

   |downloads_bioconductor-dapar| |docker_bioconductor-dapar|

   :versions: 1.16.7-0, 1.14.4-0
   
   :depends bioconductor-annotationdbi: >=1.46.0,<1.47.0
   :depends bioconductor-clusterprofiler: >=3.12.0,<3.13.0
   :depends bioconductor-dapardata: >=1.14.0,<1.15.0
   :depends bioconductor-graph: >=1.62.0,<1.63.0
   :depends bioconductor-impute: >=1.58.0,<1.59.0
   :depends bioconductor-limma: >=3.40.0,<3.41.0
   :depends bioconductor-msnbase: >=2.10.0,<2.11.0
   :depends bioconductor-pcamethods: >=1.76.0,<1.77.0
   :depends bioconductor-preprocesscore: >=1.46.0,<1.47.0
   :depends bioconductor-siggenes: >=1.58.0,<1.59.0
   :depends bioconductor-vsn: >=3.52.0,<3.53.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-cairo: 
   :depends r-cp4p: >=0.3.5
   :depends r-doparallel: 
   :depends r-dplyr: 
   :depends r-factoextra: 
   :depends r-factominer: 
   :depends r-foreach: 
   :depends r-ggplot2: 
   :depends r-gplots: 
   :depends r-highcharter: >=0.5.0
   :depends r-imp4p: >=0.7
   :depends r-knitr: 
   :depends r-lattice: 
   :depends r-lme4: 
   :depends r-matrix: 
   :depends r-norm: 
   :depends r-openxlsx: 
   :depends r-png: 
   :depends r-rcolorbrewer: 
   :depends r-readxl: 
   :depends r-reshape2: 
   :depends r-scales: 
   :depends r-stringr: 
   :depends r-tidyr: 
   :depends r-tidyverse: 
   :depends r-tmvtnorm: 
   :depends r-vioplot: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-dapar

   and update with::

      conda update bioconductor-dapar

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-dapar:<tag>

   (see `bioconductor-dapar/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-dapar| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-dapar.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-dapar
   :alt:   (downloads)
.. |docker_bioconductor-dapar| image:: https://quay.io/repository/biocontainers/bioconductor-dapar/status
   :target: https://quay.io/repository/biocontainers/bioconductor-dapar
.. _`bioconductor-dapar/tags`: https://quay.io/repository/biocontainers/bioconductor-dapar?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-dapar/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-dapar/README.html