:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-batchqc'
.. highlight: bash

bioconductor-batchqc
====================

.. conda:recipe:: bioconductor-batchqc
   :replaces_section_title:

   Sequencing and microarray samples often are collected or processed in multiple batches or at different times. This often produces technical biases that can lead to incorrect results in the downstream analysis. BatchQC is a software tool that streamlines batch preprocessing and evaluation by providing interactive diagnostics\, visualizations\, and statistical analyses to explore the extent to which batch variation impacts the data. BatchQC diagnostics help determine whether batch adjustment needs to be done\, and how correction should be applied before proceeding with a downstream analysis. Moreover\, BatchQC interactively applies multiple common batch effect approaches to the data\, and the user can quickly see the benefits of each method. BatchQC is developed as a Shiny App. The output is organized into multiple tabs\, and each tab features an important part of the batch effect analysis and visualization of the data. The BatchQC interface has the following analysis groups\: Summary\, Differential Expression\, Median Correlations\, Heatmaps\, Circular Dendrogram\, PCA Analysis\, Shape\, ComBat and SVA.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/BatchQC.html
   :license: GPL (>= 2)
   :recipe: /`bioconductor-batchqc <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-batchqc>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-batchqc/meta.yaml>`_
   :links: biotools: :biotools:`batchqc`

   


.. conda:package:: bioconductor-batchqc

   |downloads_bioconductor-batchqc| |docker_bioconductor-batchqc|

   :versions: 1.12.0-1, 1.10.1-0, 1.8.1-0, 1.6.1-0
   
   :depends bioconductor-limma: >=3.40.0,<3.41.0
   :depends bioconductor-sva: >=3.32.0,<3.33.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-corpcor: 
   :depends r-d3heatmap: 
   :depends r-ggvis: 
   :depends r-gplots: 
   :depends r-knitr: 
   :depends r-matrix: 
   :depends r-matrixstats: 
   :depends r-mcmcpack: 
   :depends r-moments: 
   :depends r-pander: 
   :depends r-reshape2: 
   :depends r-rmarkdown: 
   :depends r-shiny: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-batchqc

   and update with::

      conda update bioconductor-batchqc

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-batchqc:<tag>

   (see `bioconductor-batchqc/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-batchqc| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-batchqc.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-batchqc
   :alt:   (downloads)
.. |docker_bioconductor-batchqc| image:: https://quay.io/repository/biocontainers/bioconductor-batchqc/status
   :target: https://quay.io/repository/biocontainers/bioconductor-batchqc
.. _`bioconductor-batchqc/tags`: https://quay.io/repository/biocontainers/bioconductor-batchqc?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-batchqc/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-batchqc/README.html