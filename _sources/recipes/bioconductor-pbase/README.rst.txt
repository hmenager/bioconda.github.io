:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-pbase'
.. highlight: bash

bioconductor-pbase
==================

.. conda:recipe:: bioconductor-pbase
   :replaces_section_title:

   A set of classes and functions to investigate and understand protein sequence data in the context of a proteomics experiment.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/Pbase.html
   :license: GPL-3
   :recipe: /`bioconductor-pbase <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-pbase>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-pbase/meta.yaml>`_
   :links: biotools: :biotools:`pbase`, doi: :doi:`10.1002/pmic.201400392`

   


.. conda:package:: bioconductor-pbase

   |downloads_bioconductor-pbase| |docker_bioconductor-pbase|

   :versions: 0.24.0-1, 0.22.1-0, 0.22.0-0, 0.18.0-0
   
   :depends bioconductor-annotationfilter: >=1.8.0,<1.9.0
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends bioconductor-biocgenerics: >=0.30.0,<0.31.0
   :depends bioconductor-biocparallel: >=1.18.0,<1.19.0
   :depends bioconductor-biomart: >=2.40.0,<2.41.0
   :depends bioconductor-biostrings: >=2.52.0,<2.53.0
   :depends bioconductor-cleaver: >=1.22.0,<1.23.0
   :depends bioconductor-ensembldb: >=2.8.0,<2.9.0
   :depends bioconductor-genomicranges: >=1.36.0,<1.37.0
   :depends bioconductor-gviz: >=1.28.0,<1.29.0
   :depends bioconductor-iranges: >=2.18.0,<2.19.0
   :depends bioconductor-msnbase: >=2.10.0,<2.11.0
   :depends bioconductor-mzid: >=1.22.0,<1.23.0
   :depends bioconductor-mzr: >=2.18.0,<2.19.0
   :depends bioconductor-pviz: >=1.18.0,<1.19.0
   :depends bioconductor-rtracklayer: >=1.44.0,<1.45.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends libgcc-ng: >=7.3.0
   :depends libstdcxx-ng: >=7.3.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-rcpp: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-pbase

   and update with::

      conda update bioconductor-pbase

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-pbase:<tag>

   (see `bioconductor-pbase/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-pbase| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-pbase.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-pbase
   :alt:   (downloads)
.. |docker_bioconductor-pbase| image:: https://quay.io/repository/biocontainers/bioconductor-pbase/status
   :target: https://quay.io/repository/biocontainers/bioconductor-pbase
.. _`bioconductor-pbase/tags`: https://quay.io/repository/biocontainers/bioconductor-pbase?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-pbase/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-pbase/README.html