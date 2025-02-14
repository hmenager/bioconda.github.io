:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-aims'
.. highlight: bash

bioconductor-aims
=================

.. conda:recipe:: bioconductor-aims
   :replaces_section_title:

   This package contains the AIMS implementation. It contains necessary functions to assign the five intrinsic molecular subtypes \(Luminal A\, Luminal B\, Her2\-enriched\, Basal\-like\, Normal\-like\). Assignments could be done on individual samples as well as on dataset of gene expression data.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/AIMS.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-aims <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-aims>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-aims/meta.yaml>`_
   :links: biotools: :biotools:`aims`, doi: :doi:`10.1093/jnci/dju357`

   


.. conda:package:: bioconductor-aims

   |downloads_bioconductor-aims| |docker_bioconductor-aims|

   :versions: 1.16.0-1, 1.14.1-0, 1.14.0-0, 1.12.0-0, 1.10.0-0, 1.8.0-0
   
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-e1071: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-aims

   and update with::

      conda update bioconductor-aims

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-aims:<tag>

   (see `bioconductor-aims/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-aims| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-aims.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-aims
   :alt:   (downloads)
.. |docker_bioconductor-aims| image:: https://quay.io/repository/biocontainers/bioconductor-aims/status
   :target: https://quay.io/repository/biocontainers/bioconductor-aims
.. _`bioconductor-aims/tags`: https://quay.io/repository/biocontainers/bioconductor-aims?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-aims/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-aims/README.html