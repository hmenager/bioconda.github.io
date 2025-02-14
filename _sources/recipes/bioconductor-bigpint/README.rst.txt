:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-bigpint'
.. highlight: bash

bioconductor-bigpint
====================

.. conda:recipe:: bioconductor-bigpint
   :replaces_section_title:

   Methods for visualizing large multivariate datasets using static and interactive scatterplot matrices\, parallel coordinate plots\, volcano plots\, and litre plots. Includes examples for visualizing RNA\-sequencing datasets and differentially expressed genes.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/bigPint.html
   :license: GPL-3
   :recipe: /`bioconductor-bigpint <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-bigpint>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-bigpint/meta.yaml>`_

   


.. conda:package:: bioconductor-bigpint

   |downloads_bioconductor-bigpint| |docker_bioconductor-bigpint|

   :versions: 1.0.0-1
   
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-dplyr: >=0.7.2
   :depends r-ggally: >=1.3.2
   :depends r-ggplot2: >=2.2.1
   :depends r-gridextra: >=2.3
   :depends r-hexbin: >=1.27.1
   :depends r-hmisc: >=4.0.3
   :depends r-htmlwidgets: >=0.9
   :depends r-plotly: >=4.7.1
   :depends r-plyr: >=1.8.4
   :depends r-rcolorbrewer: >=1.1.2
   :depends r-reshape: >=0.8.7
   :depends r-shiny: >=1.0.5
   :depends r-shinycssloaders: >=0.2.0
   :depends r-shinydashboard: >=0.6.1
   :depends r-stringr: >=1.3.1
   :depends r-tidyr: >=0.7.0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-bigpint

   and update with::

      conda update bioconductor-bigpint

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-bigpint:<tag>

   (see `bioconductor-bigpint/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-bigpint| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-bigpint.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-bigpint
   :alt:   (downloads)
.. |docker_bioconductor-bigpint| image:: https://quay.io/repository/biocontainers/bioconductor-bigpint/status
   :target: https://quay.io/repository/biocontainers/bioconductor-bigpint
.. _`bioconductor-bigpint/tags`: https://quay.io/repository/biocontainers/bioconductor-bigpint?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-bigpint/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-bigpint/README.html