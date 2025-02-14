:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'ucsc-websync'
.. highlight: bash

ucsc-websync
============

.. conda:recipe:: ucsc-websync
   :replaces_section_title:

   download from https server\, using files.txt on their end to get the list of files

   :homepage: http://hgdownload.cse.ucsc.edu/admin/exe/
   :license: varies; see http://genome.ucsc.edu/license
   :recipe: /`ucsc-websync <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/ucsc-websync>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/ucsc-websync/meta.yaml>`_

   


.. conda:package:: ucsc-websync

   |downloads_ucsc-websync| |docker_ucsc-websync|

   :versions: 377-0, 366-0
   
   :depends libgcc-ng: >=7.3.0
   :depends libpng: >=1.6.35,<1.7.0a0
   :depends libuuid: >=2.32.1,<3.0a0
   :depends mysql-connector-c: >=6.1.11,<6.1.12.0a0
   :depends openssl: >=1.0.2p,<1.0.3a
   :depends python: 
   :depends zlib: >=1.2.11,<1.3.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install ucsc-websync

   and update with::

      conda update ucsc-websync

   or use the docker container::

      docker pull quay.io/biocontainers/ucsc-websync:<tag>

   (see `ucsc-websync/tags`_ for valid values for ``<tag>``)


.. |downloads_ucsc-websync| image:: https://img.shields.io/conda/dn/bioconda/ucsc-websync.svg?style=flat
   :target: https://anaconda.org/bioconda/ucsc-websync
   :alt:   (downloads)
.. |docker_ucsc-websync| image:: https://quay.io/repository/biocontainers/ucsc-websync/status
   :target: https://quay.io/repository/biocontainers/ucsc-websync
.. _`ucsc-websync/tags`: https://quay.io/repository/biocontainers/ucsc-websync?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/ucsc-websync/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/ucsc-websync/README.html