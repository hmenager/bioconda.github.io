:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-vcfarray'
.. highlight: bash

bioconductor-vcfarray
=====================

.. conda:recipe:: bioconductor-vcfarray
   :replaces_section_title:

   VCFArray extends the DelayedArray to represent VCF data entries as array\-like objects with on\-disk \/ remote VCF file as backend. Data entries from VCF files\, including info fields\, FORMAT fields\, and the fixed columns \(REF\, ALT\, QUAL\, FILTER\) could be converted into VCFArray instances with different dimensions.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/VCFArray.html
   :license: GPL-3
   :recipe: /`bioconductor-vcfarray <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-vcfarray>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-vcfarray/meta.yaml>`_

   


.. conda:package:: bioconductor-vcfarray

   |downloads_bioconductor-vcfarray| |docker_bioconductor-vcfarray|

   :versions: 1.0.3-0
   
   :depends bioconductor-biocgenerics: >=0.30.0,<0.31.0
   :depends bioconductor-delayedarray: >=0.10.0,<0.11.0
   :depends bioconductor-genomicfiles: >=1.20.0,<1.21.0
   :depends bioconductor-genomicranges: >=1.36.0,<1.37.0
   :depends bioconductor-rsamtools: >=2.0.0,<2.1.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends bioconductor-variantannotation: >=1.30.0,<1.31.0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-vcfarray

   and update with::

      conda update bioconductor-vcfarray

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-vcfarray:<tag>

   (see `bioconductor-vcfarray/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-vcfarray| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-vcfarray.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-vcfarray
   :alt:   (downloads)
.. |docker_bioconductor-vcfarray| image:: https://quay.io/repository/biocontainers/bioconductor-vcfarray/status
   :target: https://quay.io/repository/biocontainers/bioconductor-vcfarray
.. _`bioconductor-vcfarray/tags`: https://quay.io/repository/biocontainers/bioconductor-vcfarray?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-vcfarray/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-vcfarray/README.html