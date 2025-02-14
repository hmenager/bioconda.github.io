:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-generegionscan'
.. highlight: bash

bioconductor-generegionscan
===========================

.. conda:recipe:: bioconductor-generegionscan
   :replaces_section_title:

   A package with focus on analysis of discrete regions of the genome. This package is useful for investigation of one or a few genes using Affymetrix data\, since it will extract probe level data using the Affymetrix Power Tools application and wrap these data into a ProbeLevelSet. A ProbeLevelSet directly extends the expressionSet\, but includes additional information about the sequence of each probe and the probe set it is derived from. The package includes a number of functions used for plotting these probe level data as a function of location along sequences of mRNA\-strands. This can be used for analysis of variable splicing\, and is especially well suited for use with exon\-array data.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/GeneRegionScan.html
   :license: GPL (>= 2)
   :recipe: /`bioconductor-generegionscan <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-generegionscan>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-generegionscan/meta.yaml>`_
   :links: biotools: :biotools:`generegionscan`

   


.. conda:package:: bioconductor-generegionscan

   |downloads_bioconductor-generegionscan| |docker_bioconductor-generegionscan|

   :versions: 1.40.0-1, 1.38.0-0, 1.36.0-0, 1.34.0-0
   
   :depends bioconductor-affxparser: >=1.56.0,<1.57.0
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends bioconductor-biostrings: >=2.52.0,<2.53.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-rcolorbrewer: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-generegionscan

   and update with::

      conda update bioconductor-generegionscan

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-generegionscan:<tag>

   (see `bioconductor-generegionscan/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-generegionscan| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-generegionscan.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-generegionscan
   :alt:   (downloads)
.. |docker_bioconductor-generegionscan| image:: https://quay.io/repository/biocontainers/bioconductor-generegionscan/status
   :target: https://quay.io/repository/biocontainers/bioconductor-generegionscan
.. _`bioconductor-generegionscan/tags`: https://quay.io/repository/biocontainers/bioconductor-generegionscan?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-generegionscan/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-generegionscan/README.html