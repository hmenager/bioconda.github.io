:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-esatac'
.. highlight: bash

bioconductor-esatac
===================

.. conda:recipe:: bioconductor-esatac
   :replaces_section_title:

   This package provides a framework and complete preset pipeline for quantification and analysis of ATAC\-seq Reads. It covers raw sequencing reads preprocessing \(FASTQ files\)\, reads alignment \(Rbowtie2\)\, aligned reads file operations \(SAM\, BAM\, and BED files\)\, peak calling \(F\-seq\)\, genome annotations \(Motif\, GO\, SNP analysis\) and quality control report. The package is managed by dataflow graph. It is easy for user to pass variables seamlessly between processes and understand the workflow. Users can process FASTQ files through end\-to\-end preset pipeline which produces a pretty HTML report for quality control and preliminary statistical results\, or customize workflow starting from any intermediate stages with esATAC functions easily and flexibly.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/esATAC.html
   :license: GPL-3 | file LICENSE
   :recipe: /`bioconductor-esatac <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-esatac>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-esatac/meta.yaml>`_

   


.. conda:package:: bioconductor-esatac

   |downloads_bioconductor-esatac| |docker_bioconductor-esatac|

   :versions: 1.6.1-0, 1.4.3-0, 1.4.0-0
   
   :depends bioconductor-annotationdbi: >=1.46.0,<1.47.0
   :depends bioconductor-biocgenerics: >=0.30.0,<0.31.0
   :depends bioconductor-biostrings: >=2.52.0,<2.53.0
   :depends bioconductor-bsgenome: >=1.52.0,<1.53.0
   :depends bioconductor-chipseeker: >=1.20.0,<1.21.0
   :depends bioconductor-clusterprofiler: >=3.12.0,<3.13.0
   :depends bioconductor-genomeinfodb: >=1.20.0,<1.21.0
   :depends bioconductor-genomicfeatures: >=1.36.0,<1.37.0
   :depends bioconductor-genomicranges: >=1.36.0,<1.37.0
   :depends bioconductor-iranges: >=2.18.0,<2.19.0
   :depends bioconductor-jaspar2016: >=1.12.0,<1.13.0
   :depends bioconductor-motifmatchr: >=1.6.0,<1.7.0
   :depends bioconductor-rbowtie2: >=1.6.0,<1.7.0
   :depends bioconductor-rsamtools: >=2.0.0,<2.1.0
   :depends bioconductor-rtracklayer: >=1.44.0,<1.45.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends bioconductor-shortread: >=1.42.0,<1.43.0
   :depends bioconductor-tfbstools: >=1.22.0,<1.23.0
   :depends libgcc-ng: >=7.3.0
   :depends libstdcxx-ng: >=7.3.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-biocmanager: 
   :depends r-corrplot: 
   :depends r-diagrammer: 
   :depends r-digest: 
   :depends r-ggplot2: 
   :depends r-igraph: 
   :depends r-knitr: 
   :depends r-magrittr: 
   :depends r-r.utils: 
   :depends r-rcpp: >=0.12.11
   :depends r-rjava: 
   :depends r-rmarkdown: 
   :depends r-venndiagram: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-esatac

   and update with::

      conda update bioconductor-esatac

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-esatac:<tag>

   (see `bioconductor-esatac/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-esatac| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-esatac.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-esatac
   :alt:   (downloads)
.. |docker_bioconductor-esatac| image:: https://quay.io/repository/biocontainers/bioconductor-esatac/status
   :target: https://quay.io/repository/biocontainers/bioconductor-esatac
.. _`bioconductor-esatac/tags`: https://quay.io/repository/biocontainers/bioconductor-esatac?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-esatac/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-esatac/README.html