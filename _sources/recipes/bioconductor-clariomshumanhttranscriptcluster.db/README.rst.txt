:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-clariomshumanhttranscriptcluster.db'
.. highlight: bash

bioconductor-clariomshumanhttranscriptcluster.db
================================================

.. conda:recipe:: bioconductor-clariomshumanhttranscriptcluster.db
   :replaces_section_title:

   Affymetrix clariomshumanht annotation data \(chip clariomshumanhttranscriptcluster\) assembled using data from public repositories

   :homepage: https://bioconductor.org/packages/3.9/data/annotation/html/clariomshumanhttranscriptcluster.db.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-clariomshumanhttranscriptcluster.db <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-clariomshumanhttranscriptcluster.db>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-clariomshumanhttranscriptcluster.db/meta.yaml>`_

   


.. conda:package:: bioconductor-clariomshumanhttranscriptcluster.db

   |downloads_bioconductor-clariomshumanhttranscriptcluster.db| |docker_bioconductor-clariomshumanhttranscriptcluster.db|

   :versions: 8.7.0-2, 8.7.0-0
   
   :depends bioconductor-annotationdbi: >=1.46.0,<1.47.0
   :depends bioconductor-org.hs.eg.db: >=3.8.0,<3.9.0
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-clariomshumanhttranscriptcluster.db

   and update with::

      conda update bioconductor-clariomshumanhttranscriptcluster.db

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-clariomshumanhttranscriptcluster.db:<tag>

   (see `bioconductor-clariomshumanhttranscriptcluster.db/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-clariomshumanhttranscriptcluster.db| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-clariomshumanhttranscriptcluster.db.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-clariomshumanhttranscriptcluster.db
   :alt:   (downloads)
.. |docker_bioconductor-clariomshumanhttranscriptcluster.db| image:: https://quay.io/repository/biocontainers/bioconductor-clariomshumanhttranscriptcluster.db/status
   :target: https://quay.io/repository/biocontainers/bioconductor-clariomshumanhttranscriptcluster.db
.. _`bioconductor-clariomshumanhttranscriptcluster.db/tags`: https://quay.io/repository/biocontainers/bioconductor-clariomshumanhttranscriptcluster.db?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-clariomshumanhttranscriptcluster.db/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-clariomshumanhttranscriptcluster.db/README.html