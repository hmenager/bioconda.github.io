:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-vidger'
.. highlight: bash

bioconductor-vidger
===================

.. conda:recipe:: bioconductor-vidger
   :replaces_section_title:

   The aim of vidger is to rapidly generate information\-rich visualizations for the interpretation of differential gene expression results from three widely\-used tools\: Cuffdiff\, DESeq2\, and edgeR.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/vidger.html
   :license: GPL-3 | file LICENSE
   :recipe: /`bioconductor-vidger <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-vidger>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-vidger/meta.yaml>`_

   


.. conda:package:: bioconductor-vidger

   |downloads_bioconductor-vidger| |docker_bioconductor-vidger|

   :versions: 1.4.0-1, 1.2.0-0
   
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends bioconductor-deseq2: >=1.24.0,<1.25.0
   :depends bioconductor-edger: >=3.26.0,<3.27.0
   :depends bioconductor-summarizedexperiment: >=1.14.0,<1.15.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-ggally: 
   :depends r-ggplot2: 
   :depends r-ggrepel: 
   :depends r-knitr: 
   :depends r-rcolorbrewer: 
   :depends r-rmarkdown: 
   :depends r-scales: 
   :depends r-tidyr: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-vidger

   and update with::

      conda update bioconductor-vidger

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-vidger:<tag>

   (see `bioconductor-vidger/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-vidger| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-vidger.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-vidger
   :alt:   (downloads)
.. |docker_bioconductor-vidger| image:: https://quay.io/repository/biocontainers/bioconductor-vidger/status
   :target: https://quay.io/repository/biocontainers/bioconductor-vidger
.. _`bioconductor-vidger/tags`: https://quay.io/repository/biocontainers/bioconductor-vidger?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-vidger/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-vidger/README.html