:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-lipidr'
.. highlight: bash

bioconductor-lipidr
===================

.. conda:recipe:: bioconductor-lipidr
   :replaces_section_title:

   lipidr an easy\-to\-use R package implementing a complete workflow for downstream analysis of lipidomics data. lipidr parses results exported from Skyline directly into R\, allowing integration into current analysis frameworks. lipidr allows data inspection\, normalization\, univariate and multivariate analysis\, displaying informative visualizations. lipidr also implements a novel Lipid Set Enrichment Analysis \(LSEA\)\, harnessing molecular information such as lipid class\, chain length and unsaturation.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/lipidr.html
   :license: MIT + file LICENSE
   :recipe: /`bioconductor-lipidr <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-lipidr>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-lipidr/meta.yaml>`_

   


.. conda:package:: bioconductor-lipidr

   |downloads_bioconductor-lipidr| |docker_bioconductor-lipidr|

   :versions: 1.0.0-1
   
   :depends bioconductor-fgsea: >=1.10.0,<1.11.0
   :depends bioconductor-limma: >=3.40.0,<3.41.0
   :depends bioconductor-ropls: >=1.16.0,<1.17.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends bioconductor-summarizedexperiment: >=1.14.0,<1.15.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-dplyr: 
   :depends r-forcats: 
   :depends r-ggplot2: 
   :depends r-magrittr: 
   :depends r-rlang: 
   :depends r-tidyr: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-lipidr

   and update with::

      conda update bioconductor-lipidr

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-lipidr:<tag>

   (see `bioconductor-lipidr/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-lipidr| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-lipidr.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-lipidr
   :alt:   (downloads)
.. |docker_bioconductor-lipidr| image:: https://quay.io/repository/biocontainers/bioconductor-lipidr/status
   :target: https://quay.io/repository/biocontainers/bioconductor-lipidr
.. _`bioconductor-lipidr/tags`: https://quay.io/repository/biocontainers/bioconductor-lipidr?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-lipidr/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-lipidr/README.html