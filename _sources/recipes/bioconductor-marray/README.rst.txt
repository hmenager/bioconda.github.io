:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-marray'
.. highlight: bash

bioconductor-marray
===================

.. conda:recipe:: bioconductor-marray
   :replaces_section_title:

   Class definitions for two\-color spotted microarray data. Fuctions for data input\, diagnostic plots\, normalization and quality checking.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/marray.html
   :license: LGPL
   :recipe: /`bioconductor-marray <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-marray>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-marray/meta.yaml>`_
   :links: biotools: :biotools:`marray`, doi: :doi:`10.1007/0-387-21679-0_3`

   


.. conda:package:: bioconductor-marray

   |downloads_bioconductor-marray| |docker_bioconductor-marray|

   :versions: 1.62.0-1, 1.62.0-0, 1.60.0-1, 1.60.0-0, 1.58.0-0, 1.56.0-0, 1.54.0-0, 1.50.0-1, 1.50.0-0
   
   :depends bioconductor-limma: >=3.40.0,<3.41.0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-marray

   and update with::

      conda update bioconductor-marray

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-marray:<tag>

   (see `bioconductor-marray/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-marray| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-marray.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-marray
   :alt:   (downloads)
.. |docker_bioconductor-marray| image:: https://quay.io/repository/biocontainers/bioconductor-marray/status
   :target: https://quay.io/repository/biocontainers/bioconductor-marray
.. _`bioconductor-marray/tags`: https://quay.io/repository/biocontainers/bioconductor-marray?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-marray/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-marray/README.html