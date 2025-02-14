:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-ldblock'
.. highlight: bash

bioconductor-ldblock
====================

.. conda:recipe:: bioconductor-ldblock
   :replaces_section_title:

   Define data structures for linkage disequilibrium measures in populations.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/ldblock.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-ldblock <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-ldblock>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-ldblock/meta.yaml>`_

   


.. conda:package:: bioconductor-ldblock

   |downloads_bioconductor-ldblock| |docker_bioconductor-ldblock|

   :versions: 1.14.0-1, 1.12.0-0
   
   :depends bioconductor-biocgenerics: >=0.30.0,<0.31.0
   :depends bioconductor-erma: >=1.0.0,<1.1.0
   :depends bioconductor-genomeinfodb: >=1.20.0,<1.21.0
   :depends bioconductor-genomicfiles: >=1.20.0,<1.21.0
   :depends bioconductor-go.db: >=3.8.0,<3.9.0
   :depends bioconductor-homo.sapiens: >=1.3.0,<1.4.0
   :depends bioconductor-rsamtools: >=2.0.0,<2.1.0
   :depends bioconductor-snpstats: >=1.34.0,<1.35.0
   :depends bioconductor-variantannotation: >=1.30.0,<1.31.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-matrix: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-ldblock

   and update with::

      conda update bioconductor-ldblock

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-ldblock:<tag>

   (see `bioconductor-ldblock/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-ldblock| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-ldblock.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-ldblock
   :alt:   (downloads)
.. |docker_bioconductor-ldblock| image:: https://quay.io/repository/biocontainers/bioconductor-ldblock/status
   :target: https://quay.io/repository/biocontainers/bioconductor-ldblock
.. _`bioconductor-ldblock/tags`: https://quay.io/repository/biocontainers/bioconductor-ldblock?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-ldblock/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-ldblock/README.html