:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-restfulse'
.. highlight: bash

bioconductor-restfulse
======================

.. conda:recipe:: bioconductor-restfulse
   :replaces_section_title:

   This package provides functions and classes to interface with remote data stores by operating on SummarizedExperiment\-like objects.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/restfulSE.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-restfulse <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-restfulse>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-restfulse/meta.yaml>`_

   


.. conda:package:: bioconductor-restfulse

   |downloads_bioconductor-restfulse| |docker_bioconductor-restfulse|

   :versions: 1.6.0-1, 1.4.0-0
   
   :depends bioconductor-annotationdbi: >=1.46.0,<1.47.0
   :depends bioconductor-annotationhub: >=2.16.0,<2.17.0
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends bioconductor-delayedarray: >=0.10.0,<0.11.0
   :depends bioconductor-experimenthub: >=1.10.0,<1.11.0
   :depends bioconductor-go.db: >=3.8.0,<3.9.0
   :depends bioconductor-rhdf5client: >=1.6.0,<1.7.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends bioconductor-summarizedexperiment: >=1.14.0,<1.15.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-bigrquery: 
   :depends r-dbi: 
   :depends r-dplyr: >=0.7.1
   :depends r-magrittr: 
   :depends r-reshape2: 
   :depends r-rlang: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-restfulse

   and update with::

      conda update bioconductor-restfulse

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-restfulse:<tag>

   (see `bioconductor-restfulse/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-restfulse| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-restfulse.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-restfulse
   :alt:   (downloads)
.. |docker_bioconductor-restfulse| image:: https://quay.io/repository/biocontainers/bioconductor-restfulse/status
   :target: https://quay.io/repository/biocontainers/bioconductor-restfulse
.. _`bioconductor-restfulse/tags`: https://quay.io/repository/biocontainers/bioconductor-restfulse?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-restfulse/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-restfulse/README.html