:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-clariomsmousetranscriptcluster.db'
.. highlight: bash

bioconductor-clariomsmousetranscriptcluster.db
==============================================

.. conda:recipe:: bioconductor-clariomsmousetranscriptcluster.db
   :replaces_section_title:

   Affymetrix clariomsmouse annotation data \(chip clariomsmousetranscriptcluster\) assembled using data from public repositories

   :homepage: https://bioconductor.org/packages/3.9/data/annotation/html/clariomsmousetranscriptcluster.db.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-clariomsmousetranscriptcluster.db <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-clariomsmousetranscriptcluster.db>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-clariomsmousetranscriptcluster.db/meta.yaml>`_

   


.. conda:package:: bioconductor-clariomsmousetranscriptcluster.db

   |downloads_bioconductor-clariomsmousetranscriptcluster.db| |docker_bioconductor-clariomsmousetranscriptcluster.db|

   :versions: 8.7.0-2, 8.7.0-0
   
   :depends bioconductor-annotationdbi: >=1.46.0,<1.47.0
   :depends bioconductor-org.mm.eg.db: >=3.8.0,<3.9.0
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-clariomsmousetranscriptcluster.db

   and update with::

      conda update bioconductor-clariomsmousetranscriptcluster.db

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-clariomsmousetranscriptcluster.db:<tag>

   (see `bioconductor-clariomsmousetranscriptcluster.db/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-clariomsmousetranscriptcluster.db| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-clariomsmousetranscriptcluster.db.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-clariomsmousetranscriptcluster.db
   :alt:   (downloads)
.. |docker_bioconductor-clariomsmousetranscriptcluster.db| image:: https://quay.io/repository/biocontainers/bioconductor-clariomsmousetranscriptcluster.db/status
   :target: https://quay.io/repository/biocontainers/bioconductor-clariomsmousetranscriptcluster.db
.. _`bioconductor-clariomsmousetranscriptcluster.db/tags`: https://quay.io/repository/biocontainers/bioconductor-clariomsmousetranscriptcluster.db?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-clariomsmousetranscriptcluster.db/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-clariomsmousetranscriptcluster.db/README.html