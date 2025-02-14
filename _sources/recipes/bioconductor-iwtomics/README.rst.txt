:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-iwtomics'
.. highlight: bash

bioconductor-iwtomics
=====================

.. conda:recipe:: bioconductor-iwtomics
   :replaces_section_title:

   Implementation of the Interval\-Wise Testing \(IWT\) for omics data. This inferential procedure tests for differences in \"Omics\" data between two groups of genomic regions \(or between a group of genomic regions and a reference center of symmetry\)\, and does not require fixing location and scale at the outset.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/IWTomics.html
   :license: GPL (>=2)
   :recipe: /`bioconductor-iwtomics <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-iwtomics>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-iwtomics/meta.yaml>`_

   


.. conda:package:: bioconductor-iwtomics

   |downloads_bioconductor-iwtomics| |docker_bioconductor-iwtomics|

   :versions: 1.8.0-1, 1.6.0-0, 1.4.0-0, 1.2.0-0, 1.0.0-0
   
   :depends bioconductor-genomicranges: >=1.36.0,<1.37.0
   :depends bioconductor-iranges: >=2.18.0,<2.19.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-fda: 
   :depends r-gtable: 
   :depends r-kernsmooth: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-iwtomics

   and update with::

      conda update bioconductor-iwtomics

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-iwtomics:<tag>

   (see `bioconductor-iwtomics/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-iwtomics| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-iwtomics.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-iwtomics
   :alt:   (downloads)
.. |docker_bioconductor-iwtomics| image:: https://quay.io/repository/biocontainers/bioconductor-iwtomics/status
   :target: https://quay.io/repository/biocontainers/bioconductor-iwtomics
.. _`bioconductor-iwtomics/tags`: https://quay.io/repository/biocontainers/bioconductor-iwtomics?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-iwtomics/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-iwtomics/README.html