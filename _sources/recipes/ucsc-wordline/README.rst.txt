:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'ucsc-wordline'
.. highlight: bash

ucsc-wordline
=============

.. conda:recipe:: ucsc-wordline
   :replaces_section_title:

   chop up words by white space and output them with one

   :homepage: http://hgdownload.cse.ucsc.edu/admin/exe/
   :license: varies; see http://genome.ucsc.edu/license
   :recipe: /`ucsc-wordline <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/ucsc-wordline>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/ucsc-wordline/meta.yaml>`_

   


.. conda:package:: ucsc-wordline

   |downloads_ucsc-wordline| |docker_ucsc-wordline|

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

      conda install ucsc-wordline

   and update with::

      conda update ucsc-wordline

   or use the docker container::

      docker pull quay.io/biocontainers/ucsc-wordline:<tag>

   (see `ucsc-wordline/tags`_ for valid values for ``<tag>``)


.. |downloads_ucsc-wordline| image:: https://img.shields.io/conda/dn/bioconda/ucsc-wordline.svg?style=flat
   :target: https://anaconda.org/bioconda/ucsc-wordline
   :alt:   (downloads)
.. |docker_ucsc-wordline| image:: https://quay.io/repository/biocontainers/ucsc-wordline/status
   :target: https://quay.io/repository/biocontainers/ucsc-wordline
.. _`ucsc-wordline/tags`: https://quay.io/repository/biocontainers/ucsc-wordline?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/ucsc-wordline/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/ucsc-wordline/README.html