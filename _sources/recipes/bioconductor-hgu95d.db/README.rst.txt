:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-hgu95d.db'
.. highlight: bash

bioconductor-hgu95d.db
======================

.. conda:recipe:: bioconductor-hgu95d.db
   :replaces_section_title:

   Affymetrix Human Genome U95 Set annotation data \(chip hgu95d\) assembled using data from public repositories

   :homepage: https://bioconductor.org/packages/3.9/data/annotation/html/hgu95d.db.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-hgu95d.db <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-hgu95d.db>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-hgu95d.db/meta.yaml>`_

   


.. conda:package:: bioconductor-hgu95d.db

   |downloads_bioconductor-hgu95d.db| |docker_bioconductor-hgu95d.db|

   :versions: 3.2.3-2, 3.2.3-0
   
   :depends bioconductor-annotationdbi: >=1.46.0,<1.47.0
   :depends bioconductor-org.hs.eg.db: >=3.8.0,<3.9.0
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-hgu95d.db

   and update with::

      conda update bioconductor-hgu95d.db

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-hgu95d.db:<tag>

   (see `bioconductor-hgu95d.db/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-hgu95d.db| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-hgu95d.db.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-hgu95d.db
   :alt:   (downloads)
.. |docker_bioconductor-hgu95d.db| image:: https://quay.io/repository/biocontainers/bioconductor-hgu95d.db/status
   :target: https://quay.io/repository/biocontainers/bioconductor-hgu95d.db
.. _`bioconductor-hgu95d.db/tags`: https://quay.io/repository/biocontainers/bioconductor-hgu95d.db?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-hgu95d.db/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-hgu95d.db/README.html