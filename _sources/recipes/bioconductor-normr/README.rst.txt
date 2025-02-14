:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-normr'
.. highlight: bash

bioconductor-normr
==================

.. conda:recipe:: bioconductor-normr
   :replaces_section_title:

   Robust normalization and difference calling procedures for ChIP\-seq and alike data. Read counts are modeled jointly as a binomial mixture model with a user\-specified number of components. A fitted background estimate accounts for the effect of enrichment in certain regions and\, therefore\, represents an appropriate null hypothesis. This robust background is used to identify significantly enriched or depleted regions.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/normr.html
   :license: GPL-2
   :recipe: /`bioconductor-normr <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-normr>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-normr/meta.yaml>`_

   


.. conda:package:: bioconductor-normr

   |downloads_bioconductor-normr| |docker_bioconductor-normr|

   :versions: 1.10.0-1, 1.8.0-0
   
   :depends bioconductor-bamsignals: >=1.16.0,<1.17.0
   :depends bioconductor-genomeinfodb: >=1.20.0,<1.21.0
   :depends bioconductor-genomicranges: >=1.36.0,<1.37.0
   :depends bioconductor-iranges: >=2.18.0,<2.19.0
   :depends bioconductor-qvalue: >=2.16.0,<2.17.0
   :depends bioconductor-rtracklayer: >=1.44.0,<1.45.0
   :depends libgcc-ng: >=7.3.0
   :depends libstdcxx-ng: >=7.3.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-rcpp: >=0.11
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-normr

   and update with::

      conda update bioconductor-normr

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-normr:<tag>

   (see `bioconductor-normr/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-normr| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-normr.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-normr
   :alt:   (downloads)
.. |docker_bioconductor-normr| image:: https://quay.io/repository/biocontainers/bioconductor-normr/status
   :target: https://quay.io/repository/biocontainers/bioconductor-normr
.. _`bioconductor-normr/tags`: https://quay.io/repository/biocontainers/bioconductor-normr?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-normr/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-normr/README.html