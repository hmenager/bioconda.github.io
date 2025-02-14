:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-beachmat'
.. highlight: bash

bioconductor-beachmat
=====================

.. conda:recipe:: bioconductor-beachmat
   :replaces_section_title:

   Provides a consistent C\+\+ class interface for reading from and writing data to a variety of commonly used matrix types. Ordinary matrices and several sparse\/dense Matrix classes are directly supported\, third\-party S4 classes may be supported by external linkage\, while all other matrices are handled by DelayedArray block processing.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/beachmat.html
   :license: GPL-3
   :recipe: /`bioconductor-beachmat <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-beachmat>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-beachmat/meta.yaml>`_

   


.. conda:package:: bioconductor-beachmat

   |downloads_bioconductor-beachmat| |docker_bioconductor-beachmat|

   :versions: 2.0.0-1, 1.4.0-1, 1.4.0-0, 1.2.1-0, 1.0.1-0
   
   :depends bioconductor-biocgenerics: >=0.30.0,<0.31.0
   :depends bioconductor-delayedarray: >=0.10.0,<0.11.0
   :depends libgcc-ng: >=7.3.0
   :depends libstdcxx-ng: >=7.3.0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-beachmat

   and update with::

      conda update bioconductor-beachmat

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-beachmat:<tag>

   (see `bioconductor-beachmat/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-beachmat| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-beachmat.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-beachmat
   :alt:   (downloads)
.. |docker_bioconductor-beachmat| image:: https://quay.io/repository/biocontainers/bioconductor-beachmat/status
   :target: https://quay.io/repository/biocontainers/bioconductor-beachmat
.. _`bioconductor-beachmat/tags`: https://quay.io/repository/biocontainers/bioconductor-beachmat?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-beachmat/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-beachmat/README.html