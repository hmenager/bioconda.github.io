:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-proloc'
.. highlight: bash

bioconductor-proloc
===================

.. conda:recipe:: bioconductor-proloc
   :replaces_section_title:

   The pRoloc package implements machine learning and visualisation methods for the analysis and interogation of quantitiative mass spectrometry data to reliably infer protein sub\-cellular localisation.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/pRoloc.html
   :license: GPL-2
   :recipe: /`bioconductor-proloc <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-proloc>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-proloc/meta.yaml>`_
   :links: biotools: :biotools:`proloc`

   


.. conda:package:: bioconductor-proloc

   |downloads_bioconductor-proloc| |docker_bioconductor-proloc|

   :versions: 1.24.0-1, 1.22.1-0, 1.22.0-0, 1.18.0-0
   
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends bioconductor-biocgenerics: >=0.30.0,<0.31.0
   :depends bioconductor-biocparallel: >=1.18.0,<1.19.0
   :depends bioconductor-biomart: >=2.40.0,<2.41.0
   :depends bioconductor-mlinterfaces: >=1.64.0,<1.65.0
   :depends bioconductor-msnbase: >=2.10.0,<2.11.0
   :depends libgcc-ng: >=7.3.0
   :depends libstdcxx-ng: >=7.3.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-caret: 
   :depends r-class: 
   :depends r-coda: 
   :depends r-dendextend: 
   :depends r-e1071: 
   :depends r-fnn: 
   :depends r-ggplot2: 
   :depends r-gtools: 
   :depends r-hexbin: 
   :depends r-kernlab: 
   :depends r-knitr: 
   :depends r-laplacesdemon: 
   :depends r-lattice: 
   :depends r-mass: 
   :depends r-mclust: >=4.3
   :depends r-mixtools: 
   :depends r-mvtnorm: 
   :depends r-nnet: 
   :depends r-plyr: 
   :depends r-proxy: 
   :depends r-randomforest: 
   :depends r-rcolorbrewer: 
   :depends r-rcpp: >=0.10.3
   :depends r-rcpparmadillo: 
   :depends r-sampling: 
   :depends r-scales: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-proloc

   and update with::

      conda update bioconductor-proloc

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-proloc:<tag>

   (see `bioconductor-proloc/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-proloc| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-proloc.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-proloc
   :alt:   (downloads)
.. |docker_bioconductor-proloc| image:: https://quay.io/repository/biocontainers/bioconductor-proloc/status
   :target: https://quay.io/repository/biocontainers/bioconductor-proloc
.. _`bioconductor-proloc/tags`: https://quay.io/repository/biocontainers/bioconductor-proloc?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-proloc/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-proloc/README.html