:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-riboseqr'
.. highlight: bash

bioconductor-riboseqr
=====================

.. conda:recipe:: bioconductor-riboseqr
   :replaces_section_title:

   Plotting functions\, frameshift detection and parsing of sequencing data from ribosome profiling experiments.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/riboSeqR.html
   :license: GPL-3
   :recipe: /`bioconductor-riboseqr <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-riboseqr>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-riboseqr/meta.yaml>`_
   :links: biotools: :biotools:`riboseqr`, doi: :doi:`10.1080/15476286.2016.1141862`

   


.. conda:package:: bioconductor-riboseqr

   |downloads_bioconductor-riboseqr| |docker_bioconductor-riboseqr|

   :versions: 1.18.0-1, 1.16.0-0, 1.14.0-0, 1.12.0-0, 1.10.0-0
   
   :depends bioconductor-bayseq: >=2.18.0,<2.19.0
   :depends bioconductor-genomeinfodb: >=1.20.0,<1.21.0
   :depends bioconductor-genomicranges: >=1.36.0,<1.37.0
   :depends bioconductor-iranges: >=2.18.0,<2.19.0
   :depends bioconductor-rsamtools: >=2.0.0,<2.1.0
   :depends bioconductor-seqlogo: >=1.50.0,<1.51.0
   :depends r-abind: 
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-riboseqr

   and update with::

      conda update bioconductor-riboseqr

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-riboseqr:<tag>

   (see `bioconductor-riboseqr/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-riboseqr| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-riboseqr.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-riboseqr
   :alt:   (downloads)
.. |docker_bioconductor-riboseqr| image:: https://quay.io/repository/biocontainers/bioconductor-riboseqr/status
   :target: https://quay.io/repository/biocontainers/bioconductor-riboseqr
.. _`bioconductor-riboseqr/tags`: https://quay.io/repository/biocontainers/bioconductor-riboseqr?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-riboseqr/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-riboseqr/README.html