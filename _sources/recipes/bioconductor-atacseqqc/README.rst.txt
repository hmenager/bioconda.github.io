:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-atacseqqc'
.. highlight: bash

bioconductor-atacseqqc
======================

.. conda:recipe:: bioconductor-atacseqqc
   :replaces_section_title:

   ATAC\-seq\, an assay for Transposase\-Accessible Chromatin using sequencing\, is a rapid and sensitive method for chromatin accessibility analysis. It was developed as an alternative method to MNase\-seq\, FAIRE\-seq and DNAse\-seq. Comparing to the other methods\, ATAC\-seq requires less amount of the biological samples and time to process. In the process of analyzing several ATAC\-seq dataset produced in our labs\, we learned some of the unique aspects of the quality assessment for ATAC\-seq data.To help users to quickly assess whether their ATAC\-seq experiment is successful\, we developed ATACseqQC package partially following the guideline published in Nature Method 2013 \(Greenleaf et al.\)\, including diagnostic plot of fragment size distribution\, proportion of mitochondria reads\, nucleosome positioning pattern\, and CTCF or other Transcript Factor footprints.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/ATACseqQC.html
   :license: GPL (>= 2)
   :recipe: /`bioconductor-atacseqqc <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-atacseqqc>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-atacseqqc/meta.yaml>`_

   


.. conda:package:: bioconductor-atacseqqc

   |downloads_bioconductor-atacseqqc| |docker_bioconductor-atacseqqc|

   :versions: 1.8.5-0, 1.6.4-0, 1.4.3-0, 1.2.0-0, 1.0.5-0
   
   :depends bioconductor-biocgenerics: >=0.30.0,<0.31.0
   :depends bioconductor-biostrings: >=2.52.0,<2.53.0
   :depends bioconductor-bsgenome: >=1.52.0,<1.53.0
   :depends bioconductor-chippeakanno: >=3.18.0,<3.19.0
   :depends bioconductor-edger: >=3.26.0,<3.27.0
   :depends bioconductor-genomeinfodb: >=1.20.0,<1.21.0
   :depends bioconductor-genomicalignments: >=1.20.0,<1.21.0
   :depends bioconductor-genomicranges: >=1.36.0,<1.37.0
   :depends bioconductor-genomicscores: >=1.8.0,<1.9.0
   :depends bioconductor-iranges: >=2.18.0,<2.19.0
   :depends bioconductor-limma: >=3.40.0,<3.41.0
   :depends bioconductor-motifstack: >=1.28.0,<1.29.0
   :depends bioconductor-rsamtools: >=2.0.0,<2.1.0
   :depends bioconductor-rtracklayer: >=1.44.0,<1.45.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-kernsmooth: 
   :depends r-preseqr: 
   :depends r-randomforest: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-atacseqqc

   and update with::

      conda update bioconductor-atacseqqc

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-atacseqqc:<tag>

   (see `bioconductor-atacseqqc/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-atacseqqc| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-atacseqqc.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-atacseqqc
   :alt:   (downloads)
.. |docker_bioconductor-atacseqqc| image:: https://quay.io/repository/biocontainers/bioconductor-atacseqqc/status
   :target: https://quay.io/repository/biocontainers/bioconductor-atacseqqc
.. _`bioconductor-atacseqqc/tags`: https://quay.io/repository/biocontainers/bioconductor-atacseqqc?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-atacseqqc/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-atacseqqc/README.html