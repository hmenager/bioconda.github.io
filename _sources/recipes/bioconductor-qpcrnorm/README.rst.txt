:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-qpcrnorm'
.. highlight: bash

bioconductor-qpcrnorm
=====================

.. conda:recipe:: bioconductor-qpcrnorm
   :replaces_section_title:

   The package contains functions to perform normalization of high\-throughput qPCR data. Basic functions for processing raw Ct data plus functions to generate diagnostic plots are also available.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/qpcrNorm.html
   :license: LGPL (>= 2)
   :recipe: /`bioconductor-qpcrnorm <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-qpcrnorm>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-qpcrnorm/meta.yaml>`_
   :links: biotools: :biotools:`qpcrnorm`, doi: :doi:`10.1186/1471-2105-10-110`

   


.. conda:package:: bioconductor-qpcrnorm

   |downloads_bioconductor-qpcrnorm| |docker_bioconductor-qpcrnorm|

   :versions: 1.42.0-1, 1.40.0-1, 1.40.0-0, 1.38.0-0, 1.36.0-0, 1.34.0-0
   
   :depends bioconductor-affy: >=1.62.0,<1.63.0
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends bioconductor-limma: >=3.40.0,<3.41.0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-qpcrnorm

   and update with::

      conda update bioconductor-qpcrnorm

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-qpcrnorm:<tag>

   (see `bioconductor-qpcrnorm/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-qpcrnorm| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-qpcrnorm.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-qpcrnorm
   :alt:   (downloads)
.. |docker_bioconductor-qpcrnorm| image:: https://quay.io/repository/biocontainers/bioconductor-qpcrnorm/status
   :target: https://quay.io/repository/biocontainers/bioconductor-qpcrnorm
.. _`bioconductor-qpcrnorm/tags`: https://quay.io/repository/biocontainers/bioconductor-qpcrnorm?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-qpcrnorm/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-qpcrnorm/README.html