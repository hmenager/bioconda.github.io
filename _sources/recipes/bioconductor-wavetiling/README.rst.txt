:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-wavetiling'
.. highlight: bash

bioconductor-wavetiling
=======================

.. conda:recipe:: bioconductor-wavetiling
   :replaces_section_title:

   This package is designed to conduct transcriptome analysis for tiling arrays based on fast wavelet\-based functional models.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/waveTiling.html
   :license: GPL (>=2)
   :recipe: /`bioconductor-wavetiling <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-wavetiling>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-wavetiling/meta.yaml>`_
   :links: biotools: :biotools:`wavetiling`, doi: :doi:`10.1186/1471-2105-13-234`

   


.. conda:package:: bioconductor-wavetiling

   |downloads_bioconductor-wavetiling| |docker_bioconductor-wavetiling|

   :versions: 1.26.0-1, 1.24.0-0, 1.22.0-0, 1.20.0-0
   
   :depends bioconductor-affy: >=1.62.0,<1.63.0
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends bioconductor-biostrings: >=2.52.0,<2.53.0
   :depends bioconductor-genomegraphs: >=1.44.0,<1.45.0
   :depends bioconductor-genomicranges: >=1.36.0,<1.37.0
   :depends bioconductor-iranges: >=2.18.0,<2.19.0
   :depends bioconductor-oligo: >=1.48.0,<1.49.0
   :depends bioconductor-oligoclasses: >=1.46.0,<1.47.0
   :depends bioconductor-preprocesscore: >=1.46.0,<1.47.0
   :depends libgcc-ng: >=7.3.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-waveslim: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-wavetiling

   and update with::

      conda update bioconductor-wavetiling

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-wavetiling:<tag>

   (see `bioconductor-wavetiling/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-wavetiling| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-wavetiling.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-wavetiling
   :alt:   (downloads)
.. |docker_bioconductor-wavetiling| image:: https://quay.io/repository/biocontainers/bioconductor-wavetiling/status
   :target: https://quay.io/repository/biocontainers/bioconductor-wavetiling
.. _`bioconductor-wavetiling/tags`: https://quay.io/repository/biocontainers/bioconductor-wavetiling?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-wavetiling/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-wavetiling/README.html