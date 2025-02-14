:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-fantom3and4cage'
.. highlight: bash

bioconductor-fantom3and4cage
============================

.. conda:recipe:: bioconductor-fantom3and4cage
   :replaces_section_title:

   CAGE \(Cap Analysis Gene Expression\) data from FANTOM3 and FANTOM4 projects produced by RIKEN Omics Science Center.

   :homepage: https://bioconductor.org/packages/3.9/data/experiment/html/FANTOM3and4CAGE.html
   :license: GPL-3
   :recipe: /`bioconductor-fantom3and4cage <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-fantom3and4cage>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-fantom3and4cage/meta.yaml>`_

   


.. conda:package:: bioconductor-fantom3and4cage

   |downloads_bioconductor-fantom3and4cage| |docker_bioconductor-fantom3and4cage|

   :versions: 1.20.0-1, 1.20.0-0, 1.18.0-0
   
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-fantom3and4cage

   and update with::

      conda update bioconductor-fantom3and4cage

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-fantom3and4cage:<tag>

   (see `bioconductor-fantom3and4cage/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-fantom3and4cage| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-fantom3and4cage.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-fantom3and4cage
   :alt:   (downloads)
.. |docker_bioconductor-fantom3and4cage| image:: https://quay.io/repository/biocontainers/bioconductor-fantom3and4cage/status
   :target: https://quay.io/repository/biocontainers/bioconductor-fantom3and4cage
.. _`bioconductor-fantom3and4cage/tags`: https://quay.io/repository/biocontainers/bioconductor-fantom3and4cage?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-fantom3and4cage/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-fantom3and4cage/README.html