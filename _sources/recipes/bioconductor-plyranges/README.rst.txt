:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-plyranges'
.. highlight: bash

bioconductor-plyranges
======================

.. conda:recipe:: bioconductor-plyranges
   :replaces_section_title:

   A dplyr\-like interface for interacting with the common Bioconductor classes Ranges and GenomicRanges. By providing a grammatical and consistent way of manipulating these classes their accessiblity for new Bioconductor users is hopefully increased.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/plyranges.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-plyranges <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-plyranges>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-plyranges/meta.yaml>`_

   


.. conda:package:: bioconductor-plyranges

   |downloads_bioconductor-plyranges| |docker_bioconductor-plyranges|

   :versions: 1.4.3-0, 1.2.0-0
   
   :depends bioconductor-biocgenerics: >=0.30.0,<0.31.0
   :depends bioconductor-genomeinfodb: >=1.20.0,<1.21.0
   :depends bioconductor-genomicalignments: >=1.20.0,<1.21.0
   :depends bioconductor-genomicranges: >=1.36.0,<1.37.0
   :depends bioconductor-iranges: >=2.18.0,<2.19.0
   :depends bioconductor-rsamtools: >=2.0.0,<2.1.0
   :depends bioconductor-rtracklayer: >=1.44.0,<1.45.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-dplyr: 
   :depends r-magrittr: 
   :depends r-rlang: >=0.2.0
   :depends r-tidyr: 
   :depends r-tidyselect: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-plyranges

   and update with::

      conda update bioconductor-plyranges

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-plyranges:<tag>

   (see `bioconductor-plyranges/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-plyranges| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-plyranges.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-plyranges
   :alt:   (downloads)
.. |docker_bioconductor-plyranges| image:: https://quay.io/repository/biocontainers/bioconductor-plyranges/status
   :target: https://quay.io/repository/biocontainers/bioconductor-plyranges
.. _`bioconductor-plyranges/tags`: https://quay.io/repository/biocontainers/bioconductor-plyranges?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-plyranges/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-plyranges/README.html