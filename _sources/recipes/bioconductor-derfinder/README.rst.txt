:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-derfinder'
.. highlight: bash

bioconductor-derfinder
======================

.. conda:recipe:: bioconductor-derfinder
   :replaces_section_title:

   Annotation\-agnostic differential expression analysis of RNA\-seq data at base\-pair resolution via the DER Finder approach

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/derfinder.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-derfinder <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-derfinder>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-derfinder/meta.yaml>`_
   :links: biotools: :biotools:`derfinder`

   This package provides functions for annotation\-agnostic differential 
   expression analysis of RNA\-seq data. Two implementations of the DER Finder 
   approach are included in this package\: \(1\) single base\-level F\-statistics 
   and \(2\) DER identification at the expressed regions\-level. The DER Finder 
   approach can also be used to identify differentially bounded ChIP\-seq peaks.



.. conda:package:: bioconductor-derfinder

   |downloads_bioconductor-derfinder| |docker_bioconductor-derfinder|

   :versions: 1.18.3-0, 1.16.1-0, 1.14.0-0, 1.12.0-0
   
   :depends bioconductor-annotationdbi: >=1.46.0,<1.47.0
   :depends bioconductor-biocgenerics: >=0.30.0,<0.31.0
   :depends bioconductor-biocparallel: >=1.18.0,<1.19.0
   :depends bioconductor-bumphunter: >=1.26.0,<1.27.0
   :depends bioconductor-derfinderhelper: >=1.18.0,<1.19.0
   :depends bioconductor-genomeinfodb: >=1.20.0,<1.21.0
   :depends bioconductor-genomicalignments: >=1.20.0,<1.21.0
   :depends bioconductor-genomicfeatures: >=1.36.0,<1.37.0
   :depends bioconductor-genomicfiles: >=1.20.0,<1.21.0
   :depends bioconductor-genomicranges: >=1.36.0,<1.37.0
   :depends bioconductor-iranges: >=2.18.0,<2.19.0
   :depends bioconductor-qvalue: >=2.16.0,<2.17.0
   :depends bioconductor-rsamtools: >=2.0.0,<2.1.0
   :depends bioconductor-rtracklayer: >=1.44.0,<1.45.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-hmisc: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-derfinder

   and update with::

      conda update bioconductor-derfinder

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-derfinder:<tag>

   (see `bioconductor-derfinder/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-derfinder| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-derfinder.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-derfinder
   :alt:   (downloads)
.. |docker_bioconductor-derfinder| image:: https://quay.io/repository/biocontainers/bioconductor-derfinder/status
   :target: https://quay.io/repository/biocontainers/bioconductor-derfinder
.. _`bioconductor-derfinder/tags`: https://quay.io/repository/biocontainers/bioconductor-derfinder?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-derfinder/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-derfinder/README.html