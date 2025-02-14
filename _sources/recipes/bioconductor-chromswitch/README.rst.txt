:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-chromswitch'
.. highlight: bash

bioconductor-chromswitch
========================

.. conda:recipe:: bioconductor-chromswitch
   :replaces_section_title:

   Chromswitch implements a flexible method to detect chromatin state switches between samples in two biological conditions in a specific genomic region of interest given peaks or chromatin state calls from ChIP\-seq data.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/chromswitch.html
   :license: MIT + file LICENSE
   :recipe: /`bioconductor-chromswitch <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-chromswitch>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-chromswitch/meta.yaml>`_

   


.. conda:package:: bioconductor-chromswitch

   |downloads_bioconductor-chromswitch| |docker_bioconductor-chromswitch|

   :versions: 1.6.0-1, 1.4.1-0, 1.4.0-0
   
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends bioconductor-biocparallel: >=1.18.0,<1.19.0
   :depends bioconductor-genomicranges: >=1.36.0,<1.37.0
   :depends bioconductor-iranges: >=2.18.0,<2.19.0
   :depends bioconductor-rtracklayer: >=1.44.0,<1.45.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-cluster: >=2.0.6
   :depends r-dplyr: >=0.5.0
   :depends r-gplots: >=3.0.1
   :depends r-lazyeval: >=0.2.0
   :depends r-magrittr: >=1.5
   :depends r-matrixstats: >=0.52
   :depends r-nmf: >=0.20.6
   :depends r-tidyr: >=0.6.3
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-chromswitch

   and update with::

      conda update bioconductor-chromswitch

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-chromswitch:<tag>

   (see `bioconductor-chromswitch/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-chromswitch| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-chromswitch.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-chromswitch
   :alt:   (downloads)
.. |docker_bioconductor-chromswitch| image:: https://quay.io/repository/biocontainers/bioconductor-chromswitch/status
   :target: https://quay.io/repository/biocontainers/bioconductor-chromswitch
.. _`bioconductor-chromswitch/tags`: https://quay.io/repository/biocontainers/bioconductor-chromswitch?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-chromswitch/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-chromswitch/README.html