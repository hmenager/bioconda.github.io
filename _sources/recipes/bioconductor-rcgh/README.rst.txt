:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-rcgh'
.. highlight: bash

bioconductor-rcgh
=================

.. conda:recipe:: bioconductor-rcgh
   :replaces_section_title:

   A comprehensive pipeline for analyzing and interactively visualizing genomic profiles generated through commercial or custom aCGH arrays. As inputs\, rCGH supports Agilent dual\-color Feature Extraction files \(.txt\)\, from 44 to 400K\, Affymetrix SNP6.0 and cytoScanHD probeset.txt\, cychp.txt\, and cnchp.txt files exported from ChAS or Affymetrix Power Tools. rCGH also supports custom arrays\, provided data complies with the expected format. This package takes over all the steps required for individual genomic profiles analysis\, from reading files to profiles segmentation and gene annotations. This package also provides several visualization functions \(static or interactive\) which facilitate individual profiles interpretation. Input files can be in compressed format\, e.g. .bz2 or .gz.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/rCGH.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-rcgh <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-rcgh>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-rcgh/meta.yaml>`_
   :links: biotools: :biotools:`rcgh`, doi: :doi:`10.1093/bioinformatics/btv718`

   


.. conda:package:: bioconductor-rcgh

   |downloads_bioconductor-rcgh| |docker_bioconductor-rcgh|

   :versions: 1.14.0-1, 1.12.0-0, 1.10.0-0, 1.8.1-0
   
   :depends bioconductor-acgh: >=1.62.0,<1.63.0
   :depends bioconductor-affy: >=1.62.0,<1.63.0
   :depends bioconductor-annotationdbi: >=1.46.0,<1.47.0
   :depends bioconductor-dnacopy: >=1.58.0,<1.59.0
   :depends bioconductor-genomeinfodb: >=1.20.0,<1.21.0
   :depends bioconductor-genomicfeatures: >=1.36.0,<1.37.0
   :depends bioconductor-genomicranges: >=1.36.0,<1.37.0
   :depends bioconductor-iranges: >=2.18.0,<2.19.0
   :depends bioconductor-limma: >=3.40.0,<3.41.0
   :depends bioconductor-org.hs.eg.db: >=3.8.0,<3.9.0
   :depends bioconductor-txdb.hsapiens.ucsc.hg18.knowngene: >=3.2.0,<3.3.0
   :depends bioconductor-txdb.hsapiens.ucsc.hg19.knowngene: >=3.2.0,<3.3.0
   :depends bioconductor-txdb.hsapiens.ucsc.hg38.knowngene: >=3.4.0,<3.5.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-ggplot2: 
   :depends r-lattice: 
   :depends r-mclust: 
   :depends r-plyr: 
   :depends r-shiny: >=0.11.1
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-rcgh

   and update with::

      conda update bioconductor-rcgh

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-rcgh:<tag>

   (see `bioconductor-rcgh/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-rcgh| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-rcgh.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-rcgh
   :alt:   (downloads)
.. |docker_bioconductor-rcgh| image:: https://quay.io/repository/biocontainers/bioconductor-rcgh/status
   :target: https://quay.io/repository/biocontainers/bioconductor-rcgh
.. _`bioconductor-rcgh/tags`: https://quay.io/repository/biocontainers/bioconductor-rcgh?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-rcgh/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-rcgh/README.html