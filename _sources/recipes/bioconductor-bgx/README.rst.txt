:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-bgx'
.. highlight: bash

bioconductor-bgx
================

.. conda:recipe:: bioconductor-bgx
   :replaces_section_title:

   Bayesian integrated analysis of Affymetrix GeneChips

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/bgx.html
   :license: GPL-2
   :recipe: /`bioconductor-bgx <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-bgx>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-bgx/meta.yaml>`_

   


.. conda:package:: bioconductor-bgx

   |downloads_bioconductor-bgx| |docker_bioconductor-bgx|

   :versions: 1.50.0-1
   
   :depends bioconductor-affy: >=1.62.0,<1.63.0
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends bioconductor-gcrma: >=2.56.0,<2.57.0
   :depends libcxx: >=4.0.1
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-rcpp: >=0.11.0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-bgx

   and update with::

      conda update bioconductor-bgx

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-bgx:<tag>

   (see `bioconductor-bgx/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-bgx| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-bgx.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-bgx
   :alt:   (downloads)
.. |docker_bioconductor-bgx| image:: https://quay.io/repository/biocontainers/bioconductor-bgx/status
   :target: https://quay.io/repository/biocontainers/bioconductor-bgx
.. _`bioconductor-bgx/tags`: https://quay.io/repository/biocontainers/bioconductor-bgx?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-bgx/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-bgx/README.html