:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-traser'
.. highlight: bash

bioconductor-traser
===================

.. conda:recipe:: bioconductor-traser
   :replaces_section_title:

   traseR performs GWAS trait\-associated SNP enrichment analyses in genomic intervals using different hypothesis testing approaches\, also provides various functionalities to explore and visualize the results.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/traseR.html
   :license: GPL
   :recipe: /`bioconductor-traser <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-traser>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-traser/meta.yaml>`_
   :links: biotools: :biotools:`traser`, doi: :doi:`10.1093/bioinformatics/btv741`

   


.. conda:package:: bioconductor-traser

   |downloads_bioconductor-traser| |docker_bioconductor-traser|

   :versions: 1.14.0-1, 1.12.0-0, 1.10.0-0, 1.8.0-0, 1.6.0-0
   
   :depends bioconductor-bsgenome.hsapiens.ucsc.hg19: >=1.4.0,<1.5.0
   :depends bioconductor-genomicranges: >=1.36.0,<1.37.0
   :depends bioconductor-iranges: >=2.18.0,<2.19.0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-traser

   and update with::

      conda update bioconductor-traser

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-traser:<tag>

   (see `bioconductor-traser/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-traser| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-traser.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-traser
   :alt:   (downloads)
.. |docker_bioconductor-traser| image:: https://quay.io/repository/biocontainers/bioconductor-traser/status
   :target: https://quay.io/repository/biocontainers/bioconductor-traser
.. _`bioconductor-traser/tags`: https://quay.io/repository/biocontainers/bioconductor-traser?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-traser/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-traser/README.html