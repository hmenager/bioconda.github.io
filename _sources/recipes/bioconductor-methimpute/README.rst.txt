:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-methimpute'
.. highlight: bash

bioconductor-methimpute
=======================

.. conda:recipe:: bioconductor-methimpute
   :replaces_section_title:

   This package implements functions for calling methylation for all cytosines in the genome.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/methimpute.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-methimpute <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-methimpute>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-methimpute/meta.yaml>`_

   


.. conda:package:: bioconductor-methimpute

   |downloads_bioconductor-methimpute| |docker_bioconductor-methimpute|

   :versions: 1.6.0-1, 1.4.1-0, 1.4.0-0
   
   :depends bioconductor-biostrings: >=2.52.0,<2.53.0
   :depends bioconductor-genomeinfodb: >=1.20.0,<1.21.0
   :depends bioconductor-genomicranges: >=1.36.0,<1.37.0
   :depends bioconductor-iranges: >=2.18.0,<2.19.0
   :depends libgcc-ng: >=7.3.0
   :depends libstdcxx-ng: >=7.3.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-data.table: 
   :depends r-ggplot2: 
   :depends r-minpack.lm: 
   :depends r-rcpp: >=0.12.4.5
   :depends r-reshape2: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-methimpute

   and update with::

      conda update bioconductor-methimpute

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-methimpute:<tag>

   (see `bioconductor-methimpute/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-methimpute| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-methimpute.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-methimpute
   :alt:   (downloads)
.. |docker_bioconductor-methimpute| image:: https://quay.io/repository/biocontainers/bioconductor-methimpute/status
   :target: https://quay.io/repository/biocontainers/bioconductor-methimpute
.. _`bioconductor-methimpute/tags`: https://quay.io/repository/biocontainers/bioconductor-methimpute?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-methimpute/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-methimpute/README.html