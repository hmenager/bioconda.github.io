:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-metams'
.. highlight: bash

bioconductor-metams
===================

.. conda:recipe:: bioconductor-metams
   :replaces_section_title:

   MS\-based metabolomics data processing and compound annotation pipeline.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/metaMS.html
   :license: GPL (>= 2)
   :recipe: /`bioconductor-metams <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-metams>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-metams/meta.yaml>`_
   :links: biotools: :biotools:`metams`

   


.. conda:package:: bioconductor-metams

   |downloads_bioconductor-metams| |docker_bioconductor-metams|

   :versions: 1.20.0-1, 1.18.1-0, 1.14.0-0, 1.12.0-0, 1.8.0-0
   
   :depends bioconductor-biocgenerics: >=0.30.0,<0.31.0
   :depends bioconductor-camera: >=1.40.0,<1.41.0
   :depends bioconductor-xcms: >=3.6.0,<3.7.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-matrix: 
   :depends r-robustbase: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-metams

   and update with::

      conda update bioconductor-metams

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-metams:<tag>

   (see `bioconductor-metams/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-metams| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-metams.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-metams
   :alt:   (downloads)
.. |docker_bioconductor-metams| image:: https://quay.io/repository/biocontainers/bioconductor-metams/status
   :target: https://quay.io/repository/biocontainers/bioconductor-metams
.. _`bioconductor-metams/tags`: https://quay.io/repository/biocontainers/bioconductor-metams?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-metams/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-metams/README.html