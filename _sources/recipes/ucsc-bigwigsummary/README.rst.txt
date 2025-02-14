:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'ucsc-bigwigsummary'
.. highlight: bash

ucsc-bigwigsummary
==================

.. conda:recipe:: ucsc-bigwigsummary
   :replaces_section_title:

   Extract summary information from a bigWig file.

   :homepage: http://hgdownload.cse.ucsc.edu/admin/exe/
   :license: varies; see http://genome.ucsc.edu/license
   :recipe: /`ucsc-bigwigsummary <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/ucsc-bigwigsummary>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/ucsc-bigwigsummary/meta.yaml>`_

   


.. conda:package:: ucsc-bigwigsummary

   |downloads_ucsc-bigwigsummary| |docker_ucsc-bigwigsummary|

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

      conda install ucsc-bigwigsummary

   and update with::

      conda update ucsc-bigwigsummary

   or use the docker container::

      docker pull quay.io/biocontainers/ucsc-bigwigsummary:<tag>

   (see `ucsc-bigwigsummary/tags`_ for valid values for ``<tag>``)


.. |downloads_ucsc-bigwigsummary| image:: https://img.shields.io/conda/dn/bioconda/ucsc-bigwigsummary.svg?style=flat
   :target: https://anaconda.org/bioconda/ucsc-bigwigsummary
   :alt:   (downloads)
.. |docker_ucsc-bigwigsummary| image:: https://quay.io/repository/biocontainers/ucsc-bigwigsummary/status
   :target: https://quay.io/repository/biocontainers/ucsc-bigwigsummary
.. _`ucsc-bigwigsummary/tags`: https://quay.io/repository/biocontainers/ucsc-bigwigsummary?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/ucsc-bigwigsummary/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/ucsc-bigwigsummary/README.html