:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-phemd'
.. highlight: bash

bioconductor-phemd
==================

.. conda:recipe:: bioconductor-phemd
   :replaces_section_title:

   Package for comparing and generating a low\-dimensional embedding of multiple single\-cell samples.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/phemd.html
   :license: GPL-2
   :recipe: /`bioconductor-phemd <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-phemd>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-phemd/meta.yaml>`_

   


.. conda:package:: bioconductor-phemd

   |downloads_bioconductor-phemd| |docker_bioconductor-phemd|

   :versions: 1.0.1-0
   
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends bioconductor-biocgenerics: >=0.30.0,<0.31.0
   :depends bioconductor-destiny: >=2.14.0,<2.15.0
   :depends bioconductor-monocle: >=2.12.0,<2.13.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends bioconductor-singlecellexperiment: >=1.6.0,<1.7.0
   :depends bioconductor-summarizedexperiment: >=1.14.0,<1.15.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-cluster: 
   :depends r-cowplot: 
   :depends r-ggplot2: 
   :depends r-igraph: 
   :depends r-maptree: 
   :depends r-pheatmap: 
   :depends r-pracma: 
   :depends r-rann: 
   :depends r-rcolorbrewer: 
   :depends r-rtsne: 
   :depends r-scatterplot3d: 
   :depends r-seurat: 
   :depends r-transport: 
   :depends r-vgam: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-phemd

   and update with::

      conda update bioconductor-phemd

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-phemd:<tag>

   (see `bioconductor-phemd/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-phemd| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-phemd.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-phemd
   :alt:   (downloads)
.. |docker_bioconductor-phemd| image:: https://quay.io/repository/biocontainers/bioconductor-phemd/status
   :target: https://quay.io/repository/biocontainers/bioconductor-phemd
.. _`bioconductor-phemd/tags`: https://quay.io/repository/biocontainers/bioconductor-phemd?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-phemd/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-phemd/README.html