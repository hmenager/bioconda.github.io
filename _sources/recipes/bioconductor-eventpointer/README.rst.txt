:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-eventpointer'
.. highlight: bash

bioconductor-eventpointer
=========================

.. conda:recipe:: bioconductor-eventpointer
   :replaces_section_title:

   EventPointer is an R package to identify alternative splicing events that involve either simple \(case\-control experiment\) or complex experimental designs such as time course experiments and studies including paired\-samples. The algorithm can be used to analyze data from either junction arrays \(Affymetrix Arrays\) or sequencing data \(RNA\-Seq\). The software returns a data.frame with the detected alternative splicing events\: gene name\, type of event \(cassette\, alternative 3\'\,...\,etc\)\, genomic position\, statistical significance and increment of the percent spliced in \(Delta PSI\) for all the events. The algorithm can generate a series of files to visualize the detected alternative splicing events in IGV. This eases the interpretation of results and the design of primers for standard PCR validation.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/EventPointer.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-eventpointer <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-eventpointer>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-eventpointer/meta.yaml>`_

   


.. conda:package:: bioconductor-eventpointer

   |downloads_bioconductor-eventpointer| |docker_bioconductor-eventpointer|

   :versions: 2.2.4-0, 2.0.1-0
   
   :depends bioconductor-affxparser: >=1.56.0,<1.57.0
   :depends bioconductor-biostrings: >=2.52.0,<2.53.0
   :depends bioconductor-bsgenome: >=1.52.0,<1.53.0
   :depends bioconductor-bsgenome.hsapiens.ucsc.hg38: >=1.4.0,<1.5.0
   :depends bioconductor-genomeinfodb: >=1.20.0,<1.21.0
   :depends bioconductor-genomicfeatures: >=1.36.0,<1.37.0
   :depends bioconductor-genomicranges: >=1.36.0,<1.37.0
   :depends bioconductor-graph: >=1.62.0,<1.63.0
   :depends bioconductor-iranges: >=2.18.0,<2.19.0
   :depends bioconductor-limma: >=3.40.0,<3.41.0
   :depends bioconductor-qvalue: >=2.16.0,<2.17.0
   :depends bioconductor-rbgl: >=1.60.0,<1.61.0
   :depends bioconductor-rhdf5: >=2.28.0,<2.29.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends bioconductor-sgseq: >=1.18.0,<1.19.0
   :depends bioconductor-summarizedexperiment: >=1.14.0,<1.15.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-cobs: 
   :depends r-doparallel: 
   :depends r-foreach: 
   :depends r-igraph: 
   :depends r-mass: 
   :depends r-matrix: 
   :depends r-matrixstats: 
   :depends r-nnls: 
   :depends r-prodlim: 
   :depends r-stringr: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-eventpointer

   and update with::

      conda update bioconductor-eventpointer

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-eventpointer:<tag>

   (see `bioconductor-eventpointer/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-eventpointer| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-eventpointer.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-eventpointer
   :alt:   (downloads)
.. |docker_bioconductor-eventpointer| image:: https://quay.io/repository/biocontainers/bioconductor-eventpointer/status
   :target: https://quay.io/repository/biocontainers/bioconductor-eventpointer
.. _`bioconductor-eventpointer/tags`: https://quay.io/repository/biocontainers/bioconductor-eventpointer?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-eventpointer/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-eventpointer/README.html