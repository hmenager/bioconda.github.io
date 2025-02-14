:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'ucsc-bedgraphtobigwig'
.. highlight: bash

ucsc-bedgraphtobigwig
=====================

.. conda:recipe:: ucsc-bedgraphtobigwig
   :replaces_section_title:

   Convert a bedGraph file to bigWig format.

   :homepage: http://hgdownload.cse.ucsc.edu/admin/exe/
   :license: varies; see http://genome.ucsc.edu/license
   :recipe: /`ucsc-bedgraphtobigwig <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/ucsc-bedgraphtobigwig>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/ucsc-bedgraphtobigwig/meta.yaml>`_

   


.. conda:package:: ucsc-bedgraphtobigwig

   |downloads_ucsc-bedgraphtobigwig| |docker_ucsc-bedgraphtobigwig|

   :versions: 377-0, 366-0, 357-3, 357-1, 357-0, 332-0, 324-0, 308-1, 308-0
   
   :depends libgcc-ng: >=7.3.0
   :depends libpng: >=1.6.35,<1.7.0a0
   :depends libuuid: >=2.32.1,<3.0a0
   :depends mysql-connector-c: 
   :depends openssl: >=1.0.2p,<1.0.3a
   :depends zlib: >=1.2.11,<1.3.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install ucsc-bedgraphtobigwig

   and update with::

      conda update ucsc-bedgraphtobigwig

   or use the docker container::

      docker pull quay.io/biocontainers/ucsc-bedgraphtobigwig:<tag>

   (see `ucsc-bedgraphtobigwig/tags`_ for valid values for ``<tag>``)


.. |downloads_ucsc-bedgraphtobigwig| image:: https://img.shields.io/conda/dn/bioconda/ucsc-bedgraphtobigwig.svg?style=flat
   :target: https://anaconda.org/bioconda/ucsc-bedgraphtobigwig
   :alt:   (downloads)
.. |docker_ucsc-bedgraphtobigwig| image:: https://quay.io/repository/biocontainers/ucsc-bedgraphtobigwig/status
   :target: https://quay.io/repository/biocontainers/ucsc-bedgraphtobigwig
.. _`ucsc-bedgraphtobigwig/tags`: https://quay.io/repository/biocontainers/ucsc-bedgraphtobigwig?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/ucsc-bedgraphtobigwig/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/ucsc-bedgraphtobigwig/README.html