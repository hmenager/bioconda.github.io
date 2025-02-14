:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-calib'
.. highlight: bash

bioconductor-calib
==================

.. conda:recipe:: bioconductor-calib
   :replaces_section_title:

   This package contains functions for normalizing spotted microarray data\, based on a physically motivated calibration model. The model parameters and error distributions are estimated from external control spikes.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/CALIB.html
   :license: LGPL
   :recipe: /`bioconductor-calib <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-calib>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-calib/meta.yaml>`_
   :links: biotools: :biotools:`calib`, doi: :doi:`10.1093/bioinformatics/btm159`

   


.. conda:package:: bioconductor-calib

   |downloads_bioconductor-calib| |docker_bioconductor-calib|

   :versions: 1.50.0-1, 1.50.0-0, 1.48.0-0, 1.46.0-0, 1.44.0-0, 1.42.0-0
   
   :depends bioconductor-limma: >=3.40.0,<3.41.0
   :depends libgcc-ng: >=7.3.0
   :depends libstdcxx-ng: >=7.3.0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-calib

   and update with::

      conda update bioconductor-calib

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-calib:<tag>

   (see `bioconductor-calib/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-calib| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-calib.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-calib
   :alt:   (downloads)
.. |docker_bioconductor-calib| image:: https://quay.io/repository/biocontainers/bioconductor-calib/status
   :target: https://quay.io/repository/biocontainers/bioconductor-calib
.. _`bioconductor-calib/tags`: https://quay.io/repository/biocontainers/bioconductor-calib?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-calib/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-calib/README.html