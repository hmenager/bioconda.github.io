:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-minfi'
.. highlight: bash

bioconductor-minfi
==================

.. conda:recipe:: bioconductor-minfi
   :replaces_section_title:

   Tools to analyze \& visualize Illumina Infinium methylation arrays.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/minfi.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-minfi <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-minfi>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-minfi/meta.yaml>`_
   :links: biotools: :biotools:`minfi`

   


.. conda:package:: bioconductor-minfi

   |downloads_bioconductor-minfi| |docker_bioconductor-minfi|

   :versions: 1.30.0-1, 1.28.0-0, 1.26.2-0, 1.24.0-0, 1.22.1-0, 1.20.0-0, 1.16.1-0
   
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends bioconductor-biocgenerics: >=0.30.0,<0.31.0
   :depends bioconductor-biocparallel: >=1.18.0,<1.19.0
   :depends bioconductor-biostrings: >=2.52.0,<2.53.0
   :depends bioconductor-bumphunter: >=1.26.0,<1.27.0
   :depends bioconductor-delayedarray: >=0.10.0,<0.11.0
   :depends bioconductor-delayedmatrixstats: >=1.6.0,<1.7.0
   :depends bioconductor-genefilter: >=1.66.0,<1.67.0
   :depends bioconductor-genomeinfodb: >=1.20.0,<1.21.0
   :depends bioconductor-genomicranges: >=1.36.0,<1.37.0
   :depends bioconductor-geoquery: >=2.52.0,<2.53.0
   :depends bioconductor-hdf5array: >=1.12.0,<1.13.0
   :depends bioconductor-illuminaio: >=0.26.0,<0.27.0
   :depends bioconductor-iranges: >=2.18.0,<2.19.0
   :depends bioconductor-limma: >=3.40.0,<3.41.0
   :depends bioconductor-preprocesscore: >=1.46.0,<1.47.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends bioconductor-siggenes: >=1.58.0,<1.59.0
   :depends bioconductor-summarizedexperiment: >=1.14.0,<1.15.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-beanplot: 
   :depends r-data.table: 
   :depends r-lattice: 
   :depends r-mass: 
   :depends r-mclust: 
   :depends r-nlme: 
   :depends r-nor1mix: 
   :depends r-quadprog: 
   :depends r-rcolorbrewer: 
   :depends r-reshape: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-minfi

   and update with::

      conda update bioconductor-minfi

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-minfi:<tag>

   (see `bioconductor-minfi/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-minfi| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-minfi.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-minfi
   :alt:   (downloads)
.. |docker_bioconductor-minfi| image:: https://quay.io/repository/biocontainers/bioconductor-minfi/status
   :target: https://quay.io/repository/biocontainers/bioconductor-minfi
.. _`bioconductor-minfi/tags`: https://quay.io/repository/biocontainers/bioconductor-minfi?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-minfi/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-minfi/README.html