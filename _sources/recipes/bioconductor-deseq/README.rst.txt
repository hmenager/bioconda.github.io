:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-deseq'
.. highlight: bash

bioconductor-deseq
==================

.. conda:recipe:: bioconductor-deseq
   :replaces_section_title:

   Estimate variance\-mean dependence in count data from high\-throughput sequencing assays and test for differential expression based on a model using the negative binomial distribution

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/DESeq.html
   :license: GPL (>= 3)
   :recipe: /`bioconductor-deseq <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-deseq>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-deseq/meta.yaml>`_
   :links: biotools: :biotools:`deseq`

   


.. conda:package:: bioconductor-deseq

   |downloads_bioconductor-deseq| |docker_bioconductor-deseq|

   :versions: 1.36.0-1, 1.34.1-0, 1.34.0-0, 1.32.0-0, 1.30.0-0, 1.28.0-0, 1.24.0-0, 1.22.1-0
   
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends bioconductor-biocgenerics: >=0.30.0,<0.31.0
   :depends bioconductor-genefilter: >=1.66.0,<1.67.0
   :depends bioconductor-geneplotter: >=1.62.0,<1.63.0
   :depends libgcc-ng: >=7.3.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-lattice: 
   :depends r-locfit: 
   :depends r-mass: 
   :depends r-rcolorbrewer: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-deseq

   and update with::

      conda update bioconductor-deseq

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-deseq:<tag>

   (see `bioconductor-deseq/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-deseq| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-deseq.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-deseq
   :alt:   (downloads)
.. |docker_bioconductor-deseq| image:: https://quay.io/repository/biocontainers/bioconductor-deseq/status
   :target: https://quay.io/repository/biocontainers/bioconductor-deseq
.. _`bioconductor-deseq/tags`: https://quay.io/repository/biocontainers/bioconductor-deseq?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-deseq/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-deseq/README.html