:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'ucsc-xmlcat'
.. highlight: bash

ucsc-xmlcat
===========

.. conda:recipe:: ucsc-xmlcat
   :replaces_section_title:

   Concatenate xml files together\, stuffing all records inside a single outer tag. 

   :homepage: http://hgdownload.cse.ucsc.edu/admin/exe/
   :license: varies; see http://genome.ucsc.edu/license
   :recipe: /`ucsc-xmlcat <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/ucsc-xmlcat>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/ucsc-xmlcat/meta.yaml>`_

   


.. conda:package:: ucsc-xmlcat

   |downloads_ucsc-xmlcat| |docker_ucsc-xmlcat|

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

      conda install ucsc-xmlcat

   and update with::

      conda update ucsc-xmlcat

   or use the docker container::

      docker pull quay.io/biocontainers/ucsc-xmlcat:<tag>

   (see `ucsc-xmlcat/tags`_ for valid values for ``<tag>``)


.. |downloads_ucsc-xmlcat| image:: https://img.shields.io/conda/dn/bioconda/ucsc-xmlcat.svg?style=flat
   :target: https://anaconda.org/bioconda/ucsc-xmlcat
   :alt:   (downloads)
.. |docker_ucsc-xmlcat| image:: https://quay.io/repository/biocontainers/ucsc-xmlcat/status
   :target: https://quay.io/repository/biocontainers/ucsc-xmlcat
.. _`ucsc-xmlcat/tags`: https://quay.io/repository/biocontainers/ucsc-xmlcat?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/ucsc-xmlcat/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/ucsc-xmlcat/README.html