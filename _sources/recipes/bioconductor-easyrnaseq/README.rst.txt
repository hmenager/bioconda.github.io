:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-easyrnaseq'
.. highlight: bash

bioconductor-easyrnaseq
=======================

.. conda:recipe:: bioconductor-easyrnaseq
   :replaces_section_title:

   Calculates the coverage of high\-throughput short\-reads against a genome of reference and summarizes it per feature of interest \(e.g. exon\, gene\, transcript\). The data can be normalized as \'RPKM\' or by the \'DESeq\' or \'edgeR\' package.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/easyRNASeq.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-easyrnaseq <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-easyrnaseq>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-easyrnaseq/meta.yaml>`_
   :links: biotools: :biotools:`easyrnaseq`

   


.. conda:package:: bioconductor-easyrnaseq

   |downloads_bioconductor-easyrnaseq| |docker_bioconductor-easyrnaseq|

   :versions: 2.20.0-1, 2.18.2-0, 2.16.0-0, 2.14.0-0
   
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends bioconductor-biocfilecache: >=1.8.0,<1.9.0
   :depends bioconductor-biocgenerics: >=0.30.0,<0.31.0
   :depends bioconductor-biocparallel: >=1.18.0,<1.19.0
   :depends bioconductor-biomart: >=2.40.0,<2.41.0
   :depends bioconductor-biostrings: >=2.52.0,<2.53.0
   :depends bioconductor-deseq: >=1.36.0,<1.37.0
   :depends bioconductor-edger: >=3.26.0,<3.27.0
   :depends bioconductor-genomeinfodb: >=1.20.0,<1.21.0
   :depends bioconductor-genomeintervals: >=1.40.0,<1.41.0
   :depends bioconductor-genomicalignments: >=1.20.0,<1.21.0
   :depends bioconductor-genomicranges: >=1.36.0,<1.37.0
   :depends bioconductor-iranges: >=2.18.0,<2.19.0
   :depends bioconductor-rsamtools: >=2.0.0,<2.1.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends bioconductor-shortread: >=1.42.0,<1.43.0
   :depends bioconductor-summarizedexperiment: >=1.14.0,<1.15.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-locfit: 
   :depends r-lsd: >=4.0
   :depends r-rappdirs: >=0.3.1
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-easyrnaseq

   and update with::

      conda update bioconductor-easyrnaseq

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-easyrnaseq:<tag>

   (see `bioconductor-easyrnaseq/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-easyrnaseq| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-easyrnaseq.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-easyrnaseq
   :alt:   (downloads)
.. |docker_bioconductor-easyrnaseq| image:: https://quay.io/repository/biocontainers/bioconductor-easyrnaseq/status
   :target: https://quay.io/repository/biocontainers/bioconductor-easyrnaseq
.. _`bioconductor-easyrnaseq/tags`: https://quay.io/repository/biocontainers/bioconductor-easyrnaseq?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-easyrnaseq/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-easyrnaseq/README.html