:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-hs25kresogen.db'
.. highlight: bash

bioconductor-hs25kresogen.db
============================

.. conda:recipe:: bioconductor-hs25kresogen.db
   :replaces_section_title:

   RNG\_MRC Human Pangenomic 25k Set annotation data \(chip hs25kresogen\) assembled using data from public repositories

   :homepage: https://bioconductor.org/packages/3.9/data/annotation/html/hs25kresogen.db.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-hs25kresogen.db <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-hs25kresogen.db>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-hs25kresogen.db/meta.yaml>`_

   


.. conda:package:: bioconductor-hs25kresogen.db

   |downloads_bioconductor-hs25kresogen.db| |docker_bioconductor-hs25kresogen.db|

   :versions: 2.5.0-2, 2.5.0-0
   
   :depends bioconductor-annotationdbi: >=1.46.0,<1.47.0
   :depends bioconductor-org.hs.eg.db: >=3.8.0,<3.9.0
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-hs25kresogen.db

   and update with::

      conda update bioconductor-hs25kresogen.db

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-hs25kresogen.db:<tag>

   (see `bioconductor-hs25kresogen.db/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-hs25kresogen.db| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-hs25kresogen.db.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-hs25kresogen.db
   :alt:   (downloads)
.. |docker_bioconductor-hs25kresogen.db| image:: https://quay.io/repository/biocontainers/bioconductor-hs25kresogen.db/status
   :target: https://quay.io/repository/biocontainers/bioconductor-hs25kresogen.db
.. _`bioconductor-hs25kresogen.db/tags`: https://quay.io/repository/biocontainers/bioconductor-hs25kresogen.db?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-hs25kresogen.db/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-hs25kresogen.db/README.html