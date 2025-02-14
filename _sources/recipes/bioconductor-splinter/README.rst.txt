:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-splinter'
.. highlight: bash

bioconductor-splinter
=====================

.. conda:recipe:: bioconductor-splinter
   :replaces_section_title:

   SPLINTER provides tools to analyze alternative splicing sites\, interpret outcomes based on sequence information\, select and design primers for site validiation and give visual representation of the event to guide downstream experiments.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/SPLINTER.html
   :license: GPL-2
   :recipe: /`bioconductor-splinter <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-splinter>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-splinter/meta.yaml>`_
   :links: biotools: :biotools:`splinter`, doi: :doi:`10.1038/nmeth.3252`

   


.. conda:package:: bioconductor-splinter

   |downloads_bioconductor-splinter| |docker_bioconductor-splinter|

   :versions: 1.10.0-1, 1.8.0-0, 1.6.0-0, 1.4.0-0, 1.2.0-0
   
   :depends bioconductor-biomart: >=2.40.0,<2.41.0
   :depends bioconductor-biostrings: >=2.52.0,<2.53.0
   :depends bioconductor-bsgenome.mmusculus.ucsc.mm9: >=1.4.0,<1.5.0
   :depends bioconductor-genomeinfodb: >=1.20.0,<1.21.0
   :depends bioconductor-genomicalignments: >=1.20.0,<1.21.0
   :depends bioconductor-genomicfeatures: >=1.36.0,<1.37.0
   :depends bioconductor-genomicranges: >=1.36.0,<1.37.0
   :depends bioconductor-gviz: >=1.28.0,<1.29.0
   :depends bioconductor-iranges: >=2.18.0,<2.19.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends bioconductor-seqlogo: >=1.50.0,<1.51.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-ggplot2: 
   :depends r-googlevis: 
   :depends r-plyr: 
   :depends r-stringr: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-splinter

   and update with::

      conda update bioconductor-splinter

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-splinter:<tag>

   (see `bioconductor-splinter/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-splinter| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-splinter.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-splinter
   :alt:   (downloads)
.. |docker_bioconductor-splinter| image:: https://quay.io/repository/biocontainers/bioconductor-splinter/status
   :target: https://quay.io/repository/biocontainers/bioconductor-splinter
.. _`bioconductor-splinter/tags`: https://quay.io/repository/biocontainers/bioconductor-splinter?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-splinter/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-splinter/README.html