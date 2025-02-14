:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-gwasdata'
.. highlight: bash

bioconductor-gwasdata
=====================

.. conda:recipe:: bioconductor-gwasdata
   :replaces_section_title:

   Selected Affymetrix and Illlumina SNP data for HapMap subjects.  Data provided by the Center for Inherited Disease Research at Johns Hopkins University and the Broad Institute of MIT and Harvard University.

   :homepage: https://bioconductor.org/packages/3.9/data/experiment/html/GWASdata.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-gwasdata <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-gwasdata>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-gwasdata/meta.yaml>`_

   


.. conda:package:: bioconductor-gwasdata

   |downloads_bioconductor-gwasdata| |docker_bioconductor-gwasdata|

   :versions: 1.22.0-1, 1.20.0-0
   
   :depends bioconductor-gwastools: >=1.30.0,<1.31.0
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-gwasdata

   and update with::

      conda update bioconductor-gwasdata

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-gwasdata:<tag>

   (see `bioconductor-gwasdata/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-gwasdata| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-gwasdata.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-gwasdata
   :alt:   (downloads)
.. |docker_bioconductor-gwasdata| image:: https://quay.io/repository/biocontainers/bioconductor-gwasdata/status
   :target: https://quay.io/repository/biocontainers/bioconductor-gwasdata
.. _`bioconductor-gwasdata/tags`: https://quay.io/repository/biocontainers/bioconductor-gwasdata?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-gwasdata/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-gwasdata/README.html