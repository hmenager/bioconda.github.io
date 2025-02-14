:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-wheatprobe'
.. highlight: bash

bioconductor-wheatprobe
=======================

.. conda:recipe:: bioconductor-wheatprobe
   :replaces_section_title:

   This package was automatically created by package AnnotationForge version 1.11.21. The probe sequence data was obtained from http\:\/\/www.affymetrix.com. The file name was wheat\\\_probe\\\_tab.

   :homepage: https://bioconductor.org/packages/3.9/data/annotation/html/wheatprobe.html
   :license: LGPL
   :recipe: /`bioconductor-wheatprobe <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-wheatprobe>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-wheatprobe/meta.yaml>`_

   


.. conda:package:: bioconductor-wheatprobe

   |downloads_bioconductor-wheatprobe| |docker_bioconductor-wheatprobe|

   :versions: 2.18.0-3, 2.18.0-1, 2.18.0-0
   
   :depends bioconductor-annotationdbi: >=1.46.0,<1.47.0
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-wheatprobe

   and update with::

      conda update bioconductor-wheatprobe

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-wheatprobe:<tag>

   (see `bioconductor-wheatprobe/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-wheatprobe| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-wheatprobe.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-wheatprobe
   :alt:   (downloads)
.. |docker_bioconductor-wheatprobe| image:: https://quay.io/repository/biocontainers/bioconductor-wheatprobe/status
   :target: https://quay.io/repository/biocontainers/bioconductor-wheatprobe
.. _`bioconductor-wheatprobe/tags`: https://quay.io/repository/biocontainers/bioconductor-wheatprobe?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-wheatprobe/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-wheatprobe/README.html