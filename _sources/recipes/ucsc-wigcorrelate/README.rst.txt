:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'ucsc-wigcorrelate'
.. highlight: bash

ucsc-wigcorrelate
=================

.. conda:recipe:: ucsc-wigcorrelate
   :replaces_section_title:

   Produce a table that correlates all pairs of wigs.

   :homepage: http://hgdownload.cse.ucsc.edu/admin/exe/
   :license: varies; see http://genome.ucsc.edu/license
   :recipe: /`ucsc-wigcorrelate <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/ucsc-wigcorrelate>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/ucsc-wigcorrelate/meta.yaml>`_

   


.. conda:package:: ucsc-wigcorrelate

   |downloads_ucsc-wigcorrelate| |docker_ucsc-wigcorrelate|

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

      conda install ucsc-wigcorrelate

   and update with::

      conda update ucsc-wigcorrelate

   or use the docker container::

      docker pull quay.io/biocontainers/ucsc-wigcorrelate:<tag>

   (see `ucsc-wigcorrelate/tags`_ for valid values for ``<tag>``)


.. |downloads_ucsc-wigcorrelate| image:: https://img.shields.io/conda/dn/bioconda/ucsc-wigcorrelate.svg?style=flat
   :target: https://anaconda.org/bioconda/ucsc-wigcorrelate
   :alt:   (downloads)
.. |docker_ucsc-wigcorrelate| image:: https://quay.io/repository/biocontainers/ucsc-wigcorrelate/status
   :target: https://quay.io/repository/biocontainers/ucsc-wigcorrelate
.. _`ucsc-wigcorrelate/tags`: https://quay.io/repository/biocontainers/ucsc-wigcorrelate?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/ucsc-wigcorrelate/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/ucsc-wigcorrelate/README.html