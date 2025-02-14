:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-rforproteomics'
.. highlight: bash

bioconductor-rforproteomics
===========================

.. conda:recipe:: bioconductor-rforproteomics
   :replaces_section_title:

   This package contains code to illustrate the \'Using R and Bioconductor for proteomics data analysis\' and \'Visualisation of proteomics data using R and Bioconductor\' manuscripts. The vignettes describe the code and data needed to reproduce the examples and figures described in the paper and functionality for proteomics visualisation. It also contain various function to discover R software for mass spectrometry and proteomics.

   :homepage: https://bioconductor.org/packages/3.9/data/experiment/html/RforProteomics.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-rforproteomics <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-rforproteomics>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-rforproteomics/meta.yaml>`_

   


.. conda:package:: bioconductor-rforproteomics

   |downloads_bioconductor-rforproteomics| |docker_bioconductor-rforproteomics|

   :versions: 1.22.0-1, 1.20.0-0
   
   :depends bioconductor-biocviews: >=1.52.0,<1.53.0
   :depends bioconductor-msnbase: >=2.10.0,<2.11.0
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-biocmanager: 
   :depends r-r.utils: 
   :depends r-shiny: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-rforproteomics

   and update with::

      conda update bioconductor-rforproteomics

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-rforproteomics:<tag>

   (see `bioconductor-rforproteomics/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-rforproteomics| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-rforproteomics.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-rforproteomics
   :alt:   (downloads)
.. |docker_bioconductor-rforproteomics| image:: https://quay.io/repository/biocontainers/bioconductor-rforproteomics/status
   :target: https://quay.io/repository/biocontainers/bioconductor-rforproteomics
.. _`bioconductor-rforproteomics/tags`: https://quay.io/repository/biocontainers/bioconductor-rforproteomics?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-rforproteomics/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-rforproteomics/README.html