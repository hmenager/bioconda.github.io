:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'ucsc-pslpretty'
.. highlight: bash

ucsc-pslpretty
==============

.. conda:recipe:: ucsc-pslpretty
   :replaces_section_title:

   Convert PSL to human\-readable output

   :homepage: http://hgdownload.cse.ucsc.edu/admin/exe/
   :license: varies; see http://genome.ucsc.edu/license
   :recipe: /`ucsc-pslpretty <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/ucsc-pslpretty>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/ucsc-pslpretty/meta.yaml>`_

   


.. conda:package:: ucsc-pslpretty

   |downloads_ucsc-pslpretty| |docker_ucsc-pslpretty|

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

      conda install ucsc-pslpretty

   and update with::

      conda update ucsc-pslpretty

   or use the docker container::

      docker pull quay.io/biocontainers/ucsc-pslpretty:<tag>

   (see `ucsc-pslpretty/tags`_ for valid values for ``<tag>``)


.. |downloads_ucsc-pslpretty| image:: https://img.shields.io/conda/dn/bioconda/ucsc-pslpretty.svg?style=flat
   :target: https://anaconda.org/bioconda/ucsc-pslpretty
   :alt:   (downloads)
.. |docker_ucsc-pslpretty| image:: https://quay.io/repository/biocontainers/ucsc-pslpretty/status
   :target: https://quay.io/repository/biocontainers/ucsc-pslpretty
.. _`ucsc-pslpretty/tags`: https://quay.io/repository/biocontainers/ucsc-pslpretty?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/ucsc-pslpretty/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/ucsc-pslpretty/README.html