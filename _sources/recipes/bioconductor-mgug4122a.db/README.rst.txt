:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-mgug4122a.db'
.. highlight: bash

bioconductor-mgug4122a.db
=========================

.. conda:recipe:: bioconductor-mgug4122a.db
   :replaces_section_title:

   Agilent \"Mouse Genome\, Whole\" annotation data \(chip mgug4122a\) assembled using data from public repositories

   :homepage: https://bioconductor.org/packages/3.9/data/annotation/html/mgug4122a.db.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-mgug4122a.db <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-mgug4122a.db>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-mgug4122a.db/meta.yaml>`_

   


.. conda:package:: bioconductor-mgug4122a.db

   |downloads_bioconductor-mgug4122a.db| |docker_bioconductor-mgug4122a.db|

   :versions: 3.2.3-7, 3.2.3-5, 3.2.3-4, 3.2.3-2, 3.2.3-1, 3.2.3-0, 3.2.2-0
   
   :depends bioconductor-annotationdbi: >=1.46.0,<1.47.0
   :depends bioconductor-org.mm.eg.db: >=3.8.0,<3.9.0
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-mgug4122a.db

   and update with::

      conda update bioconductor-mgug4122a.db

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-mgug4122a.db:<tag>

   (see `bioconductor-mgug4122a.db/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-mgug4122a.db| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-mgug4122a.db.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-mgug4122a.db
   :alt:   (downloads)
.. |docker_bioconductor-mgug4122a.db| image:: https://quay.io/repository/biocontainers/bioconductor-mgug4122a.db/status
   :target: https://quay.io/repository/biocontainers/bioconductor-mgug4122a.db
.. _`bioconductor-mgug4122a.db/tags`: https://quay.io/repository/biocontainers/bioconductor-mgug4122a.db?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-mgug4122a.db/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-mgug4122a.db/README.html