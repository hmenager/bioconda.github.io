:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-chromstar'
.. highlight: bash

bioconductor-chromstar
======================

.. conda:recipe:: bioconductor-chromstar
   :replaces_section_title:

   This package implements functions for combinatorial and differential analysis of ChIP\-seq data. It includes uni\- and multivariate peak\-calling\, export to genome browser viewable files\, and functions for enrichment analyses.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/chromstaR.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-chromstar <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-chromstar>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-chromstar/meta.yaml>`_
   :links: biotools: :biotools:`chromstar`, doi: :doi:`10.1101/038612`

   


.. conda:package:: bioconductor-chromstar

   |downloads_bioconductor-chromstar| |docker_bioconductor-chromstar|

   :versions: 1.10.0-1, 1.8.1-0, 1.8.0-0, 1.6.2-0, 1.4.0-0
   
   :depends bioconductor-bamsignals: >=1.16.0,<1.17.0
   :depends bioconductor-chromstardata: >=1.10.0,<1.11.0
   :depends bioconductor-genomeinfodb: >=1.20.0,<1.21.0
   :depends bioconductor-genomicalignments: >=1.20.0,<1.21.0
   :depends bioconductor-genomicranges: >=1.36.0,<1.37.0
   :depends bioconductor-iranges: >=2.18.0,<2.19.0
   :depends bioconductor-rsamtools: >=2.0.0,<2.1.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends libgcc-ng: >=7.3.0
   :depends libstdcxx-ng: >=7.3.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-doparallel: 
   :depends r-foreach: 
   :depends r-ggplot2: 
   :depends r-mvtnorm: 
   :depends r-reshape2: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-chromstar

   and update with::

      conda update bioconductor-chromstar

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-chromstar:<tag>

   (see `bioconductor-chromstar/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-chromstar| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-chromstar.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-chromstar
   :alt:   (downloads)
.. |docker_bioconductor-chromstar| image:: https://quay.io/repository/biocontainers/bioconductor-chromstar/status
   :target: https://quay.io/repository/biocontainers/bioconductor-chromstar
.. _`bioconductor-chromstar/tags`: https://quay.io/repository/biocontainers/bioconductor-chromstar?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-chromstar/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-chromstar/README.html