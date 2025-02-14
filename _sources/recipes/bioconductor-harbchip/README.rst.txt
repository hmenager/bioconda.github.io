:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-harbchip'
.. highlight: bash

bioconductor-harbchip
=====================

.. conda:recipe:: bioconductor-harbchip
   :replaces_section_title:

   data from a yeast ChIP\-chip experiment

   :homepage: https://bioconductor.org/packages/3.9/data/experiment/html/harbChIP.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-harbchip <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-harbchip>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-harbchip/meta.yaml>`_

   


.. conda:package:: bioconductor-harbchip

   |downloads_bioconductor-harbchip| |docker_bioconductor-harbchip|

   :versions: 1.22.0-1, 1.20.0-0
   
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends bioconductor-biostrings: >=2.52.0,<2.53.0
   :depends bioconductor-iranges: >=2.18.0,<2.19.0
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-harbchip

   and update with::

      conda update bioconductor-harbchip

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-harbchip:<tag>

   (see `bioconductor-harbchip/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-harbchip| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-harbchip.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-harbchip
   :alt:   (downloads)
.. |docker_bioconductor-harbchip| image:: https://quay.io/repository/biocontainers/bioconductor-harbchip/status
   :target: https://quay.io/repository/biocontainers/bioconductor-harbchip
.. _`bioconductor-harbchip/tags`: https://quay.io/repository/biocontainers/bioconductor-harbchip?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-harbchip/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-harbchip/README.html