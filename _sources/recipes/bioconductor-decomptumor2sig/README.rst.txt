:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-decomptumor2sig'
.. highlight: bash

bioconductor-decomptumor2sig
============================

.. conda:recipe:: bioconductor-decomptumor2sig
   :replaces_section_title:

   Uses quadratic programming for signature refitting\, i.e.\, to decompose the mutation catalog from an individual tumor sample into a set of given mutational signatures \(either Alexandrov\-model signatures or Shiraishi\-model signatures\)\, computing weights that reflect the contributions of the signatures to the mutation load of the tumor.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/decompTumor2Sig.html
   :license: GPL-2
   :recipe: /`bioconductor-decomptumor2sig <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-decomptumor2sig>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-decomptumor2sig/meta.yaml>`_

   


.. conda:package:: bioconductor-decomptumor2sig

   |downloads_bioconductor-decomptumor2sig| |docker_bioconductor-decomptumor2sig|

   :versions: 2.0.0-1
   
   :depends bioconductor-biocgenerics: >=0.30.0,<0.31.0
   :depends bioconductor-biostrings: >=2.52.0,<2.53.0
   :depends bioconductor-bsgenome.hsapiens.ucsc.hg19: >=1.4.0,<1.5.0
   :depends bioconductor-genomicfeatures: >=1.36.0,<1.37.0
   :depends bioconductor-genomicranges: >=1.36.0,<1.37.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends bioconductor-summarizedexperiment: >=1.14.0,<1.15.0
   :depends bioconductor-txdb.hsapiens.ucsc.hg19.knowngene: >=3.2.0,<3.3.0
   :depends bioconductor-variantannotation: >=1.30.0,<1.31.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-data.table: 
   :depends r-ggplot2: 
   :depends r-ggseqlogo: 
   :depends r-gridextra: 
   :depends r-matrix: 
   :depends r-plyr: 
   :depends r-quadprog: >=1.5-5
   :depends r-vcfr: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-decomptumor2sig

   and update with::

      conda update bioconductor-decomptumor2sig

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-decomptumor2sig:<tag>

   (see `bioconductor-decomptumor2sig/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-decomptumor2sig| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-decomptumor2sig.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-decomptumor2sig
   :alt:   (downloads)
.. |docker_bioconductor-decomptumor2sig| image:: https://quay.io/repository/biocontainers/bioconductor-decomptumor2sig/status
   :target: https://quay.io/repository/biocontainers/bioconductor-decomptumor2sig
.. _`bioconductor-decomptumor2sig/tags`: https://quay.io/repository/biocontainers/bioconductor-decomptumor2sig?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-decomptumor2sig/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-decomptumor2sig/README.html