:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-enrichedheatmap'
.. highlight: bash

bioconductor-enrichedheatmap
============================

.. conda:recipe:: bioconductor-enrichedheatmap
   :replaces_section_title:

   Enriched heatmap is a special type of heatmap which visualizes the enrichment of genomic signals on specific target regions. Here we implement enriched heatmap by ComplexHeatmap package. Since this type of heatmap is just a normal heatmap but with some special settings\, with the functionality of ComplexHeatmap\, it would be much easier to customize the heatmap as well as concatenating to a list of heatmaps to show correspondance between different data sources.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/EnrichedHeatmap.html
   :license: MIT + file LICENSE
   :recipe: /`bioconductor-enrichedheatmap <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-enrichedheatmap>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-enrichedheatmap/meta.yaml>`_

   


.. conda:package:: bioconductor-enrichedheatmap

   |downloads_bioconductor-enrichedheatmap| |docker_bioconductor-enrichedheatmap|

   :versions: 1.14.0-1, 1.12.0-0
   
   :depends bioconductor-complexheatmap: >=2.0.0,<2.1.0
   :depends bioconductor-genomicranges: >=1.36.0,<1.37.0
   :depends bioconductor-iranges: >=2.18.0,<2.19.0
   :depends libgcc-ng: >=7.3.0
   :depends libstdcxx-ng: >=7.3.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-circlize: >=0.4.5
   :depends r-getoptlong: 
   :depends r-locfit: 
   :depends r-matrixstats: 
   :depends r-rcpp: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-enrichedheatmap

   and update with::

      conda update bioconductor-enrichedheatmap

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-enrichedheatmap:<tag>

   (see `bioconductor-enrichedheatmap/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-enrichedheatmap| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-enrichedheatmap.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-enrichedheatmap
   :alt:   (downloads)
.. |docker_bioconductor-enrichedheatmap| image:: https://quay.io/repository/biocontainers/bioconductor-enrichedheatmap/status
   :target: https://quay.io/repository/biocontainers/bioconductor-enrichedheatmap
.. _`bioconductor-enrichedheatmap/tags`: https://quay.io/repository/biocontainers/bioconductor-enrichedheatmap?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-enrichedheatmap/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-enrichedheatmap/README.html