:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-ichip'
.. highlight: bash

bioconductor-ichip
==================

.. conda:recipe:: bioconductor-ichip
   :replaces_section_title:

   Hidden Ising models are implemented to identify enriched genomic regions in ChIP\-chip data.  They can be used to analyze the data from multiple platforms \(e.g.\, Affymetrix\, Agilent\, and NimbleGen\)\, and the data with single to multiple replicates.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/iChip.html
   :license: GPL (>= 2)
   :recipe: /`bioconductor-ichip <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-ichip>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-ichip/meta.yaml>`_
   :links: biotools: :biotools:`ichip`, doi: :doi:`10.1093/bioinformatics/btq032`

   


.. conda:package:: bioconductor-ichip

   |downloads_bioconductor-ichip| |docker_bioconductor-ichip|

   :versions: 1.38.0-1, 1.38.0-0, 1.36.0-0, 1.34.0-0, 1.32.0-0
   
   :depends bioconductor-limma: >=3.40.0,<3.41.0
   :depends libgcc-ng: >=7.3.0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-ichip

   and update with::

      conda update bioconductor-ichip

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-ichip:<tag>

   (see `bioconductor-ichip/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-ichip| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-ichip.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-ichip
   :alt:   (downloads)
.. |docker_bioconductor-ichip| image:: https://quay.io/repository/biocontainers/bioconductor-ichip/status
   :target: https://quay.io/repository/biocontainers/bioconductor-ichip
.. _`bioconductor-ichip/tags`: https://quay.io/repository/biocontainers/bioconductor-ichip?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-ichip/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-ichip/README.html