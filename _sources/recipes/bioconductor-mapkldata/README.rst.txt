:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-mapkldata'
.. highlight: bash

bioconductor-mapkldata
======================

.. conda:recipe:: bioconductor-mapkldata
   :replaces_section_title:

   Gene expression data from a breast cancer study published by Turashvili et al. in 2007\, provided as an eSet.

   :homepage: https://bioconductor.org/packages/3.9/data/experiment/html/mAPKLData.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-mapkldata <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-mapkldata>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-mapkldata/meta.yaml>`_

   


.. conda:package:: bioconductor-mapkldata

   |downloads_bioconductor-mapkldata| |docker_bioconductor-mapkldata|

   :versions: 1.16.0-1, 1.16.0-0, 1.14.0-0
   
   :depends curl: >=7.65.2,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-mapkldata

   and update with::

      conda update bioconductor-mapkldata

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-mapkldata:<tag>

   (see `bioconductor-mapkldata/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-mapkldata| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-mapkldata.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-mapkldata
   :alt:   (downloads)
.. |docker_bioconductor-mapkldata| image:: https://quay.io/repository/biocontainers/bioconductor-mapkldata/status
   :target: https://quay.io/repository/biocontainers/bioconductor-mapkldata
.. _`bioconductor-mapkldata/tags`: https://quay.io/repository/biocontainers/bioconductor-mapkldata?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-mapkldata/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-mapkldata/README.html