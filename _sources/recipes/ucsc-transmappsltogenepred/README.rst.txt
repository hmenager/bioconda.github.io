:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'ucsc-transmappsltogenepred'
.. highlight: bash

ucsc-transmappsltogenepred
==========================

.. conda:recipe:: ucsc-transmappsltogenepred
   :replaces_section_title:

   convert PSL alignments of mRNAs to gene annotations.

   :homepage: http://hgdownload.cse.ucsc.edu/admin/exe/
   :license: varies; see http://genome.ucsc.edu/license
   :recipe: /`ucsc-transmappsltogenepred <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/ucsc-transmappsltogenepred>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/ucsc-transmappsltogenepred/meta.yaml>`_

   


.. conda:package:: ucsc-transmappsltogenepred

   |downloads_ucsc-transmappsltogenepred| |docker_ucsc-transmappsltogenepred|

   :versions: 377-0, 366-0, 357-2, 357-1, 357-0
   
   :depends libgcc-ng: >=7.3.0
   :depends libpng: >=1.6.35,<1.7.0a0
   :depends libuuid: >=2.32.1,<3.0a0
   :depends mysql-connector-c: 
   :depends openssl: >=1.0.2p,<1.0.3a
   :depends zlib: >=1.2.11,<1.3.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install ucsc-transmappsltogenepred

   and update with::

      conda update ucsc-transmappsltogenepred

   or use the docker container::

      docker pull quay.io/biocontainers/ucsc-transmappsltogenepred:<tag>

   (see `ucsc-transmappsltogenepred/tags`_ for valid values for ``<tag>``)


.. |downloads_ucsc-transmappsltogenepred| image:: https://img.shields.io/conda/dn/bioconda/ucsc-transmappsltogenepred.svg?style=flat
   :target: https://anaconda.org/bioconda/ucsc-transmappsltogenepred
   :alt:   (downloads)
.. |docker_ucsc-transmappsltogenepred| image:: https://quay.io/repository/biocontainers/ucsc-transmappsltogenepred/status
   :target: https://quay.io/repository/biocontainers/ucsc-transmappsltogenepred
.. _`ucsc-transmappsltogenepred/tags`: https://quay.io/repository/biocontainers/ucsc-transmappsltogenepred?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/ucsc-transmappsltogenepred/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/ucsc-transmappsltogenepred/README.html