:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-ngsreports'
.. highlight: bash

bioconductor-ngsreports
=======================

.. conda:recipe:: bioconductor-ngsreports
   :replaces_section_title:

   This package provides methods and object classes for parsing FastQC reports and output summaries from other NGS tools into R\, as well as visualising the data loaded from these files.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/ngsReports.html
   :license: LGPL (>= 3)
   :recipe: /`bioconductor-ngsreports <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-ngsreports>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-ngsreports/meta.yaml>`_

   


.. conda:package:: bioconductor-ngsreports

   |downloads_bioconductor-ngsreports| |docker_bioconductor-ngsreports|

   :versions: 1.0.0-1
   
   :depends bioconductor-biocgenerics: >=0.30.0,<0.31.0
   :depends bioconductor-biostrings: >=2.52.0,<2.53.0
   :depends bioconductor-rsamtools: >=2.0.0,<2.1.0
   :depends bioconductor-shortread: >=1.42.0,<1.43.0
   :depends bioconductor-xvector: >=0.24.0,<0.25.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-checkmate: 
   :depends r-dplyr: >=0.7.5
   :depends r-ggdendro: 
   :depends r-ggplot2: 
   :depends r-lubridate: 
   :depends r-plotly: 
   :depends r-readr: 
   :depends r-reshape2: 
   :depends r-rmarkdown: 
   :depends r-scales: 
   :depends r-stringr: 
   :depends r-tibble: >=1.3.1
   :depends r-tidyr: 
   :depends r-tidyselect: >=0.2.3
   :depends r-truncnorm: 
   :depends r-viridislite: 
   :depends r-zoo: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-ngsreports

   and update with::

      conda update bioconductor-ngsreports

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-ngsreports:<tag>

   (see `bioconductor-ngsreports/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-ngsreports| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-ngsreports.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-ngsreports
   :alt:   (downloads)
.. |docker_bioconductor-ngsreports| image:: https://quay.io/repository/biocontainers/bioconductor-ngsreports/status
   :target: https://quay.io/repository/biocontainers/bioconductor-ngsreports
.. _`bioconductor-ngsreports/tags`: https://quay.io/repository/biocontainers/bioconductor-ngsreports?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-ngsreports/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-ngsreports/README.html