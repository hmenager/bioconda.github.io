:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-glmsparsenet'
.. highlight: bash

bioconductor-glmsparsenet
=========================

.. conda:recipe:: bioconductor-glmsparsenet
   :replaces_section_title:

   glmSparseNet is an R\-package that generalizes sparse regression models when the features \(e.g. genes\) have a graph structure \(e.g. protein\-protein interactions\)\, by including network\-based regularizers. glmSparseNet uses the glmnet R\-package\, by including centrality measures of the network as penalty weights in the regularization. The current version implements regularization based on node degree\, i.e. the strength and\/or number of its associated edges\, either by promoting hubs in the solution or orphan genes in the solution. All the glmnet distribution families are supported\, namely \"gaussian\"\, \"poisson\"\, \"binomial\"\, \"multinomial\"\, \"cox\"\, and \"mgaussian\".

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/glmSparseNet.html
   :license: GPL (>=3)
   :recipe: /`bioconductor-glmsparsenet <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-glmsparsenet>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-glmsparsenet/meta.yaml>`_

   


.. conda:package:: bioconductor-glmsparsenet

   |downloads_bioconductor-glmsparsenet| |docker_bioconductor-glmsparsenet|

   :versions: 1.2.0-0, 1.0.0-0
   
   :depends bioconductor-biomart: >=2.40.0,<2.41.0
   :depends bioconductor-multiassayexperiment: >=1.10.0,<1.11.0
   :depends bioconductor-stringdb: >=1.24.0,<1.25.0
   :depends bioconductor-summarizedexperiment: >=1.14.0,<1.15.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-dplyr: 
   :depends r-forcats: 
   :depends r-futile.logger: 
   :depends r-ggplot2: 
   :depends r-glmnet: 
   :depends r-loose.rock: >=1.0.12
   :depends r-matrix: 
   :depends r-readr: 
   :depends r-reshape2: 
   :depends r-rlang: 
   :depends r-sparsebn: 
   :depends r-sparsebnutils: 
   :depends r-stringr: 
   :depends r-survminer: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-glmsparsenet

   and update with::

      conda update bioconductor-glmsparsenet

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-glmsparsenet:<tag>

   (see `bioconductor-glmsparsenet/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-glmsparsenet| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-glmsparsenet.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-glmsparsenet
   :alt:   (downloads)
.. |docker_bioconductor-glmsparsenet| image:: https://quay.io/repository/biocontainers/bioconductor-glmsparsenet/status
   :target: https://quay.io/repository/biocontainers/bioconductor-glmsparsenet
.. _`bioconductor-glmsparsenet/tags`: https://quay.io/repository/biocontainers/bioconductor-glmsparsenet?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-glmsparsenet/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-glmsparsenet/README.html