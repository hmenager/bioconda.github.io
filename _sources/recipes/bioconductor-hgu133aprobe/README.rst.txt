:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-hgu133aprobe'
.. highlight: bash

bioconductor-hgu133aprobe
=========================

.. conda:recipe:: bioconductor-hgu133aprobe
   :replaces_section_title:

   This package was automatically created by package AnnotationForge version 1.11.21. The probe sequence data was obtained from http\:\/\/www.affymetrix.com. The file name was HG\-U133A\\\_probe\\\_tab.

   :homepage: https://bioconductor.org/packages/3.9/data/annotation/html/hgu133aprobe.html
   :license: LGPL
   :recipe: /`bioconductor-hgu133aprobe <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-hgu133aprobe>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-hgu133aprobe/meta.yaml>`_

   


.. conda:package:: bioconductor-hgu133aprobe

   |downloads_bioconductor-hgu133aprobe| |docker_bioconductor-hgu133aprobe|

   :versions: 2.18.0-2, 2.18.0-0
   
   :depends bioconductor-annotationdbi: >=1.46.0,<1.47.0
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-hgu133aprobe

   and update with::

      conda update bioconductor-hgu133aprobe

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-hgu133aprobe:<tag>

   (see `bioconductor-hgu133aprobe/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-hgu133aprobe| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-hgu133aprobe.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-hgu133aprobe
   :alt:   (downloads)
.. |docker_bioconductor-hgu133aprobe| image:: https://quay.io/repository/biocontainers/bioconductor-hgu133aprobe/status
   :target: https://quay.io/repository/biocontainers/bioconductor-hgu133aprobe
.. _`bioconductor-hgu133aprobe/tags`: https://quay.io/repository/biocontainers/bioconductor-hgu133aprobe?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-hgu133aprobe/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-hgu133aprobe/README.html