:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-riboprofiling'
.. highlight: bash

bioconductor-riboprofiling
==========================

.. conda:recipe:: bioconductor-riboprofiling
   :replaces_section_title:

   Starting with a BAM file\, this package provides the necessary functions for quality assessment\, read start position recalibration\, the counting of reads on CDS\, 3\'UTR\, and 5\'UTR\, plotting of count data\: pairs\, log fold\-change\, codon frequency and coverage assessment\, principal component analysis on codon coverage.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/RiboProfiling.html
   :license: GPL-3
   :recipe: /`bioconductor-riboprofiling <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-riboprofiling>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-riboprofiling/meta.yaml>`_
   :links: biotools: :biotools:`riboprofiling`, doi: :doi:`10.12688/f1000research.8964.1`

   


.. conda:package:: bioconductor-riboprofiling

   |downloads_bioconductor-riboprofiling| |docker_bioconductor-riboprofiling|

   :versions: 1.14.0-1, 1.12.0-1, 1.12.0-0, 1.10.0-0, 1.7.1-0, 1.6.0-0
   
   :depends bioconductor-biocgenerics: >=0.30.0,<0.31.0
   :depends bioconductor-biostrings: >=2.52.0,<2.53.0
   :depends bioconductor-genomeinfodb: >=1.20.0,<1.21.0
   :depends bioconductor-genomicalignments: >=1.20.0,<1.21.0
   :depends bioconductor-genomicfeatures: >=1.36.0,<1.37.0
   :depends bioconductor-genomicranges: >=1.36.0,<1.37.0
   :depends bioconductor-ggbio: >=1.32.0,<1.33.0
   :depends bioconductor-iranges: >=2.18.0,<2.19.0
   :depends bioconductor-rsamtools: >=2.0.0,<2.1.0
   :depends bioconductor-rtracklayer: >=1.44.0,<1.45.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-data.table: 
   :depends r-ggplot2: 
   :depends r-plyr: 
   :depends r-reshape2: 
   :depends r-sqldf: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-riboprofiling

   and update with::

      conda update bioconductor-riboprofiling

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-riboprofiling:<tag>

   (see `bioconductor-riboprofiling/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-riboprofiling| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-riboprofiling.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-riboprofiling
   :alt:   (downloads)
.. |docker_bioconductor-riboprofiling| image:: https://quay.io/repository/biocontainers/bioconductor-riboprofiling/status
   :target: https://quay.io/repository/biocontainers/bioconductor-riboprofiling
.. _`bioconductor-riboprofiling/tags`: https://quay.io/repository/biocontainers/bioconductor-riboprofiling?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-riboprofiling/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-riboprofiling/README.html