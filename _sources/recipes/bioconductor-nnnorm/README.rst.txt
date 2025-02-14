:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-nnnorm'
.. highlight: bash

bioconductor-nnnorm
===================

.. conda:recipe:: bioconductor-nnnorm
   :replaces_section_title:

   This package allows to detect and correct for spatial and intensity biases with two\-channel microarray data. The normalization method implemented in this package is based on robust neural networks fitting.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/nnNorm.html
   :license: LGPL
   :recipe: /`bioconductor-nnnorm <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-nnnorm>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-nnnorm/meta.yaml>`_
   :links: biotools: :biotools:`nnnorm`, doi: :doi:`10.1093/bioinformatics/bti397`

   


.. conda:package:: bioconductor-nnnorm

   |downloads_bioconductor-nnnorm| |docker_bioconductor-nnnorm|

   :versions: 2.48.0-1, 2.48.0-0, 2.46.0-0, 2.44.0-0, 2.42.0-0, 2.40.0-0
   
   :depends bioconductor-marray: >=1.62.0,<1.63.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-nnet: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-nnnorm

   and update with::

      conda update bioconductor-nnnorm

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-nnnorm:<tag>

   (see `bioconductor-nnnorm/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-nnnorm| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-nnnorm.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-nnnorm
   :alt:   (downloads)
.. |docker_bioconductor-nnnorm| image:: https://quay.io/repository/biocontainers/bioconductor-nnnorm/status
   :target: https://quay.io/repository/biocontainers/bioconductor-nnnorm
.. _`bioconductor-nnnorm/tags`: https://quay.io/repository/biocontainers/bioconductor-nnnorm?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-nnnorm/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-nnnorm/README.html