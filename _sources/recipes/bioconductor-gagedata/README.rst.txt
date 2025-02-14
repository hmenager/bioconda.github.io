:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-gagedata'
.. highlight: bash

bioconductor-gagedata
=====================

.. conda:recipe:: bioconductor-gagedata
   :replaces_section_title:

   This is a supportive data package for the software package\, gage. However\, the data supplied here are also useful for gene set or pathway analysis or microarray data analysis in general. In this package\, we provide two demo microarray dataset\: GSE16873 \(a breast cancer dataset from GEO\) and BMP6 \(originally published as an demo dataset for GAGE\, also registered as GSE13604 in GEO\). This package also includes commonly used gene set data based on KEGG pathways and GO terms for major research species\, including human\, mouse\, rat and budding yeast. Mapping data between common gene IDs for budding yeast are also included.

   :homepage: https://bioconductor.org/packages/3.9/data/experiment/html/gageData.html
   :license: GPL (>=2.0)
   :recipe: /`bioconductor-gagedata <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-gagedata>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-gagedata/meta.yaml>`_

   


.. conda:package:: bioconductor-gagedata

   |downloads_bioconductor-gagedata| |docker_bioconductor-gagedata|

   :versions: 2.22.0-1, 2.22.0-0, 2.20.0-0, 2.18.0-0, 2.16.0-1, 2.16.0-0, 2.14.0-0, 2.10.0-0, 2.8.0-0
   
   :depends curl: >=7.65.2,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-gagedata

   and update with::

      conda update bioconductor-gagedata

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-gagedata:<tag>

   (see `bioconductor-gagedata/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-gagedata| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-gagedata.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-gagedata
   :alt:   (downloads)
.. |docker_bioconductor-gagedata| image:: https://quay.io/repository/biocontainers/bioconductor-gagedata/status
   :target: https://quay.io/repository/biocontainers/bioconductor-gagedata
.. _`bioconductor-gagedata/tags`: https://quay.io/repository/biocontainers/bioconductor-gagedata?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-gagedata/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-gagedata/README.html