:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-bitseq'
.. highlight: bash

bioconductor-bitseq
===================

.. conda:recipe:: bioconductor-bitseq
   :replaces_section_title:

   The BitSeq package is targeted for transcript expression analysis and differential expression analysis of RNA\-seq data in two stage process. In the first stage it uses Bayesian inference methodology to infer expression of individual transcripts from individual RNA\-seq experiments. The second stage of BitSeq embraces the differential expression analysis of transcript expression. Providing expression estimates from replicates of multiple conditions\, Log\-Normal model of the estimates is used for inferring the condition mean transcript expression and ranking the transcripts based on the likelihood of differential expression.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/BitSeq.html
   :license: Artistic-2.0 + file LICENSE
   :recipe: /`bioconductor-bitseq <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-bitseq>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-bitseq/meta.yaml>`_
   :links: biotools: :biotools:`bitseq`

   


.. conda:package:: bioconductor-bitseq

   |downloads_bioconductor-bitseq| |docker_bioconductor-bitseq|

   :versions: 1.28.0-1, 1.26.0-0, 1.24.0-0, 1.22.0-0, 1.20.0-0
   
   :depends bioconductor-iranges: >=2.18.0,<2.19.0
   :depends bioconductor-rhtslib: >=1.16.0,<1.17.0
   :depends bioconductor-rsamtools: >=2.0.0,<2.1.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends libgcc-ng: >=7.3.0
   :depends libstdcxx-ng: >=7.3.0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-bitseq

   and update with::

      conda update bioconductor-bitseq

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-bitseq:<tag>

   (see `bioconductor-bitseq/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-bitseq| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-bitseq.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-bitseq
   :alt:   (downloads)
.. |docker_bioconductor-bitseq| image:: https://quay.io/repository/biocontainers/bioconductor-bitseq/status
   :target: https://quay.io/repository/biocontainers/bioconductor-bitseq
.. _`bioconductor-bitseq/tags`: https://quay.io/repository/biocontainers/bioconductor-bitseq?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-bitseq/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-bitseq/README.html