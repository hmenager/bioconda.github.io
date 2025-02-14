:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-ebimage'
.. highlight: bash

bioconductor-ebimage
====================

.. conda:recipe:: bioconductor-ebimage
   :replaces_section_title:

   EBImage provides general purpose functionality for image processing and analysis. In the context of \(high\-throughput\) microscopy\-based cellular assays\, EBImage offers tools to segment cells and extract quantitative cellular descriptors. This allows the automation of such tasks using the R programming language and facilitates the use of other tools in the R environment for signal processing\, statistical modeling\, machine learning and visualization with image data.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/EBImage.html
   :license: LGPL
   :recipe: /`bioconductor-ebimage <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-ebimage>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-ebimage/meta.yaml>`_
   :links: biotools: :biotools:`ebimage`

   


.. conda:package:: bioconductor-ebimage

   |downloads_bioconductor-ebimage| |docker_bioconductor-ebimage|

   :versions: 4.26.0-1, 4.24.0-0, 4.22.1-0, 4.20.0-0, 4.18.3-0, 4.13.0-0, 4.12.2-0
   
   :depends bioconductor-biocgenerics: >=0.30.0,<0.31.0
   :depends libgcc-ng: >=7.3.0
   :depends libstdcxx-ng: >=7.3.0
   :depends r-abind: 
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-fftwtools: >=0.9-7
   :depends r-htmltools: 
   :depends r-htmlwidgets: 
   :depends r-jpeg: 
   :depends r-locfit: 
   :depends r-png: 
   :depends r-rcurl: 
   :depends r-tiff: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-ebimage

   and update with::

      conda update bioconductor-ebimage

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-ebimage:<tag>

   (see `bioconductor-ebimage/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-ebimage| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-ebimage.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-ebimage
   :alt:   (downloads)
.. |docker_bioconductor-ebimage| image:: https://quay.io/repository/biocontainers/bioconductor-ebimage/status
   :target: https://quay.io/repository/biocontainers/bioconductor-ebimage
.. _`bioconductor-ebimage/tags`: https://quay.io/repository/biocontainers/bioconductor-ebimage?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-ebimage/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-ebimage/README.html