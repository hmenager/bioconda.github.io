:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'ucsc-pslliftsubrangeblat'
.. highlight: bash

ucsc-pslliftsubrangeblat
========================

.. conda:recipe:: ucsc-pslliftsubrangeblat
   :replaces_section_title:

   lift PSLs from blat subrange alignments

   :homepage: http://hgdownload.cse.ucsc.edu/admin/exe/
   :license: varies; see http://genome.ucsc.edu/license
   :recipe: /`ucsc-pslliftsubrangeblat <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/ucsc-pslliftsubrangeblat>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/ucsc-pslliftsubrangeblat/meta.yaml>`_

   


.. conda:package:: ucsc-pslliftsubrangeblat

   |downloads_ucsc-pslliftsubrangeblat| |docker_ucsc-pslliftsubrangeblat|

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

      conda install ucsc-pslliftsubrangeblat

   and update with::

      conda update ucsc-pslliftsubrangeblat

   or use the docker container::

      docker pull quay.io/biocontainers/ucsc-pslliftsubrangeblat:<tag>

   (see `ucsc-pslliftsubrangeblat/tags`_ for valid values for ``<tag>``)


.. |downloads_ucsc-pslliftsubrangeblat| image:: https://img.shields.io/conda/dn/bioconda/ucsc-pslliftsubrangeblat.svg?style=flat
   :target: https://anaconda.org/bioconda/ucsc-pslliftsubrangeblat
   :alt:   (downloads)
.. |docker_ucsc-pslliftsubrangeblat| image:: https://quay.io/repository/biocontainers/ucsc-pslliftsubrangeblat/status
   :target: https://quay.io/repository/biocontainers/ucsc-pslliftsubrangeblat
.. _`ucsc-pslliftsubrangeblat/tags`: https://quay.io/repository/biocontainers/ucsc-pslliftsubrangeblat?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/ucsc-pslliftsubrangeblat/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/ucsc-pslliftsubrangeblat/README.html