:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-go.db'
.. highlight: bash

bioconductor-go.db
==================

.. conda:recipe:: bioconductor-go.db
   :replaces_section_title:

   A set of annotation maps describing the entire Gene Ontology assembled using data from GO

   :homepage: https://bioconductor.org/packages/3.9/data/annotation/html/GO.db.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-go.db <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-go.db>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-go.db/meta.yaml>`_

   


.. conda:package:: bioconductor-go.db

   |downloads_bioconductor-go.db| |docker_bioconductor-go.db|

   :versions: 3.8.2-1, 3.7.0-0, 3.6.0-0, 3.5.0-1, 3.5.0-0, 3.4.2-0, 3.4.1-0, 3.4.0-0, 3.3.0-0, 3.2.2-0
   
   :depends bioconductor-annotationdbi: >=1.46.0,<1.47.0
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-go.db

   and update with::

      conda update bioconductor-go.db

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-go.db:<tag>

   (see `bioconductor-go.db/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-go.db| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-go.db.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-go.db
   :alt:   (downloads)
.. |docker_bioconductor-go.db| image:: https://quay.io/repository/biocontainers/bioconductor-go.db/status
   :target: https://quay.io/repository/biocontainers/bioconductor-go.db
.. _`bioconductor-go.db/tags`: https://quay.io/repository/biocontainers/bioconductor-go.db?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-go.db/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-go.db/README.html