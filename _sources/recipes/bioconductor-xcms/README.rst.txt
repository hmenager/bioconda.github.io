:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-xcms'
.. highlight: bash

bioconductor-xcms
=================

.. conda:recipe:: bioconductor-xcms
   :replaces_section_title:

   Framework for processing and visualization of chromatographically separated and single\-spectra mass spectral data. Imports from AIA\/ANDI NetCDF\, mzXML\, mzData and mzML files. Preprocesses data for high\-throughput\, untargeted analyte profiling.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/xcms.html
   :license: GPL (>= 2) + file LICENSE
   :recipe: /`bioconductor-xcms <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-xcms>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-xcms/meta.yaml>`_

   


.. conda:package:: bioconductor-xcms

   |downloads_bioconductor-xcms| |docker_bioconductor-xcms|

   :versions: 3.6.1-0, 3.4.4-0, 3.4.2-0, 3.4.1-0, 3.0.0-1, 3.0.0-0, 1.52.0-1, 1.52.0-0, 1.50.1-0, 1.48.0-1, 1.46.0-1, 1.46.0-0, 1.44.0-1, 1.44.0-0
   
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends bioconductor-biocgenerics: >=0.30.0,<0.31.0
   :depends bioconductor-biocparallel: >=1.18.0,<1.19.0
   :depends bioconductor-massspecwavelet: >=1.50.0,<1.51.0
   :depends bioconductor-msnbase: >=2.10.0,<2.11.0
   :depends bioconductor-multtest: >=2.40.0,<2.41.0
   :depends bioconductor-mzr: >=2.18.0,<2.19.0
   :depends bioconductor-protgenerics: >=1.16.0,<1.17.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends libgcc-ng: >=7.3.0
   :depends libstdcxx-ng: >=7.3.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-lattice: 
   :depends r-plyr: 
   :depends r-rann: 
   :depends r-rcolorbrewer: 
   :depends r-robustbase: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-xcms

   and update with::

      conda update bioconductor-xcms

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-xcms:<tag>

   (see `bioconductor-xcms/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-xcms| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-xcms.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-xcms
   :alt:   (downloads)
.. |docker_bioconductor-xcms| image:: https://quay.io/repository/biocontainers/bioconductor-xcms/status
   :target: https://quay.io/repository/biocontainers/bioconductor-xcms
.. _`bioconductor-xcms/tags`: https://quay.io/repository/biocontainers/bioconductor-xcms?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-xcms/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-xcms/README.html