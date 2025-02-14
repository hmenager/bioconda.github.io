:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-tssi'
.. highlight: bash

bioconductor-tssi
=================

.. conda:recipe:: bioconductor-tssi
   :replaces_section_title:

   Identify and normalize transcription start sites in high\-throughput sequencing data.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/TSSi.html
   :license: GPL-3
   :recipe: /`bioconductor-tssi <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-tssi>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-tssi/meta.yaml>`_
   :links: biotools: :biotools:`tssi`, doi: :doi:`10.1093/bioinformatics/bts189`

   


.. conda:package:: bioconductor-tssi

   |downloads_bioconductor-tssi| |docker_bioconductor-tssi|

   :versions: 1.29.0-1, 1.28.0-0, 1.26.0-0, 1.24.0-0, 1.22.0-0
   
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends bioconductor-biocgenerics: >=0.30.0,<0.31.0
   :depends bioconductor-iranges: >=2.18.0,<2.19.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends libgcc-ng: >=7.3.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-hmisc: 
   :depends r-minqa: 
   :depends r-plyr: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-tssi

   and update with::

      conda update bioconductor-tssi

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-tssi:<tag>

   (see `bioconductor-tssi/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-tssi| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-tssi.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-tssi
   :alt:   (downloads)
.. |docker_bioconductor-tssi| image:: https://quay.io/repository/biocontainers/bioconductor-tssi/status
   :target: https://quay.io/repository/biocontainers/bioconductor-tssi
.. _`bioconductor-tssi/tags`: https://quay.io/repository/biocontainers/bioconductor-tssi?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-tssi/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-tssi/README.html