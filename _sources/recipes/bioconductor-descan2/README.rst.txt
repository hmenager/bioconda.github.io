:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-descan2'
.. highlight: bash

bioconductor-descan2
====================

.. conda:recipe:: bioconductor-descan2
   :replaces_section_title:

   Integrated peak and differential caller\, specifically designed for broad epigenomic signals.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/DEScan2.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-descan2 <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-descan2>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-descan2/meta.yaml>`_

   


.. conda:package:: bioconductor-descan2

   |downloads_bioconductor-descan2| |docker_bioconductor-descan2|

   :versions: 1.4.0-1, 1.2.0-0
   
   :depends bioconductor-biocgenerics: >=0.30.0,<0.31.0
   :depends bioconductor-biocparallel: >=1.18.0,<1.19.0
   :depends bioconductor-chippeakanno: >=3.18.0,<3.19.0
   :depends bioconductor-delayedarray: >=0.10.0,<0.11.0
   :depends bioconductor-genomeinfodb: >=1.20.0,<1.21.0
   :depends bioconductor-genomicalignments: >=1.20.0,<1.21.0
   :depends bioconductor-genomicranges: >=1.36.0,<1.37.0
   :depends bioconductor-iranges: >=2.18.0,<2.19.0
   :depends bioconductor-rtracklayer: >=1.44.0,<1.45.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends bioconductor-summarizedexperiment: >=1.14.0,<1.15.0
   :depends libgcc-ng: >=7.3.0
   :depends libstdcxx-ng: >=7.3.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-data.table: 
   :depends r-glue: 
   :depends r-plyr: 
   :depends r-rcpp: >=0.12.13
   :depends r-rcpparmadillo: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-descan2

   and update with::

      conda update bioconductor-descan2

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-descan2:<tag>

   (see `bioconductor-descan2/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-descan2| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-descan2.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-descan2
   :alt:   (downloads)
.. |docker_bioconductor-descan2| image:: https://quay.io/repository/biocontainers/bioconductor-descan2/status
   :target: https://quay.io/repository/biocontainers/bioconductor-descan2
.. _`bioconductor-descan2/tags`: https://quay.io/repository/biocontainers/bioconductor-descan2?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-descan2/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-descan2/README.html