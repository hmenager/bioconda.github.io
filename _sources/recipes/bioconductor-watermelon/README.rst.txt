:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-watermelon'
.. highlight: bash

bioconductor-watermelon
=======================

.. conda:recipe:: bioconductor-watermelon
   :replaces_section_title:

   15 flavours of betas and three performance metrics\, with methods for objects produced by methylumi and minfi packages.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/wateRmelon.html
   :license: GPL-3
   :recipe: /`bioconductor-watermelon <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-watermelon>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-watermelon/meta.yaml>`_
   :links: biotools: :biotools:`watermelon`

   


.. conda:package:: bioconductor-watermelon

   |downloads_bioconductor-watermelon| |docker_bioconductor-watermelon|

   :versions: 1.28.0-1, 1.26.0-0, 1.24.0-0, 1.22.0-0
   
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends bioconductor-illuminahumanmethylation450kanno.ilmn12.hg19: >=0.6.0,<0.7.0
   :depends bioconductor-illuminaio: >=0.26.0,<0.27.0
   :depends bioconductor-limma: >=3.40.0,<3.41.0
   :depends bioconductor-lumi: >=2.36.0,<2.37.0
   :depends bioconductor-methylumi: >=2.30.0,<2.31.0
   :depends bioconductor-roc: >=1.60.0,<1.61.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-matrixstats: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-watermelon

   and update with::

      conda update bioconductor-watermelon

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-watermelon:<tag>

   (see `bioconductor-watermelon/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-watermelon| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-watermelon.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-watermelon
   :alt:   (downloads)
.. |docker_bioconductor-watermelon| image:: https://quay.io/repository/biocontainers/bioconductor-watermelon/status
   :target: https://quay.io/repository/biocontainers/bioconductor-watermelon
.. _`bioconductor-watermelon/tags`: https://quay.io/repository/biocontainers/bioconductor-watermelon?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-watermelon/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-watermelon/README.html