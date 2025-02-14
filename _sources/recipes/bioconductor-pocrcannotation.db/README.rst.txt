:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-pocrcannotation.db'
.. highlight: bash

bioconductor-pocrcannotation.db
===============================

.. conda:recipe:: bioconductor-pocrcannotation.db
   :replaces_section_title:

   A package containing metadata for POCRC arrays assembled using data from public repositories

   :homepage: https://bioconductor.org/packages/3.9/data/annotation/html/POCRCannotation.db.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-pocrcannotation.db <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-pocrcannotation.db>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-pocrcannotation.db/meta.yaml>`_

   


.. conda:package:: bioconductor-pocrcannotation.db

   |downloads_bioconductor-pocrcannotation.db| |docker_bioconductor-pocrcannotation.db|

   :versions: 3.2.3-2, 3.2.3-0
   
   :depends bioconductor-annotationdbi: >=1.46.0,<1.47.0
   :depends bioconductor-org.hs.eg.db: >=3.8.0,<3.9.0
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-pocrcannotation.db

   and update with::

      conda update bioconductor-pocrcannotation.db

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-pocrcannotation.db:<tag>

   (see `bioconductor-pocrcannotation.db/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-pocrcannotation.db| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-pocrcannotation.db.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-pocrcannotation.db
   :alt:   (downloads)
.. |docker_bioconductor-pocrcannotation.db| image:: https://quay.io/repository/biocontainers/bioconductor-pocrcannotation.db/status
   :target: https://quay.io/repository/biocontainers/bioconductor-pocrcannotation.db
.. _`bioconductor-pocrcannotation.db/tags`: https://quay.io/repository/biocontainers/bioconductor-pocrcannotation.db?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-pocrcannotation.db/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-pocrcannotation.db/README.html