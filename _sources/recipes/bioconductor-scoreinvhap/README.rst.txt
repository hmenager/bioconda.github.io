:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-scoreinvhap'
.. highlight: bash

bioconductor-scoreinvhap
========================

.. conda:recipe:: bioconductor-scoreinvhap
   :replaces_section_title:

   scoreInvHap can get the samples\' inversion status of known inversions. scoreInvHap uses SNP data as input and requires the following information about the inversion\: genotype frequencies in the different haplotypes\, R2 between the region SNPs and inversion status and heterozygote genotypes in the reference. The package include this data for two well known inversions \(8p23 and 17q21.31\) and for two additional regions.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/scoreInvHap.html
   :license: file LICENSE
   :recipe: /`bioconductor-scoreinvhap <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-scoreinvhap>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-scoreinvhap/meta.yaml>`_

   


.. conda:package:: bioconductor-scoreinvhap

   |downloads_bioconductor-scoreinvhap| |docker_bioconductor-scoreinvhap|

   :versions: 1.6.0-1, 1.4.0-0
   
   :depends bioconductor-biocparallel: >=1.18.0,<1.19.0
   :depends bioconductor-biostrings: >=2.52.0,<2.53.0
   :depends bioconductor-genomicranges: >=1.36.0,<1.37.0
   :depends bioconductor-snpstats: >=1.34.0,<1.35.0
   :depends bioconductor-summarizedexperiment: >=1.14.0,<1.15.0
   :depends bioconductor-variantannotation: >=1.30.0,<1.31.0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-scoreinvhap

   and update with::

      conda update bioconductor-scoreinvhap

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-scoreinvhap:<tag>

   (see `bioconductor-scoreinvhap/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-scoreinvhap| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-scoreinvhap.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-scoreinvhap
   :alt:   (downloads)
.. |docker_bioconductor-scoreinvhap| image:: https://quay.io/repository/biocontainers/bioconductor-scoreinvhap/status
   :target: https://quay.io/repository/biocontainers/bioconductor-scoreinvhap
.. _`bioconductor-scoreinvhap/tags`: https://quay.io/repository/biocontainers/bioconductor-scoreinvhap?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-scoreinvhap/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-scoreinvhap/README.html