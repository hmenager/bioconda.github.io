:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-rnaprobr'
.. highlight: bash

bioconductor-rnaprobr
=====================

.. conda:recipe:: bioconductor-rnaprobr
   :replaces_section_title:

   This package facilitates analysis of Next Generation Sequencing data for which positional information with a single nucleotide resolution is a key. It allows for applying different types of relevant normalizations\, data visualization and export in a table or UCSC compatible bedgraph file.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/RNAprobR.html
   :license: GPL (>=2)
   :recipe: /`bioconductor-rnaprobr <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-rnaprobr>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-rnaprobr/meta.yaml>`_
   :links: biotools: :biotools:`rnaprobr`

   


.. conda:package:: bioconductor-rnaprobr

   |downloads_bioconductor-rnaprobr| |docker_bioconductor-rnaprobr|

   :versions: 1.16.0-1, 1.14.0-0, 1.12.0-0, 1.9.0-0, 1.8.0-0
   
   :depends bioconductor-biocgenerics: >=0.30.0,<0.31.0
   :depends bioconductor-biostrings: >=2.52.0,<2.53.0
   :depends bioconductor-genomicalignments: >=1.20.0,<1.21.0
   :depends bioconductor-genomicfeatures: >=1.36.0,<1.37.0
   :depends bioconductor-genomicranges: >=1.36.0,<1.37.0
   :depends bioconductor-iranges: >=2.18.0,<2.19.0
   :depends bioconductor-rsamtools: >=2.0.0,<2.1.0
   :depends bioconductor-rtracklayer: >=1.44.0,<1.45.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-plyr: >=1.8.1
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-rnaprobr

   and update with::

      conda update bioconductor-rnaprobr

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-rnaprobr:<tag>

   (see `bioconductor-rnaprobr/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-rnaprobr| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-rnaprobr.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-rnaprobr
   :alt:   (downloads)
.. |docker_bioconductor-rnaprobr| image:: https://quay.io/repository/biocontainers/bioconductor-rnaprobr/status
   :target: https://quay.io/repository/biocontainers/bioconductor-rnaprobr
.. _`bioconductor-rnaprobr/tags`: https://quay.io/repository/biocontainers/bioconductor-rnaprobr?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-rnaprobr/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-rnaprobr/README.html