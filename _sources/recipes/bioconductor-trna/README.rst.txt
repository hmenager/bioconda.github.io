:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-trna'
.. highlight: bash

bioconductor-trna
=================

.. conda:recipe:: bioconductor-trna
   :replaces_section_title:

   The tRNA package allows tRNA sequences and structures to be accessed and used for subsetting. In addition\, it provides visualization tools to compare feature parameters of multiple tRNA sets and correlate them to additional data. The tRNA package uses GRanges objects as inputs requiring only few additional column data sets.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/tRNA.html
   :license: GPL-3 + file LICENSE
   :recipe: /`bioconductor-trna <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-trna>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-trna/meta.yaml>`_

   


.. conda:package:: bioconductor-trna

   |downloads_bioconductor-trna| |docker_bioconductor-trna|

   :versions: 1.2.2-0, 1.0.0-0
   
   :depends bioconductor-biocgenerics: >=0.30.0,<0.31.0
   :depends bioconductor-biostrings: >=2.52.0,<2.53.0
   :depends bioconductor-genomicranges: >=1.36.0,<1.37.0
   :depends bioconductor-iranges: >=2.18.0,<2.19.0
   :depends bioconductor-modstrings: >=1.0.0,<1.1.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends bioconductor-structstrings: >=1.0.0,<1.1.0
   :depends bioconductor-xvector: >=0.24.0,<0.25.0
   :depends r-assertive: 
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-ggplot2: 
   :depends r-scales: 
   :depends r-stringr: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-trna

   and update with::

      conda update bioconductor-trna

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-trna:<tag>

   (see `bioconductor-trna/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-trna| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-trna.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-trna
   :alt:   (downloads)
.. |docker_bioconductor-trna| image:: https://quay.io/repository/biocontainers/bioconductor-trna/status
   :target: https://quay.io/repository/biocontainers/bioconductor-trna
.. _`bioconductor-trna/tags`: https://quay.io/repository/biocontainers/bioconductor-trna?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-trna/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-trna/README.html