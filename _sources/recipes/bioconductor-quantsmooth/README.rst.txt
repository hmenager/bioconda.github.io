:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-quantsmooth'
.. highlight: bash

bioconductor-quantsmooth
========================

.. conda:recipe:: bioconductor-quantsmooth
   :replaces_section_title:

   Implements quantile smoothing as introduced in\: Quantile smoothing of array CGH data\; Eilers PH\, de Menezes RX\; Bioinformatics. 2005 Apr 1\;21\(7\)\:1146\-53.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/quantsmooth.html
   :license: GPL-2
   :recipe: /`bioconductor-quantsmooth <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-quantsmooth>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-quantsmooth/meta.yaml>`_
   :links: biotools: :biotools:`quantsmooth`, doi: :doi:`10.1038/nmeth.3252`

   


.. conda:package:: bioconductor-quantsmooth

   |downloads_bioconductor-quantsmooth| |docker_bioconductor-quantsmooth|

   :versions: 1.50.0-1, 1.50.0-0, 1.48.0-0, 1.46.0-0, 1.44.0-0, 1.42.0-0
   
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-quantreg: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-quantsmooth

   and update with::

      conda update bioconductor-quantsmooth

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-quantsmooth:<tag>

   (see `bioconductor-quantsmooth/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-quantsmooth| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-quantsmooth.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-quantsmooth
   :alt:   (downloads)
.. |docker_bioconductor-quantsmooth| image:: https://quay.io/repository/biocontainers/bioconductor-quantsmooth/status
   :target: https://quay.io/repository/biocontainers/bioconductor-quantsmooth
.. _`bioconductor-quantsmooth/tags`: https://quay.io/repository/biocontainers/bioconductor-quantsmooth?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-quantsmooth/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-quantsmooth/README.html