:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-mlinterfaces'
.. highlight: bash

bioconductor-mlinterfaces
=========================

.. conda:recipe:: bioconductor-mlinterfaces
   :replaces_section_title:

   This package provides uniform interfaces to machine learning code for data in R and Bioconductor containers.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/MLInterfaces.html
   :license: LGPL
   :recipe: /`bioconductor-mlinterfaces <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-mlinterfaces>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-mlinterfaces/meta.yaml>`_
   :links: biotools: :biotools:`mlinterfaces`, doi: :doi:`10.1038/nmeth.3252`

   


.. conda:package:: bioconductor-mlinterfaces

   |downloads_bioconductor-mlinterfaces| |docker_bioconductor-mlinterfaces|

   :versions: 1.64.0-1, 1.62.0-0, 1.60.1-0, 1.58.0-0
   
   :depends bioconductor-annotate: >=1.62.0,<1.63.0
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends bioconductor-biocgenerics: >=0.30.0,<0.31.0
   :depends bioconductor-genefilter: >=1.66.0,<1.67.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-cluster: 
   :depends r-fpc: 
   :depends r-gbm: 
   :depends r-gdata: 
   :depends r-ggvis: 
   :depends r-hwriter: 
   :depends r-mass: 
   :depends r-mlbench: 
   :depends r-pls: 
   :depends r-rcolorbrewer: 
   :depends r-rda: 
   :depends r-rpart: 
   :depends r-sfsmisc: 
   :depends r-shiny: 
   :depends r-threejs: >=0.2.2
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-mlinterfaces

   and update with::

      conda update bioconductor-mlinterfaces

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-mlinterfaces:<tag>

   (see `bioconductor-mlinterfaces/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-mlinterfaces| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-mlinterfaces.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-mlinterfaces
   :alt:   (downloads)
.. |docker_bioconductor-mlinterfaces| image:: https://quay.io/repository/biocontainers/bioconductor-mlinterfaces/status
   :target: https://quay.io/repository/biocontainers/bioconductor-mlinterfaces
.. _`bioconductor-mlinterfaces/tags`: https://quay.io/repository/biocontainers/bioconductor-mlinterfaces?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-mlinterfaces/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-mlinterfaces/README.html