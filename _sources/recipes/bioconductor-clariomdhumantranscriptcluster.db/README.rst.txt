:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-clariomdhumantranscriptcluster.db'
.. highlight: bash

bioconductor-clariomdhumantranscriptcluster.db
==============================================

.. conda:recipe:: bioconductor-clariomdhumantranscriptcluster.db
   :replaces_section_title:

   Affymetrix clariomdhuman annotation data \(chip clariomdhumantranscriptcluster\) assembled using data from public repositories

   :homepage: https://bioconductor.org/packages/3.9/data/annotation/html/clariomdhumantranscriptcluster.db.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-clariomdhumantranscriptcluster.db <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-clariomdhumantranscriptcluster.db>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-clariomdhumantranscriptcluster.db/meta.yaml>`_

   


.. conda:package:: bioconductor-clariomdhumantranscriptcluster.db

   |downloads_bioconductor-clariomdhumantranscriptcluster.db| |docker_bioconductor-clariomdhumantranscriptcluster.db|

   :versions: 8.7.0-2, 8.7.0-0
   
   :depends bioconductor-annotationdbi: >=1.46.0,<1.47.0
   :depends bioconductor-org.hs.eg.db: >=3.8.0,<3.9.0
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-clariomdhumantranscriptcluster.db

   and update with::

      conda update bioconductor-clariomdhumantranscriptcluster.db

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-clariomdhumantranscriptcluster.db:<tag>

   (see `bioconductor-clariomdhumantranscriptcluster.db/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-clariomdhumantranscriptcluster.db| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-clariomdhumantranscriptcluster.db.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-clariomdhumantranscriptcluster.db
   :alt:   (downloads)
.. |docker_bioconductor-clariomdhumantranscriptcluster.db| image:: https://quay.io/repository/biocontainers/bioconductor-clariomdhumantranscriptcluster.db/status
   :target: https://quay.io/repository/biocontainers/bioconductor-clariomdhumantranscriptcluster.db
.. _`bioconductor-clariomdhumantranscriptcluster.db/tags`: https://quay.io/repository/biocontainers/bioconductor-clariomdhumantranscriptcluster.db?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-clariomdhumantranscriptcluster.db/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-clariomdhumantranscriptcluster.db/README.html