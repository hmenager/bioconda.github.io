:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-topaseq'
.. highlight: bash

bioconductor-topaseq
====================

.. conda:recipe:: bioconductor-topaseq
   :replaces_section_title:

   Implementation of methods for topology\-based pathway analysis of RNA\-seq data. This includes Topological Analysis of Pathway Phenotype Association \(TAPPA\; Gao and Wang\, 2007\)\, PathWay Enrichment Analysis \(PWEA\; Hung et al.\, 2010\)\, and the Pathway Regulation Score \(PRS\; Ibrahim et al.\, 2012\).

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/ToPASeq.html
   :license: AGPL-3
   :recipe: /`bioconductor-topaseq <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-topaseq>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-topaseq/meta.yaml>`_

   


.. conda:package:: bioconductor-topaseq

   |downloads_bioconductor-topaseq| |docker_bioconductor-topaseq|

   :versions: 1.17.1-1, 1.16.0-0
   
   :depends bioconductor-graph: >=1.62.0,<1.63.0
   :depends bioconductor-graphite: >=1.30.0,<1.31.0
   :depends libgcc-ng: >=7.3.0
   :depends libstdcxx-ng: >=7.3.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-rcpp: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-topaseq

   and update with::

      conda update bioconductor-topaseq

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-topaseq:<tag>

   (see `bioconductor-topaseq/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-topaseq| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-topaseq.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-topaseq
   :alt:   (downloads)
.. |docker_bioconductor-topaseq| image:: https://quay.io/repository/biocontainers/bioconductor-topaseq/status
   :target: https://quay.io/repository/biocontainers/bioconductor-topaseq
.. _`bioconductor-topaseq/tags`: https://quay.io/repository/biocontainers/bioconductor-topaseq?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-topaseq/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-topaseq/README.html