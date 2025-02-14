:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-hapmap370k'
.. highlight: bash

bioconductor-hapmap370k
=======================

.. conda:recipe:: bioconductor-hapmap370k
   :replaces_section_title:

   Example HapMap data from Illumina 370k BeadChips

   :homepage: https://bioconductor.org/packages/3.9/data/annotation/html/hapmap370k.html
   :license: GPL
   :recipe: /`bioconductor-hapmap370k <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-hapmap370k>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-hapmap370k/meta.yaml>`_

   


.. conda:package:: bioconductor-hapmap370k

   |downloads_bioconductor-hapmap370k| |docker_bioconductor-hapmap370k|

   :versions: 1.0.1-2, 1.0.1-1, 1.0.1-0
   
   :depends curl: >=7.65.2,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-hapmap370k

   and update with::

      conda update bioconductor-hapmap370k

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-hapmap370k:<tag>

   (see `bioconductor-hapmap370k/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-hapmap370k| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-hapmap370k.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-hapmap370k
   :alt:   (downloads)
.. |docker_bioconductor-hapmap370k| image:: https://quay.io/repository/biocontainers/bioconductor-hapmap370k/status
   :target: https://quay.io/repository/biocontainers/bioconductor-hapmap370k
.. _`bioconductor-hapmap370k/tags`: https://quay.io/repository/biocontainers/bioconductor-hapmap370k?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-hapmap370k/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-hapmap370k/README.html