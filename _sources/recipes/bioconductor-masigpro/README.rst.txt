:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-masigpro'
.. highlight: bash

bioconductor-masigpro
=====================

.. conda:recipe:: bioconductor-masigpro
   :replaces_section_title:

   maSigPro is a regression based approach to find genes for which there are significant gene expression profile differences between experimental groups in time course microarray and RNA\-Seq experiments.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/maSigPro.html
   :license: GPL (>= 2)
   :recipe: /`bioconductor-masigpro <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-masigpro>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-masigpro/meta.yaml>`_
   :links: biotools: :biotools:`masigpro`, doi: :doi:`10.1093/bioinformatics/btu333`

   


.. conda:package:: bioconductor-masigpro

   |downloads_bioconductor-masigpro| |docker_bioconductor-masigpro|

   :versions: 1.56.0-1, 1.54.0-0, 1.52.0-0, 1.50.0-0, 1.49.4-0, 1.49.3-0, 1.49.0-0, 1.48.0-0, 1.46.0-0
   
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-mass: 
   :depends r-mclust: 
   :depends r-venn: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-masigpro

   and update with::

      conda update bioconductor-masigpro

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-masigpro:<tag>

   (see `bioconductor-masigpro/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-masigpro| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-masigpro.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-masigpro
   :alt:   (downloads)
.. |docker_bioconductor-masigpro| image:: https://quay.io/repository/biocontainers/bioconductor-masigpro/status
   :target: https://quay.io/repository/biocontainers/bioconductor-masigpro
.. _`bioconductor-masigpro/tags`: https://quay.io/repository/biocontainers/bioconductor-masigpro?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-masigpro/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-masigpro/README.html