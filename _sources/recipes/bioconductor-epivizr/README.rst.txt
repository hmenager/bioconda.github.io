:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-epivizr'
.. highlight: bash

bioconductor-epivizr
====================

.. conda:recipe:: bioconductor-epivizr
   :replaces_section_title:

   This package provides connections to the epiviz web app \(http\:\/\/epiviz.cbcb.umd.edu\) for interactive visualization of genomic data. Objects in R\/bioc interactive sessions can be displayed in genome browser tracks or plots to be explored by navigation through genomic regions. Fundamental Bioconductor data structures are supported \(e.g.\, GenomicRanges and RangedSummarizedExperiment objects\)\, while providing an easy mechanism to support other data structures \(through package epivizrData\). Visualizations \(using d3.js\) can be easily added to the web app as well.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/epivizr.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-epivizr <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-epivizr>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-epivizr/meta.yaml>`_
   :links: biotools: :biotools:`epivizr`, doi: :doi:`10.1038/nmeth.3038`

   


.. conda:package:: bioconductor-epivizr

   |downloads_bioconductor-epivizr| |docker_bioconductor-epivizr|

   :versions: 2.14.0-1, 2.12.0-0, 2.10.0-0, 2.8.0-0
   
   :depends bioconductor-epivizrdata: >=1.12.0,<1.13.0
   :depends bioconductor-epivizrserver: >=1.12.0,<1.13.0
   :depends bioconductor-genomicranges: >=1.36.0,<1.37.0
   :depends bioconductor-iranges: >=2.18.0,<2.19.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-epivizr

   and update with::

      conda update bioconductor-epivizr

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-epivizr:<tag>

   (see `bioconductor-epivizr/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-epivizr| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-epivizr.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-epivizr
   :alt:   (downloads)
.. |docker_bioconductor-epivizr| image:: https://quay.io/repository/biocontainers/bioconductor-epivizr/status
   :target: https://quay.io/repository/biocontainers/bioconductor-epivizr
.. _`bioconductor-epivizr/tags`: https://quay.io/repository/biocontainers/bioconductor-epivizr?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-epivizr/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-epivizr/README.html