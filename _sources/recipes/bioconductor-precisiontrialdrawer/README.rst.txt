:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-precisiontrialdrawer'
.. highlight: bash

bioconductor-precisiontrialdrawer
=================================

.. conda:recipe:: bioconductor-precisiontrialdrawer
   :replaces_section_title:

   A suite of methods to design umbrella and basket trials for preision oncology.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/PrecisionTrialDrawer.html
   :license: GPL-3
   :recipe: /`bioconductor-precisiontrialdrawer <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-precisiontrialdrawer>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-precisiontrialdrawer/meta.yaml>`_

   


.. conda:package:: bioconductor-precisiontrialdrawer

   |downloads_bioconductor-precisiontrialdrawer| |docker_bioconductor-precisiontrialdrawer|

   :versions: 1.0.1-0
   
   :depends bioconductor-biocparallel: >=1.18.0,<1.19.0
   :depends bioconductor-biomart: >=2.40.0,<2.41.0
   :depends bioconductor-genomicranges: >=1.36.0,<1.37.0
   :depends bioconductor-iranges: >=2.18.0,<2.19.0
   :depends bioconductor-lowmacaannotation: >=0.99.0,<0.100.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-brglm: 
   :depends r-cgdsr: 
   :depends r-data.table: 
   :depends r-dt: 
   :depends r-ggplot2: 
   :depends r-ggrepel: 
   :depends r-googlevis: 
   :depends r-httr: 
   :depends r-jsonlite: 
   :depends r-magrittr: 
   :depends r-matrixstats: 
   :depends r-rcolorbrewer: 
   :depends r-reshape2: 
   :depends r-shiny: 
   :depends r-shinybs: 
   :depends r-stringr: 
   :depends r-xml: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-precisiontrialdrawer

   and update with::

      conda update bioconductor-precisiontrialdrawer

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-precisiontrialdrawer:<tag>

   (see `bioconductor-precisiontrialdrawer/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-precisiontrialdrawer| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-precisiontrialdrawer.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-precisiontrialdrawer
   :alt:   (downloads)
.. |docker_bioconductor-precisiontrialdrawer| image:: https://quay.io/repository/biocontainers/bioconductor-precisiontrialdrawer/status
   :target: https://quay.io/repository/biocontainers/bioconductor-precisiontrialdrawer
.. _`bioconductor-precisiontrialdrawer/tags`: https://quay.io/repository/biocontainers/bioconductor-precisiontrialdrawer?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-precisiontrialdrawer/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-precisiontrialdrawer/README.html