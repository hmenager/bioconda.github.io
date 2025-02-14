:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-trigger'
.. highlight: bash

bioconductor-trigger
====================

.. conda:recipe:: bioconductor-trigger
   :replaces_section_title:

   This R package provides tools for the statistical analysis of integrative genomic data that involve some combination of\: genotypes\, high\-dimensional intermediate traits \(e.g.\, gene expression\, protein abundance\)\, and higher\-order traits \(phenotypes\). The package includes functions to\: \(1\) construct global linkage maps between genetic markers and gene expression\; \(2\) analyze multiple\-locus linkage \(epistasis\) for gene expression\; \(3\) quantify the proportion of genome\-wide variation explained by each locus and identify eQTL hotspots\; \(4\) estimate pair\-wise causal gene regulatory probabilities and construct gene regulatory networks\; and \(5\) identify causal genes for a quantitative trait of interest.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/trigger.html
   :license: GPL-3
   :recipe: /`bioconductor-trigger <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-trigger>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-trigger/meta.yaml>`_
   :links: biotools: :biotools:`trigger`, doi: :doi:`10.1038/nmeth.3252`

   


.. conda:package:: bioconductor-trigger

   |downloads_bioconductor-trigger| |docker_bioconductor-trigger|

   :versions: 1.30.0-1, 1.28.0-0, 1.26.0-0, 1.24.0-0
   
   :depends bioconductor-qvalue: >=2.16.0,<2.17.0
   :depends bioconductor-sva: >=3.32.0,<3.33.0
   :depends libgcc-ng: >=7.3.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-corpcor: 
   :depends r-qtl: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-trigger

   and update with::

      conda update bioconductor-trigger

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-trigger:<tag>

   (see `bioconductor-trigger/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-trigger| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-trigger.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-trigger
   :alt:   (downloads)
.. |docker_bioconductor-trigger| image:: https://quay.io/repository/biocontainers/bioconductor-trigger/status
   :target: https://quay.io/repository/biocontainers/bioconductor-trigger
.. _`bioconductor-trigger/tags`: https://quay.io/repository/biocontainers/bioconductor-trigger?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-trigger/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-trigger/README.html