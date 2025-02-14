:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-agprobe'
.. highlight: bash

bioconductor-agprobe
====================

.. conda:recipe:: bioconductor-agprobe
   :replaces_section_title:

   This package was automatically created by package AnnotationForge version 1.11.21. The probe sequence data was obtained from http\:\/\/www.affymetrix.com. The file name was AG\\\_probe\\\_tab.

   :homepage: https://bioconductor.org/packages/3.9/data/annotation/html/agprobe.html
   :license: LGPL
   :recipe: /`bioconductor-agprobe <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-agprobe>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-agprobe/meta.yaml>`_

   


.. conda:package:: bioconductor-agprobe

   |downloads_bioconductor-agprobe| |docker_bioconductor-agprobe|

   :versions: 2.18.0-2, 2.18.0-0
   
   :depends bioconductor-annotationdbi: >=1.46.0,<1.47.0
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-agprobe

   and update with::

      conda update bioconductor-agprobe

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-agprobe:<tag>

   (see `bioconductor-agprobe/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-agprobe| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-agprobe.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-agprobe
   :alt:   (downloads)
.. |docker_bioconductor-agprobe| image:: https://quay.io/repository/biocontainers/bioconductor-agprobe/status
   :target: https://quay.io/repository/biocontainers/bioconductor-agprobe
.. _`bioconductor-agprobe/tags`: https://quay.io/repository/biocontainers/bioconductor-agprobe?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-agprobe/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-agprobe/README.html