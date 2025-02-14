:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-geuvpack'
.. highlight: bash

bioconductor-geuvpack
=====================

.. conda:recipe:: bioconductor-geuvpack
   :replaces_section_title:

   FPKM from GEUVADIS\, annotated to gencode regions

   :homepage: https://bioconductor.org/packages/3.9/data/experiment/html/geuvPack.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-geuvpack <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-geuvpack>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-geuvpack/meta.yaml>`_

   


.. conda:package:: bioconductor-geuvpack

   |downloads_bioconductor-geuvpack| |docker_bioconductor-geuvpack|

   :versions: 1.16.0-1, 1.14.0-0
   
   :depends bioconductor-summarizedexperiment: >=1.14.0,<1.15.0
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-geuvpack

   and update with::

      conda update bioconductor-geuvpack

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-geuvpack:<tag>

   (see `bioconductor-geuvpack/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-geuvpack| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-geuvpack.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-geuvpack
   :alt:   (downloads)
.. |docker_bioconductor-geuvpack| image:: https://quay.io/repository/biocontainers/bioconductor-geuvpack/status
   :target: https://quay.io/repository/biocontainers/bioconductor-geuvpack
.. _`bioconductor-geuvpack/tags`: https://quay.io/repository/biocontainers/bioconductor-geuvpack?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-geuvpack/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-geuvpack/README.html