:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-demixt'
.. highlight: bash

bioconductor-demixt
===================

.. conda:recipe:: bioconductor-demixt
   :replaces_section_title:

   DeMixT is a software package that performs deconvolution on transcriptome data from a mixture of two or three components.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/DeMixT.html
   :license: GPL-3
   :recipe: /`bioconductor-demixt <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-demixt>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-demixt/meta.yaml>`_

   


.. conda:package:: bioconductor-demixt

   |downloads_bioconductor-demixt| |docker_bioconductor-demixt|

   :versions: 1.0.2-0
   
   :depends bioconductor-summarizedexperiment: >=1.14.0,<1.15.0
   :depends libgcc-ng: >=7.3.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-kernsmooth: 
   :depends r-knitr: 
   :depends r-matrixstats: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-demixt

   and update with::

      conda update bioconductor-demixt

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-demixt:<tag>

   (see `bioconductor-demixt/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-demixt| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-demixt.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-demixt
   :alt:   (downloads)
.. |docker_bioconductor-demixt| image:: https://quay.io/repository/biocontainers/bioconductor-demixt/status
   :target: https://quay.io/repository/biocontainers/bioconductor-demixt
.. _`bioconductor-demixt/tags`: https://quay.io/repository/biocontainers/bioconductor-demixt?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-demixt/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-demixt/README.html