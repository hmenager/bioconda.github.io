:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-netboost'
.. highlight: bash

bioconductor-netboost
=====================

.. conda:recipe:: bioconductor-netboost
   :replaces_section_title:

   Boosting supported network analysis for high\-dimensional omics applications. This package comes bundled with the MC\-UPGMA clustering package by Yaniv Loewenstein.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/netboost.html
   :license: GPL-3
   :recipe: /`bioconductor-netboost <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-netboost>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-netboost/meta.yaml>`_

   


.. conda:package:: bioconductor-netboost

   |downloads_bioconductor-netboost| |docker_bioconductor-netboost|

   :versions: 1.0.0-1
   
   :depends bioconductor-impute: >=1.58.0,<1.59.0
   :depends libcxx: >=4.0.1
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-colorspace: 
   :depends r-dynamictreecut: 
   :depends r-r.utils: 
   :depends r-rcpp: 
   :depends r-rcppparallel: 
   :depends r-wgcna: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-netboost

   and update with::

      conda update bioconductor-netboost

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-netboost:<tag>

   (see `bioconductor-netboost/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-netboost| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-netboost.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-netboost
   :alt:   (downloads)
.. |docker_bioconductor-netboost| image:: https://quay.io/repository/biocontainers/bioconductor-netboost/status
   :target: https://quay.io/repository/biocontainers/bioconductor-netboost
.. _`bioconductor-netboost/tags`: https://quay.io/repository/biocontainers/bioconductor-netboost?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-netboost/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-netboost/README.html