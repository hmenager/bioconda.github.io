:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-mofa'
.. highlight: bash

bioconductor-mofa
=================

.. conda:recipe:: bioconductor-mofa
   :replaces_section_title:

   Multi\-Omics Factor Analysis\: an unsupervised framework for the integration of multi\-omics data sets.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/MOFA.html
   :license: LGPL-3 | file LICENSE
   :recipe: /`bioconductor-mofa <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-mofa>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-mofa/meta.yaml>`_

   


.. conda:package:: bioconductor-mofa

   |downloads_bioconductor-mofa| |docker_bioconductor-mofa|

   :versions: 1.0.0-1
   
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends bioconductor-multiassayexperiment: >=1.10.0,<1.11.0
   :depends bioconductor-rhdf5: >=2.28.0,<2.29.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-corrplot: 
   :depends r-cowplot: 
   :depends r-doparallel: 
   :depends r-dplyr: 
   :depends r-foreach: 
   :depends r-ggally: 
   :depends r-ggbeeswarm: 
   :depends r-ggplot2: 
   :depends r-ggrepel: 
   :depends r-pheatmap: 
   :depends r-rcolorbrewer: 
   :depends r-reshape2: 
   :depends r-reticulate: 
   :depends r-scales: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-mofa

   and update with::

      conda update bioconductor-mofa

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-mofa:<tag>

   (see `bioconductor-mofa/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-mofa| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-mofa.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-mofa
   :alt:   (downloads)
.. |docker_bioconductor-mofa| image:: https://quay.io/repository/biocontainers/bioconductor-mofa/status
   :target: https://quay.io/repository/biocontainers/bioconductor-mofa
.. _`bioconductor-mofa/tags`: https://quay.io/repository/biocontainers/bioconductor-mofa?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-mofa/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-mofa/README.html