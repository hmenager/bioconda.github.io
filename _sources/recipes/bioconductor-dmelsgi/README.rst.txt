:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-dmelsgi'
.. highlight: bash

bioconductor-dmelsgi
====================

.. conda:recipe:: bioconductor-dmelsgi
   :replaces_section_title:

   The package contains the experimental data and documented source code of the manuscript \"Fischer et al.\, A Map of Directional Genetic Interactions in a Metazoan Cell\, eLife\, 2015\, in Press.\". The vignette code generates all figures in the paper.

   :homepage: https://bioconductor.org/packages/3.9/data/experiment/html/DmelSGI.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-dmelsgi <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-dmelsgi>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-dmelsgi/meta.yaml>`_

   


.. conda:package:: bioconductor-dmelsgi

   |downloads_bioconductor-dmelsgi| |docker_bioconductor-dmelsgi|

   :versions: 1.16.0-1, 1.16.0-0, 1.14.0-0
   
   :depends bioconductor-limma: >=3.40.0,<3.41.0
   :depends bioconductor-rhdf5: >=2.28.0,<2.29.0
   :depends curl: >=7.65.3,<8.0a0
   :depends r-abind: 
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-gplots: 
   :depends r-igraph: 
   :depends r-knitr: 
   :depends r-tsp: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-dmelsgi

   and update with::

      conda update bioconductor-dmelsgi

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-dmelsgi:<tag>

   (see `bioconductor-dmelsgi/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-dmelsgi| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-dmelsgi.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-dmelsgi
   :alt:   (downloads)
.. |docker_bioconductor-dmelsgi| image:: https://quay.io/repository/biocontainers/bioconductor-dmelsgi/status
   :target: https://quay.io/repository/biocontainers/bioconductor-dmelsgi
.. _`bioconductor-dmelsgi/tags`: https://quay.io/repository/biocontainers/bioconductor-dmelsgi?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-dmelsgi/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-dmelsgi/README.html