:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-contibait'
.. highlight: bash

bioconductor-contibait
======================

.. conda:recipe:: bioconductor-contibait
   :replaces_section_title:

   Using strand inheritance data from multiple single cells from the organism whose genome is to be assembled\, contiBAIT can cluster unbridged contigs together into putative chromosomes\, and order the contigs within those chromosomes.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/contiBAIT.html
   :license: BSD_2_clause + file LICENSE
   :recipe: /`bioconductor-contibait <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-contibait>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-contibait/meta.yaml>`_
   :links: biotools: :biotools:`contibait`, doi: :doi:`10.1093/bioinformatics/btx281`

   


.. conda:package:: bioconductor-contibait

   |downloads_bioconductor-contibait| |docker_bioconductor-contibait|

   :versions: 1.12.0-1, 1.10.0-0, 1.8.0-0, 1.6.0-0
   
   :depends bioconductor-biocparallel: >=1.18.0,<1.19.0
   :depends bioconductor-dnacopy: >=1.58.0,<1.59.0
   :depends bioconductor-exomecopy: >=1.30.0,<1.31.0
   :depends bioconductor-genomicalignments: >=1.20.0,<1.21.0
   :depends bioconductor-genomicfiles: >=1.20.0,<1.21.0
   :depends bioconductor-genomicranges: >=1.36.0,<1.37.0
   :depends bioconductor-iranges: >=2.18.0,<2.19.0
   :depends bioconductor-rsamtools: >=2.0.0,<2.1.0
   :depends bioconductor-rtracklayer: >=1.44.0,<1.45.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends libgcc-ng: >=7.3.0
   :depends libstdcxx-ng: >=7.3.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-bh: >=1.51.0-3
   :depends r-clue: 
   :depends r-cluster: 
   :depends r-colorspace: 
   :depends r-data.table: 
   :depends r-diagram: 
   :depends r-ggplot2: 
   :depends r-gplots: 
   :depends r-gtools: 
   :depends r-rcpp: 
   :depends r-reshape2: 
   :depends r-tsp: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-contibait

   and update with::

      conda update bioconductor-contibait

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-contibait:<tag>

   (see `bioconductor-contibait/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-contibait| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-contibait.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-contibait
   :alt:   (downloads)
.. |docker_bioconductor-contibait| image:: https://quay.io/repository/biocontainers/bioconductor-contibait/status
   :target: https://quay.io/repository/biocontainers/bioconductor-contibait
.. _`bioconductor-contibait/tags`: https://quay.io/repository/biocontainers/bioconductor-contibait?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-contibait/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-contibait/README.html