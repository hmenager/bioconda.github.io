:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-cola'
.. highlight: bash

bioconductor-cola
=================

.. conda:recipe:: bioconductor-cola
   :replaces_section_title:

   Subgroup classification is a basic task in genomic data analysis\, especially for gene expression data and methylation data. It can predict novel subgroups when there is nothing known about the data or it can test consistency between predicted subgroups with known annotations. The cola package provides a general framework for subgroup classification by consensus clustering. It has following features\: 1. It modularizes the consensus clustering processes that various methods can be easily integrated. 2. It provides rich visualizations for interpreting the results. 3. It allows running multiple methods at the same time and provides functionalities to compare results in a straightforward way. 4. It provides a new method to extract features which are more efficient to separate subgroups. 5. It allows doing partitioning in a hierarchical way to detect subgroups with relatively smaller difference. 6. It generates detailed reports for the complete analysis.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/cola.html
   :license: MIT + file LICENSE
   :recipe: /`bioconductor-cola <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-cola>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-cola/meta.yaml>`_

   


.. conda:package:: bioconductor-cola

   |downloads_bioconductor-cola| |docker_bioconductor-cola|

   :versions: 1.0.0-1, 1.0.0-0
   
   :depends bioconductor-complexheatmap: >=2.0.0,<2.1.0
   :depends bioconductor-impute: >=1.58.0,<1.59.0
   :depends libgcc-ng: >=7.3.0
   :depends libstdcxx-ng: >=7.3.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-brew: 
   :depends r-circlize: >=0.4.5
   :depends r-clue: 
   :depends r-cluster: 
   :depends r-crayon: 
   :depends r-digest: 
   :depends r-getoptlong: 
   :depends r-globaloptions: >=0.1.0
   :depends r-gplots: 
   :depends r-httr: 
   :depends r-knitr: 
   :depends r-markdown: 
   :depends r-matrixstats: 
   :depends r-mclust: 
   :depends r-microbenchmark: 
   :depends r-png: 
   :depends r-rcolorbrewer: 
   :depends r-rcpp: >=0.11.0
   :depends r-skmeans: 
   :depends r-xml2: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-cola

   and update with::

      conda update bioconductor-cola

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-cola:<tag>

   (see `bioconductor-cola/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-cola| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-cola.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-cola
   :alt:   (downloads)
.. |docker_bioconductor-cola| image:: https://quay.io/repository/biocontainers/bioconductor-cola/status
   :target: https://quay.io/repository/biocontainers/bioconductor-cola
.. _`bioconductor-cola/tags`: https://quay.io/repository/biocontainers/bioconductor-cola?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-cola/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-cola/README.html