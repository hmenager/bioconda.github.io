:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-rmmquant'
.. highlight: bash

bioconductor-rmmquant
=====================

.. conda:recipe:: bioconductor-rmmquant
   :replaces_section_title:

   RNA\-Seq is currently used routinely\, and it provides accurate information on gene transcription. However\, the method cannot accurately estimate duplicated genes expression. Several strategies have been previously used\, but all of them provide biased results. With Rmmquant\, if a read maps at different positions\, the tool detects that the corresponding genes are duplicated\; it merges the genes and creates a merged gene. The counts of ambiguous reads is then based on the input genes and the merged genes. Rmmquant is a drop\-in replacement of the widely used tools findOverlaps and featureCounts that handles multi\-mapping reads in an unabiased way.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/Rmmquant.html
   :license: GPL-3
   :recipe: /`bioconductor-rmmquant <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-rmmquant>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-rmmquant/meta.yaml>`_

   


.. conda:package:: bioconductor-rmmquant

   |downloads_bioconductor-rmmquant| |docker_bioconductor-rmmquant|

   :versions: 1.2.0-1, 1.0.0-0
   
   :depends bioconductor-biocstyle: >=2.12.0,<2.13.0
   :depends bioconductor-deseq2: >=1.24.0,<1.25.0
   :depends bioconductor-genomicranges: >=1.36.0,<1.37.0
   :depends bioconductor-org.mm.eg.db: >=3.8.0,<3.9.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends bioconductor-summarizedexperiment: >=1.14.0,<1.15.0
   :depends bioconductor-tbx20bamsubset: >=1.20.0,<1.21.0
   :depends bioconductor-txdb.mmusculus.ucsc.mm9.knowngene: >=3.2.0,<3.3.0
   :depends libgcc-ng: >=7.3.0
   :depends libstdcxx-ng: >=7.3.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-devtools: 
   :depends r-rcpp: >=0.12.8
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-rmmquant

   and update with::

      conda update bioconductor-rmmquant

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-rmmquant:<tag>

   (see `bioconductor-rmmquant/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-rmmquant| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-rmmquant.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-rmmquant
   :alt:   (downloads)
.. |docker_bioconductor-rmmquant| image:: https://quay.io/repository/biocontainers/bioconductor-rmmquant/status
   :target: https://quay.io/repository/biocontainers/bioconductor-rmmquant
.. _`bioconductor-rmmquant/tags`: https://quay.io/repository/biocontainers/bioconductor-rmmquant?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-rmmquant/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-rmmquant/README.html