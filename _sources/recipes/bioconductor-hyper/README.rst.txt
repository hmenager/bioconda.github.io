:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-hyper'
.. highlight: bash

bioconductor-hyper
==================

.. conda:recipe:: bioconductor-hyper
   :replaces_section_title:

   Geneset enrichment analysis based on hyper\-geometric test.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/hypeR.html
   :license: GPL-3 + file LICENSE
   :recipe: /`bioconductor-hyper <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-hyper>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-hyper/meta.yaml>`_

   


.. conda:package:: bioconductor-hyper

   |downloads_bioconductor-hyper| |docker_bioconductor-hyper|

   :versions: 1.00.0-1
   
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-dplyr: 
   :depends r-dt: 
   :depends r-magrittr: 
   :depends r-msigdbr: 
   :depends r-openxlsx: 
   :depends r-plotly: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-hyper

   and update with::

      conda update bioconductor-hyper

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-hyper:<tag>

   (see `bioconductor-hyper/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-hyper| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-hyper.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-hyper
   :alt:   (downloads)
.. |docker_bioconductor-hyper| image:: https://quay.io/repository/biocontainers/bioconductor-hyper/status
   :target: https://quay.io/repository/biocontainers/bioconductor-hyper
.. _`bioconductor-hyper/tags`: https://quay.io/repository/biocontainers/bioconductor-hyper?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-hyper/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-hyper/README.html