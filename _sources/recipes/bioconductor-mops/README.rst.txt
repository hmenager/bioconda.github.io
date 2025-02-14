:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-mops'
.. highlight: bash

bioconductor-mops
=================

.. conda:recipe:: bioconductor-mops
   :replaces_section_title:

   Identification and characterization of periodic fluctuations in time\-series data.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/MoPS.html
   :license: GPL-3
   :recipe: /`bioconductor-mops <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-mops>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-mops/meta.yaml>`_
   :links: biotools: :biotools:`mops`, doi: :doi:`10.1002/msb.134886`

   


.. conda:package:: bioconductor-mops

   |downloads_bioconductor-mops| |docker_bioconductor-mops|

   :versions: 1.18.0-1, 1.16.0-0, 1.14.0-0, 1.12.0-0, 1.10.0-0
   
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-mops

   and update with::

      conda update bioconductor-mops

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-mops:<tag>

   (see `bioconductor-mops/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-mops| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-mops.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-mops
   :alt:   (downloads)
.. |docker_bioconductor-mops| image:: https://quay.io/repository/biocontainers/bioconductor-mops/status
   :target: https://quay.io/repository/biocontainers/bioconductor-mops
.. _`bioconductor-mops/tags`: https://quay.io/repository/biocontainers/bioconductor-mops?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-mops/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-mops/README.html