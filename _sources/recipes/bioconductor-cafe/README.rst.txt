:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-cafe'
.. highlight: bash

bioconductor-cafe
=================

.. conda:recipe:: bioconductor-cafe
   :replaces_section_title:

   Detection and visualizations of gross chromosomal aberrations using Affymetrix expression microarrays as input

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/CAFE.html
   :license: GPL-3
   :recipe: /`bioconductor-cafe <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-cafe>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-cafe/meta.yaml>`_

   


.. conda:package:: bioconductor-cafe

   |downloads_bioconductor-cafe| |docker_bioconductor-cafe|

   :versions: 1.20.0-1, 1.18.0-0
   
   :depends bioconductor-affy: >=1.62.0,<1.63.0
   :depends bioconductor-annotate: >=1.62.0,<1.63.0
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends bioconductor-biovizbase: >=1.32.0,<1.33.0
   :depends bioconductor-genomicranges: >=1.36.0,<1.37.0
   :depends bioconductor-ggbio: >=1.32.0,<1.33.0
   :depends bioconductor-iranges: >=2.18.0,<2.19.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-ggplot2: 
   :depends r-gridextra: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-cafe

   and update with::

      conda update bioconductor-cafe

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-cafe:<tag>

   (see `bioconductor-cafe/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-cafe| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-cafe.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-cafe
   :alt:   (downloads)
.. |docker_bioconductor-cafe| image:: https://quay.io/repository/biocontainers/bioconductor-cafe/status
   :target: https://quay.io/repository/biocontainers/bioconductor-cafe
.. _`bioconductor-cafe/tags`: https://quay.io/repository/biocontainers/bioconductor-cafe?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-cafe/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-cafe/README.html