:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-hgfocus.db'
.. highlight: bash

bioconductor-hgfocus.db
=======================

.. conda:recipe:: bioconductor-hgfocus.db
   :replaces_section_title:

   Affymetrix Human Genome Focus Array annotation data \(chip hgfocus\) assembled using data from public repositories

   :homepage: https://bioconductor.org/packages/3.9/data/annotation/html/hgfocus.db.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-hgfocus.db <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-hgfocus.db>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-hgfocus.db/meta.yaml>`_

   


.. conda:package:: bioconductor-hgfocus.db

   |downloads_bioconductor-hgfocus.db| |docker_bioconductor-hgfocus.db|

   :versions: 3.2.3-2, 3.2.3-0
   
   :depends bioconductor-annotationdbi: >=1.46.0,<1.47.0
   :depends bioconductor-org.hs.eg.db: >=3.8.0,<3.9.0
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-hgfocus.db

   and update with::

      conda update bioconductor-hgfocus.db

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-hgfocus.db:<tag>

   (see `bioconductor-hgfocus.db/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-hgfocus.db| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-hgfocus.db.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-hgfocus.db
   :alt:   (downloads)
.. |docker_bioconductor-hgfocus.db| image:: https://quay.io/repository/biocontainers/bioconductor-hgfocus.db/status
   :target: https://quay.io/repository/biocontainers/bioconductor-hgfocus.db
.. _`bioconductor-hgfocus.db/tags`: https://quay.io/repository/biocontainers/bioconductor-hgfocus.db?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-hgfocus.db/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-hgfocus.db/README.html