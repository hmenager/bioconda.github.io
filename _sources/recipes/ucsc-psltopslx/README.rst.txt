:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'ucsc-psltopslx'
.. highlight: bash

ucsc-psltopslx
==============

.. conda:recipe:: ucsc-psltopslx
   :replaces_section_title:

   Convert from psl to pslx format\, which includes sequences

   :homepage: http://hgdownload.cse.ucsc.edu/admin/exe/
   :license: varies; see http://genome.ucsc.edu/license
   :recipe: /`ucsc-psltopslx <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/ucsc-psltopslx>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/ucsc-psltopslx/meta.yaml>`_

   


.. conda:package:: ucsc-psltopslx

   |downloads_ucsc-psltopslx| |docker_ucsc-psltopslx|

   :versions: 377-0, 366-0, 357-2, 357-1, 357-0, 332-0, 324-0
   
   :depends libgcc-ng: >=7.3.0
   :depends libpng: >=1.6.35,<1.7.0a0
   :depends libuuid: >=2.32.1,<3.0a0
   :depends mysql-connector-c: >=6.1.11,<6.1.12.0a0
   :depends openssl: >=1.0.2p,<1.0.3a
   :depends zlib: >=1.2.11,<1.3.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install ucsc-psltopslx

   and update with::

      conda update ucsc-psltopslx

   or use the docker container::

      docker pull quay.io/biocontainers/ucsc-psltopslx:<tag>

   (see `ucsc-psltopslx/tags`_ for valid values for ``<tag>``)


.. |downloads_ucsc-psltopslx| image:: https://img.shields.io/conda/dn/bioconda/ucsc-psltopslx.svg?style=flat
   :target: https://anaconda.org/bioconda/ucsc-psltopslx
   :alt:   (downloads)
.. |docker_ucsc-psltopslx| image:: https://quay.io/repository/biocontainers/ucsc-psltopslx/status
   :target: https://quay.io/repository/biocontainers/ucsc-psltopslx
.. _`ucsc-psltopslx/tags`: https://quay.io/repository/biocontainers/ucsc-psltopslx?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/ucsc-psltopslx/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/ucsc-psltopslx/README.html