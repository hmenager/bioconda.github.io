:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-rtu34.db'
.. highlight: bash

bioconductor-rtu34.db
=====================

.. conda:recipe:: bioconductor-rtu34.db
   :replaces_section_title:

   Affymetrix Rat Toxicology U34 Array annotation data \(chip rtu34\) assembled using data from public repositories

   :homepage: https://bioconductor.org/packages/3.9/data/annotation/html/rtu34.db.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-rtu34.db <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-rtu34.db>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-rtu34.db/meta.yaml>`_

   


.. conda:package:: bioconductor-rtu34.db

   |downloads_bioconductor-rtu34.db| |docker_bioconductor-rtu34.db|

   :versions: 3.2.3-2, 3.2.3-0
   
   :depends bioconductor-annotationdbi: >=1.46.0,<1.47.0
   :depends bioconductor-org.rn.eg.db: >=3.8.0,<3.9.0
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-rtu34.db

   and update with::

      conda update bioconductor-rtu34.db

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-rtu34.db:<tag>

   (see `bioconductor-rtu34.db/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-rtu34.db| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-rtu34.db.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-rtu34.db
   :alt:   (downloads)
.. |docker_bioconductor-rtu34.db| image:: https://quay.io/repository/biocontainers/bioconductor-rtu34.db/status
   :target: https://quay.io/repository/biocontainers/bioconductor-rtu34.db
.. _`bioconductor-rtu34.db/tags`: https://quay.io/repository/biocontainers/bioconductor-rtu34.db?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-rtu34.db/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-rtu34.db/README.html