:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-gsva'
.. highlight: bash

bioconductor-gsva
=================

.. conda:recipe:: bioconductor-gsva
   :replaces_section_title:

   Gene Set Variation Analysis \(GSVA\) is a non\-parametric\, unsupervised method for estimating variation of gene set enrichment through the samples of a expression data set. GSVA performs a change in coordinate systems\, transforming the data from a gene by sample matrix to a gene\-set by sample matrix\, thereby allowing the evaluation of pathway enrichment for each sample. This new matrix of GSVA enrichment scores facilitates applying standard analytical methods like functional enrichment\, survival analysis\, clustering\, CNV\-pathway analysis or cross\-tissue pathway analysis\, in a pathway\-centric manner.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/GSVA.html
   :license: GPL (>= 2)
   :recipe: /`bioconductor-gsva <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-gsva>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-gsva/meta.yaml>`_
   :links: biotools: :biotools:`gsva`

   


.. conda:package:: bioconductor-gsva

   |downloads_bioconductor-gsva| |docker_bioconductor-gsva|

   :versions: 1.32.0-1, 1.30.0-1, 1.30.0-0, 1.28.0-0, 1.26.0-0, 1.24.2-0, 1.24.1-0
   
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends bioconductor-biocgenerics: >=0.30.0,<0.31.0
   :depends bioconductor-geneplotter: >=1.62.0,<1.63.0
   :depends bioconductor-gseabase: >=1.46.0,<1.47.0
   :depends libgcc-ng: >=7.3.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-shiny: 
   :depends r-shinythemes: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-gsva

   and update with::

      conda update bioconductor-gsva

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-gsva:<tag>

   (see `bioconductor-gsva/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-gsva| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-gsva.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-gsva
   :alt:   (downloads)
.. |docker_bioconductor-gsva| image:: https://quay.io/repository/biocontainers/bioconductor-gsva/status
   :target: https://quay.io/repository/biocontainers/bioconductor-gsva
.. _`bioconductor-gsva/tags`: https://quay.io/repository/biocontainers/bioconductor-gsva?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-gsva/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-gsva/README.html