:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'ucsc-bigwigaverageoverbed'
.. highlight: bash

ucsc-bigwigaverageoverbed
=========================

.. conda:recipe:: ucsc-bigwigaverageoverbed
   :replaces_section_title:

   Compute average score of big wig over each bed\, which may have introns.

   :homepage: http://hgdownload.cse.ucsc.edu/admin/exe/
   :license: varies; see http://genome.ucsc.edu/license
   :recipe: /`ucsc-bigwigaverageoverbed <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/ucsc-bigwigaverageoverbed>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/ucsc-bigwigaverageoverbed/meta.yaml>`_

   


.. conda:package:: ucsc-bigwigaverageoverbed

   |downloads_ucsc-bigwigaverageoverbed| |docker_ucsc-bigwigaverageoverbed|

   :versions: 377-0, 366-0, 357-1, 357-0, 332-0, 324-0
   
   :depends libgcc-ng: >=7.3.0
   :depends libpng: >=1.6.35,<1.7.0a0
   :depends libuuid: >=2.32.1,<3.0a0
   :depends mysql-connector-c: 
   :depends openssl: >=1.0.2p,<1.0.3a
   :depends zlib: >=1.2.11,<1.3.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install ucsc-bigwigaverageoverbed

   and update with::

      conda update ucsc-bigwigaverageoverbed

   or use the docker container::

      docker pull quay.io/biocontainers/ucsc-bigwigaverageoverbed:<tag>

   (see `ucsc-bigwigaverageoverbed/tags`_ for valid values for ``<tag>``)


.. |downloads_ucsc-bigwigaverageoverbed| image:: https://img.shields.io/conda/dn/bioconda/ucsc-bigwigaverageoverbed.svg?style=flat
   :target: https://anaconda.org/bioconda/ucsc-bigwigaverageoverbed
   :alt:   (downloads)
.. |docker_ucsc-bigwigaverageoverbed| image:: https://quay.io/repository/biocontainers/ucsc-bigwigaverageoverbed/status
   :target: https://quay.io/repository/biocontainers/ucsc-bigwigaverageoverbed
.. _`ucsc-bigwigaverageoverbed/tags`: https://quay.io/repository/biocontainers/ucsc-bigwigaverageoverbed?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/ucsc-bigwigaverageoverbed/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/ucsc-bigwigaverageoverbed/README.html