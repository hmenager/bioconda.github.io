:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'ucsc-bigwigcluster'
.. highlight: bash

ucsc-bigwigcluster
==================

.. conda:recipe:: ucsc-bigwigcluster
   :replaces_section_title:

   Cluster bigWigs using a hacTree

   :homepage: http://hgdownload.cse.ucsc.edu/admin/exe/
   :license: varies; see http://genome.ucsc.edu/license
   :recipe: /`ucsc-bigwigcluster <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/ucsc-bigwigcluster>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/ucsc-bigwigcluster/meta.yaml>`_

   


.. conda:package:: ucsc-bigwigcluster

   |downloads_ucsc-bigwigcluster| |docker_ucsc-bigwigcluster|

   :versions: 377-0, 366-0, 357-2, 357-1, 357-0, 332-0, 324-0
   
   :depends libgcc-ng: >=7.3.0
   :depends libpng: >=1.6.35,<1.7.0a0
   :depends libuuid: >=2.32.1,<3.0a0
   :depends mysql-connector-c: 
   :depends openssl: >=1.0.2p,<1.0.3a
   :depends zlib: >=1.2.11,<1.3.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install ucsc-bigwigcluster

   and update with::

      conda update ucsc-bigwigcluster

   or use the docker container::

      docker pull quay.io/biocontainers/ucsc-bigwigcluster:<tag>

   (see `ucsc-bigwigcluster/tags`_ for valid values for ``<tag>``)


.. |downloads_ucsc-bigwigcluster| image:: https://img.shields.io/conda/dn/bioconda/ucsc-bigwigcluster.svg?style=flat
   :target: https://anaconda.org/bioconda/ucsc-bigwigcluster
   :alt:   (downloads)
.. |docker_ucsc-bigwigcluster| image:: https://quay.io/repository/biocontainers/ucsc-bigwigcluster/status
   :target: https://quay.io/repository/biocontainers/ucsc-bigwigcluster
.. _`ucsc-bigwigcluster/tags`: https://quay.io/repository/biocontainers/ucsc-bigwigcluster?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/ucsc-bigwigcluster/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/ucsc-bigwigcluster/README.html