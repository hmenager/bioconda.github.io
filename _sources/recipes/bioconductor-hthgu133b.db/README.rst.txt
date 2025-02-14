:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-hthgu133b.db'
.. highlight: bash

bioconductor-hthgu133b.db
=========================

.. conda:recipe:: bioconductor-hthgu133b.db
   :replaces_section_title:

   Affymetrix HT Human Genome U133 Array Plate Set annotation data \(chip hthgu133b\) assembled using data from public repositories

   :homepage: https://bioconductor.org/packages/3.9/data/annotation/html/hthgu133b.db.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-hthgu133b.db <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-hthgu133b.db>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-hthgu133b.db/meta.yaml>`_

   


.. conda:package:: bioconductor-hthgu133b.db

   |downloads_bioconductor-hthgu133b.db| |docker_bioconductor-hthgu133b.db|

   :versions: 3.2.3-2, 3.2.3-0
   
   :depends bioconductor-annotationdbi: >=1.46.0,<1.47.0
   :depends bioconductor-org.hs.eg.db: >=3.8.0,<3.9.0
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-hthgu133b.db

   and update with::

      conda update bioconductor-hthgu133b.db

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-hthgu133b.db:<tag>

   (see `bioconductor-hthgu133b.db/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-hthgu133b.db| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-hthgu133b.db.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-hthgu133b.db
   :alt:   (downloads)
.. |docker_bioconductor-hthgu133b.db| image:: https://quay.io/repository/biocontainers/bioconductor-hthgu133b.db/status
   :target: https://quay.io/repository/biocontainers/bioconductor-hthgu133b.db
.. _`bioconductor-hthgu133b.db/tags`: https://quay.io/repository/biocontainers/bioconductor-hthgu133b.db?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-hthgu133b.db/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-hthgu133b.db/README.html