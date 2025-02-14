:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-sangerseqr'
.. highlight: bash

bioconductor-sangerseqr
=======================

.. conda:recipe:: bioconductor-sangerseqr
   :replaces_section_title:

   This package contains several tools for analyzing Sanger Sequencing data files in R\, including reading .scf and .ab1 files\, making basecalls and plotting chromatograms.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/sangerseqR.html
   :license: GPL-2
   :recipe: /`bioconductor-sangerseqr <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-sangerseqr>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-sangerseqr/meta.yaml>`_
   :links: biotools: :biotools:`sangerseqr`

   


.. conda:package:: bioconductor-sangerseqr

   |downloads_bioconductor-sangerseqr| |docker_bioconductor-sangerseqr|

   :versions: 1.20.0-1, 1.18.0-0, 1.16.0-0, 1.14.0-0, 1.12.0-0
   
   :depends bioconductor-biostrings: >=2.52.0,<2.53.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-shiny: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-sangerseqr

   and update with::

      conda update bioconductor-sangerseqr

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-sangerseqr:<tag>

   (see `bioconductor-sangerseqr/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-sangerseqr| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-sangerseqr.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-sangerseqr
   :alt:   (downloads)
.. |docker_bioconductor-sangerseqr| image:: https://quay.io/repository/biocontainers/bioconductor-sangerseqr/status
   :target: https://quay.io/repository/biocontainers/bioconductor-sangerseqr
.. _`bioconductor-sangerseqr/tags`: https://quay.io/repository/biocontainers/bioconductor-sangerseqr?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-sangerseqr/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-sangerseqr/README.html