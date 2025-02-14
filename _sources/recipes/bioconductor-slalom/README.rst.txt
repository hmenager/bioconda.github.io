:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-slalom'
.. highlight: bash

bioconductor-slalom
===================

.. conda:recipe:: bioconductor-slalom
   :replaces_section_title:

   slalom is a scalable modelling framework for single\-cell RNA\-seq data that uses gene set annotations to dissect single\-cell transcriptome heterogeneity\, thereby allowing to identify biological drivers of cell\-to\-cell variability and model confounding factors.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/slalom.html
   :license: GPL-2
   :recipe: /`bioconductor-slalom <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-slalom>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-slalom/meta.yaml>`_

   


.. conda:package:: bioconductor-slalom

   |downloads_bioconductor-slalom| |docker_bioconductor-slalom|

   :versions: 1.6.0-1, 1.4.1-0, 1.4.0-0
   
   :depends bioconductor-gseabase: >=1.46.0,<1.47.0
   :depends bioconductor-singlecellexperiment: >=1.6.0,<1.7.0
   :depends bioconductor-summarizedexperiment: >=1.14.0,<1.15.0
   :depends libgcc-ng: >=7.3.0
   :depends libstdcxx-ng: >=7.3.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-bh: 
   :depends r-ggplot2: 
   :depends r-rcpp: >=0.12.8
   :depends r-rcpparmadillo: 
   :depends r-rsvd: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-slalom

   and update with::

      conda update bioconductor-slalom

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-slalom:<tag>

   (see `bioconductor-slalom/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-slalom| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-slalom.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-slalom
   :alt:   (downloads)
.. |docker_bioconductor-slalom| image:: https://quay.io/repository/biocontainers/bioconductor-slalom/status
   :target: https://quay.io/repository/biocontainers/bioconductor-slalom
.. _`bioconductor-slalom/tags`: https://quay.io/repository/biocontainers/bioconductor-slalom?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-slalom/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-slalom/README.html