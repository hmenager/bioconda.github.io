:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-cocoa'
.. highlight: bash

bioconductor-cocoa
==================

.. conda:recipe:: bioconductor-cocoa
   :replaces_section_title:

   COCOA is a method for understanding variation among samples and can be used with data that includes genomic coordinates such as DNA methylation. On a high level\, COCOA uses a database of \"region sets\" and principal component analysis \(PCA\) of your data to identify sources of variation among samples. A region set is a set of genomic regions that share a biological annotation\, for instance\, transcription factor binding regions\, histone modification regions\, or open chromatin regions. COCOA works in both supervised \(known groups of samples\) and unsupervised \(no groups\) situations and can be used as a complement to \"differential\" methods that find discrete differences between groups. COCOA can identify biologically meaningful sources of variation between samples and increase understanding of variation in your data.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/COCOA.html
   :license: GPL-3
   :recipe: /`bioconductor-cocoa <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-cocoa>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-cocoa/meta.yaml>`_

   


.. conda:package:: bioconductor-cocoa

   |downloads_bioconductor-cocoa| |docker_bioconductor-cocoa|

   :versions: 1.2.0-1, 1.0.1-0
   
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends bioconductor-biocgenerics: >=0.30.0,<0.31.0
   :depends bioconductor-complexheatmap: >=2.0.0,<2.1.0
   :depends bioconductor-genomicranges: >=1.36.0,<1.37.0
   :depends bioconductor-iranges: >=2.18.0,<2.19.0
   :depends bioconductor-mira: >=1.6.0,<1.7.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-data.table: 
   :depends r-ggplot2: 
   :depends r-tidyr: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-cocoa

   and update with::

      conda update bioconductor-cocoa

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-cocoa:<tag>

   (see `bioconductor-cocoa/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-cocoa| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-cocoa.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-cocoa
   :alt:   (downloads)
.. |docker_bioconductor-cocoa| image:: https://quay.io/repository/biocontainers/bioconductor-cocoa/status
   :target: https://quay.io/repository/biocontainers/bioconductor-cocoa
.. _`bioconductor-cocoa/tags`: https://quay.io/repository/biocontainers/bioconductor-cocoa?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-cocoa/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-cocoa/README.html