:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-pwmenrich.hsapiens.background'
.. highlight: bash

bioconductor-pwmenrich.hsapiens.background
==========================================

.. conda:recipe:: bioconductor-pwmenrich.hsapiens.background
   :replaces_section_title:

   PWMEnrich pre\-compiled background objects for H. sapiens \(human\) and MotifDb H. sapiens motifs.

   :homepage: https://bioconductor.org/packages/3.9/data/experiment/html/PWMEnrich.Hsapiens.background.html
   :license: GPL-3
   :recipe: /`bioconductor-pwmenrich.hsapiens.background <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-pwmenrich.hsapiens.background>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-pwmenrich.hsapiens.background/meta.yaml>`_

   


.. conda:package:: bioconductor-pwmenrich.hsapiens.background

   |downloads_bioconductor-pwmenrich.hsapiens.background| |docker_bioconductor-pwmenrich.hsapiens.background|

   :versions: 4.18.0-1, 4.16.0-0
   
   :depends bioconductor-pwmenrich: >=4.20.0,<4.21.0
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-pwmenrich.hsapiens.background

   and update with::

      conda update bioconductor-pwmenrich.hsapiens.background

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-pwmenrich.hsapiens.background:<tag>

   (see `bioconductor-pwmenrich.hsapiens.background/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-pwmenrich.hsapiens.background| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-pwmenrich.hsapiens.background.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-pwmenrich.hsapiens.background
   :alt:   (downloads)
.. |docker_bioconductor-pwmenrich.hsapiens.background| image:: https://quay.io/repository/biocontainers/bioconductor-pwmenrich.hsapiens.background/status
   :target: https://quay.io/repository/biocontainers/bioconductor-pwmenrich.hsapiens.background
.. _`bioconductor-pwmenrich.hsapiens.background/tags`: https://quay.io/repository/biocontainers/bioconductor-pwmenrich.hsapiens.background?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-pwmenrich.hsapiens.background/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-pwmenrich.hsapiens.background/README.html