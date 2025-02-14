:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'ucsc-chainbridge'
.. highlight: bash

ucsc-chainbridge
================

.. conda:recipe:: ucsc-chainbridge
   :replaces_section_title:

   Attempt to extend alignments through double\-sided gaps of similar size

   :homepage: http://hgdownload.cse.ucsc.edu/admin/exe/
   :license: varies; see http://genome.ucsc.edu/license
   :recipe: /`ucsc-chainbridge <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/ucsc-chainbridge>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/ucsc-chainbridge/meta.yaml>`_

   


.. conda:package:: ucsc-chainbridge

   |downloads_ucsc-chainbridge| |docker_ucsc-chainbridge|

   :versions: 377-0
   
   :depends libgcc-ng: >=7.3.0
   :depends libpng: >=1.6.35,<1.7.0a0
   :depends libuuid: >=2.32.1,<3.0a0
   :depends mysql-connector-c: 
   :depends openssl: >=1.0.2p,<1.0.3a
   :depends zlib: >=1.2.11,<1.3.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install ucsc-chainbridge

   and update with::

      conda update ucsc-chainbridge

   or use the docker container::

      docker pull quay.io/biocontainers/ucsc-chainbridge:<tag>

   (see `ucsc-chainbridge/tags`_ for valid values for ``<tag>``)


.. |downloads_ucsc-chainbridge| image:: https://img.shields.io/conda/dn/bioconda/ucsc-chainbridge.svg?style=flat
   :target: https://anaconda.org/bioconda/ucsc-chainbridge
   :alt:   (downloads)
.. |docker_ucsc-chainbridge| image:: https://quay.io/repository/biocontainers/ucsc-chainbridge/status
   :target: https://quay.io/repository/biocontainers/ucsc-chainbridge
.. _`ucsc-chainbridge/tags`: https://quay.io/repository/biocontainers/ucsc-chainbridge?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/ucsc-chainbridge/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/ucsc-chainbridge/README.html