:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-oligo'
.. highlight: bash

bioconductor-oligo
==================

.. conda:recipe:: bioconductor-oligo
   :replaces_section_title:

   A package to analyze oligonucleotide arrays \(expression\/SNP\/tiling\/exon\) at probe\-level. It currently supports Affymetrix \(CEL files\) and NimbleGen arrays \(XYS files\).

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/oligo.html
   :license: LGPL (>= 2)
   :recipe: /`bioconductor-oligo <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-oligo>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-oligo/meta.yaml>`_
   :links: biotools: :biotools:`oligo`

   


.. conda:package:: bioconductor-oligo

   |downloads_bioconductor-oligo| |docker_bioconductor-oligo|

   :versions: 1.48.0-1, 1.46.0-0, 1.44.0-0, 1.42.0-0, 1.40.2-0, 1.40.1-0
   
   :depends bioconductor-affxparser: >=1.56.0,<1.57.0
   :depends bioconductor-affyio: >=1.54.0,<1.55.0
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends bioconductor-biocgenerics: >=0.30.0,<0.31.0
   :depends bioconductor-biostrings: >=2.52.0,<2.53.0
   :depends bioconductor-oligoclasses: >=1.46.0,<1.47.0
   :depends bioconductor-preprocesscore: >=1.46.0,<1.47.0
   :depends bioconductor-zlibbioc: >=1.30.0,<1.31.0
   :depends libgcc-ng: >=7.3.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-dbi: >=0.3.1
   :depends r-ff: 
   :depends r-rsqlite: >=1.0.0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-oligo

   and update with::

      conda update bioconductor-oligo

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-oligo:<tag>

   (see `bioconductor-oligo/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-oligo| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-oligo.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-oligo
   :alt:   (downloads)
.. |docker_bioconductor-oligo| image:: https://quay.io/repository/biocontainers/bioconductor-oligo/status
   :target: https://quay.io/repository/biocontainers/bioconductor-oligo
.. _`bioconductor-oligo/tags`: https://quay.io/repository/biocontainers/bioconductor-oligo?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-oligo/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-oligo/README.html