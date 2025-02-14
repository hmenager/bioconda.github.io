:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'ucsc-ixixx'
.. highlight: bash

ucsc-ixixx
==========

.. conda:recipe:: ucsc-ixixx
   :replaces_section_title:

   Create indices for simple line\-oriented file of format 

   :homepage: http://hgdownload.cse.ucsc.edu/admin/exe/
   :license: varies; see http://genome.ucsc.edu/license
   :recipe: /`ucsc-ixixx <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/ucsc-ixixx>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/ucsc-ixixx/meta.yaml>`_

   


.. conda:package:: ucsc-ixixx

   |downloads_ucsc-ixixx| |docker_ucsc-ixixx|

   :versions: 377-0, 366-0, 357-2, 357-1, 357-0
   
   :depends libgcc-ng: >=7.3.0
   :depends libpng: >=1.6.35,<1.7.0a0
   :depends libuuid: >=2.32.1,<3.0a0
   :depends mysql-connector-c: >=6.1.11,<6.1.12.0a0
   :depends openssl: >=1.0.2p,<1.0.3a
   :depends zlib: >=1.2.11,<1.3.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install ucsc-ixixx

   and update with::

      conda update ucsc-ixixx

   or use the docker container::

      docker pull quay.io/biocontainers/ucsc-ixixx:<tag>

   (see `ucsc-ixixx/tags`_ for valid values for ``<tag>``)


.. |downloads_ucsc-ixixx| image:: https://img.shields.io/conda/dn/bioconda/ucsc-ixixx.svg?style=flat
   :target: https://anaconda.org/bioconda/ucsc-ixixx
   :alt:   (downloads)
.. |docker_ucsc-ixixx| image:: https://quay.io/repository/biocontainers/ucsc-ixixx/status
   :target: https://quay.io/repository/biocontainers/ucsc-ixixx
.. _`ucsc-ixixx/tags`: https://quay.io/repository/biocontainers/ucsc-ixixx?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/ucsc-ixixx/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/ucsc-ixixx/README.html