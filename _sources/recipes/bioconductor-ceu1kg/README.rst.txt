:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-ceu1kg'
.. highlight: bash

bioconductor-ceu1kg
===================

.. conda:recipe:: bioconductor-ceu1kg
   :replaces_section_title:

   CEU genotypes from 1000 genomes \"low coverage\" pilot phase I \(approx 8 million SNP calls released July 2010\)\; includes Wellcome trust GENEVAR expression for 43 indiv

   :homepage: https://bioconductor.org/packages/3.9/data/experiment/html/ceu1kg.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-ceu1kg <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-ceu1kg>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-ceu1kg/meta.yaml>`_

   


.. conda:package:: bioconductor-ceu1kg

   |downloads_bioconductor-ceu1kg| |docker_bioconductor-ceu1kg|

   :versions: 0.22.0-1, 0.20.0-0
   
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends bioconductor-ggbase: >=3.46.0,<3.47.0
   :depends bioconductor-ggtools: >=5.20.0,<5.21.0
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-ceu1kg

   and update with::

      conda update bioconductor-ceu1kg

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-ceu1kg:<tag>

   (see `bioconductor-ceu1kg/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-ceu1kg| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-ceu1kg.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-ceu1kg
   :alt:   (downloads)
.. |docker_bioconductor-ceu1kg| image:: https://quay.io/repository/biocontainers/bioconductor-ceu1kg/status
   :target: https://quay.io/repository/biocontainers/bioconductor-ceu1kg
.. _`bioconductor-ceu1kg/tags`: https://quay.io/repository/biocontainers/bioconductor-ceu1kg?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-ceu1kg/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-ceu1kg/README.html