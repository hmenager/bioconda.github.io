:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-derfinderplot'
.. highlight: bash

bioconductor-derfinderplot
==========================

.. conda:recipe:: bioconductor-derfinderplot
   :replaces_section_title:

   This package provides plotting functions for results from the derfinder package.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/derfinderPlot.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-derfinderplot <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-derfinderplot>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-derfinderplot/meta.yaml>`_
   :links: biotools: :biotools:`derfinderplot`

   


.. conda:package:: bioconductor-derfinderplot

   |downloads_bioconductor-derfinderplot| |docker_bioconductor-derfinderplot|

   :versions: 1.18.1-0, 1.16.1-0, 1.14.0-0, 1.12.0-0
   
   :depends bioconductor-derfinder: >=1.18.0,<1.19.0
   :depends bioconductor-genomeinfodb: >=1.20.0,<1.21.0
   :depends bioconductor-genomicfeatures: >=1.36.0,<1.37.0
   :depends bioconductor-genomicranges: >=1.36.0,<1.37.0
   :depends bioconductor-ggbio: >=1.32.0,<1.33.0
   :depends bioconductor-iranges: >=2.18.0,<2.19.0
   :depends bioconductor-limma: >=3.40.0,<3.41.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-ggplot2: 
   :depends r-plyr: 
   :depends r-rcolorbrewer: 
   :depends r-refmanager: 
   :depends r-reshape2: 
   :depends r-scales: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-derfinderplot

   and update with::

      conda update bioconductor-derfinderplot

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-derfinderplot:<tag>

   (see `bioconductor-derfinderplot/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-derfinderplot| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-derfinderplot.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-derfinderplot
   :alt:   (downloads)
.. |docker_bioconductor-derfinderplot| image:: https://quay.io/repository/biocontainers/bioconductor-derfinderplot/status
   :target: https://quay.io/repository/biocontainers/bioconductor-derfinderplot
.. _`bioconductor-derfinderplot/tags`: https://quay.io/repository/biocontainers/bioconductor-derfinderplot?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-derfinderplot/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-derfinderplot/README.html