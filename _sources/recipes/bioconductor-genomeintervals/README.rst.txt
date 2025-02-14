:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-genomeintervals'
.. highlight: bash

bioconductor-genomeintervals
============================

.. conda:recipe:: bioconductor-genomeintervals
   :replaces_section_title:

   This package defines classes for representing genomic intervals and provides functions and methods for working with these. Note\: The package provides the basic infrastructure for and is enhanced by the package \'girafe\'.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/genomeIntervals.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-genomeintervals <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-genomeintervals>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-genomeintervals/meta.yaml>`_
   :links: biotools: :biotools:`genomeintervals`, doi: :doi:`10.1038/nmeth.3252`

   


.. conda:package:: bioconductor-genomeintervals

   |downloads_bioconductor-genomeintervals| |docker_bioconductor-genomeintervals|

   :versions: 1.40.0-1, 1.38.0-0, 1.36.0-0, 1.34.0-0
   
   :depends bioconductor-biocgenerics: >=0.30.0,<0.31.0
   :depends bioconductor-genomeinfodb: >=1.20.0,<1.21.0
   :depends bioconductor-genomicranges: >=1.36.0,<1.37.0
   :depends bioconductor-iranges: >=2.18.0,<2.19.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-intervals: >=0.14.0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-genomeintervals

   and update with::

      conda update bioconductor-genomeintervals

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-genomeintervals:<tag>

   (see `bioconductor-genomeintervals/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-genomeintervals| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-genomeintervals.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-genomeintervals
   :alt:   (downloads)
.. |docker_bioconductor-genomeintervals| image:: https://quay.io/repository/biocontainers/bioconductor-genomeintervals/status
   :target: https://quay.io/repository/biocontainers/bioconductor-genomeintervals
.. _`bioconductor-genomeintervals/tags`: https://quay.io/repository/biocontainers/bioconductor-genomeintervals?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-genomeintervals/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-genomeintervals/README.html