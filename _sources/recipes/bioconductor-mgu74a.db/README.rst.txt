:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-mgu74a.db'
.. highlight: bash

bioconductor-mgu74a.db
======================

.. conda:recipe:: bioconductor-mgu74a.db
   :replaces_section_title:

   Affymetrix Murine Genome U74v2 annotation data \(chip mgu74a\) assembled using data from public repositories

   :homepage: https://bioconductor.org/packages/3.9/data/annotation/html/mgu74a.db.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-mgu74a.db <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-mgu74a.db>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-mgu74a.db/meta.yaml>`_

   


.. conda:package:: bioconductor-mgu74a.db

   |downloads_bioconductor-mgu74a.db| |docker_bioconductor-mgu74a.db|

   :versions: 3.2.3-2, 3.2.3-0
   
   :depends bioconductor-annotationdbi: >=1.46.0,<1.47.0
   :depends bioconductor-org.mm.eg.db: >=3.8.0,<3.9.0
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-mgu74a.db

   and update with::

      conda update bioconductor-mgu74a.db

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-mgu74a.db:<tag>

   (see `bioconductor-mgu74a.db/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-mgu74a.db| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-mgu74a.db.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-mgu74a.db
   :alt:   (downloads)
.. |docker_bioconductor-mgu74a.db| image:: https://quay.io/repository/biocontainers/bioconductor-mgu74a.db/status
   :target: https://quay.io/repository/biocontainers/bioconductor-mgu74a.db
.. _`bioconductor-mgu74a.db/tags`: https://quay.io/repository/biocontainers/bioconductor-mgu74a.db?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-mgu74a.db/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-mgu74a.db/README.html