:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-qdnaseq.mm10'
.. highlight: bash

bioconductor-qdnaseq.mm10
=========================

.. conda:recipe:: bioconductor-qdnaseq.mm10
   :replaces_section_title:

   This package provides QDNAseq bin annotations for the mouse genome build mm10.

   :homepage: https://bioconductor.org/packages/3.9/data/experiment/html/QDNAseq.mm10.html
   :license: GPL
   :recipe: /`bioconductor-qdnaseq.mm10 <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-qdnaseq.mm10>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-qdnaseq.mm10/meta.yaml>`_

   


.. conda:package:: bioconductor-qdnaseq.mm10

   |downloads_bioconductor-qdnaseq.mm10| |docker_bioconductor-qdnaseq.mm10|

   :versions: 1.14.0-1, 1.12.0-0, 1.10.0-0, 1.8.0-1, 1.8.0-0, 1.6.0-16, 1.4.0-1, 1.4.0-0
   
   :depends bioconductor-qdnaseq: >=1.20.0,<1.21.0
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-qdnaseq.mm10

   and update with::

      conda update bioconductor-qdnaseq.mm10

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-qdnaseq.mm10:<tag>

   (see `bioconductor-qdnaseq.mm10/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-qdnaseq.mm10| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-qdnaseq.mm10.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-qdnaseq.mm10
   :alt:   (downloads)
.. |docker_bioconductor-qdnaseq.mm10| image:: https://quay.io/repository/biocontainers/bioconductor-qdnaseq.mm10/status
   :target: https://quay.io/repository/biocontainers/bioconductor-qdnaseq.mm10
.. _`bioconductor-qdnaseq.mm10/tags`: https://quay.io/repository/biocontainers/bioconductor-qdnaseq.mm10?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-qdnaseq.mm10/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-qdnaseq.mm10/README.html