:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-migsa'
.. highlight: bash

bioconductor-migsa
==================

.. conda:recipe:: bioconductor-migsa
   :replaces_section_title:

   Massive and Integrative Gene Set Analysis. The MIGSA package allows to perform a massive and integrative gene set analysis over several expression and gene sets simultaneously. It provides a common gene expression analytic framework that grants a comprehensive and coherent analysis. Only a minimal user parameter setting is required to perform both singular and gene set enrichment analyses in an integrative manner by means of the best available methods\, i.e. dEnricher and mGSZ respectively. The greatest strengths of this big omics data tool are the availability of several functions to explore\, analyze and visualize its results in order to facilitate the data mining task over huge information sources. MIGSA package also provides several functions that allow to easily load the most updated gene sets from several repositories.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/MIGSA.html
   :license: GPL (>= 2)
   :recipe: /`bioconductor-migsa <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-migsa>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-migsa/meta.yaml>`_

   


.. conda:package:: bioconductor-migsa

   |downloads_bioconductor-migsa| |docker_bioconductor-migsa|

   :versions: 1.8.1-0, 1.6.0-0
   
   :depends bioconductor-annotationdbi: >=1.46.0,<1.47.0
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends bioconductor-biocgenerics: >=0.30.0,<0.31.0
   :depends bioconductor-biocparallel: >=1.18.0,<1.19.0
   :depends bioconductor-edger: >=3.26.0,<3.27.0
   :depends bioconductor-go.db: >=3.8.0,<3.9.0
   :depends bioconductor-gostats: >=2.50.0,<2.51.0
   :depends bioconductor-graph: >=1.62.0,<1.63.0
   :depends bioconductor-gseabase: >=1.46.0,<1.47.0
   :depends bioconductor-limma: >=3.40.0,<3.41.0
   :depends bioconductor-org.hs.eg.db: >=3.8.0,<3.9.0
   :depends bioconductor-rbgl: >=1.60.0,<1.61.0
   :depends bioconductor-rgraphviz: >=2.28.0,<2.29.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-data.table: 
   :depends r-futile.logger: 
   :depends r-ggdendro: 
   :depends r-ggplot2: 
   :depends r-ismev: 
   :depends r-matrixstats: 
   :depends r-reshape2: 
   :depends r-rjsonio: 
   :depends r-vegan: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-migsa

   and update with::

      conda update bioconductor-migsa

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-migsa:<tag>

   (see `bioconductor-migsa/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-migsa| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-migsa.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-migsa
   :alt:   (downloads)
.. |docker_bioconductor-migsa| image:: https://quay.io/repository/biocontainers/bioconductor-migsa/status
   :target: https://quay.io/repository/biocontainers/bioconductor-migsa
.. _`bioconductor-migsa/tags`: https://quay.io/repository/biocontainers/bioconductor-migsa?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-migsa/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-migsa/README.html