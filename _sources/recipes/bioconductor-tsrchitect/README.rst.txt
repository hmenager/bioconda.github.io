:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-tsrchitect'
.. highlight: bash

bioconductor-tsrchitect
=======================

.. conda:recipe:: bioconductor-tsrchitect
   :replaces_section_title:

   In recent years\, large\-scale transcriptional sequence data has yielded considerable insights into the nature of gene expression and regulation in eukaryotes. Techniques that identify the 5\' end of mRNAs\, most notably CAGE\, have mapped the promoter landscape across a number of model organisms. Due to the variability of TSS distributions and the transcriptional noise present in datasets\, precisely identifying the active promoter\(s\) for genes from these datasets is not straightforward. TSRchitect allows the user to efficiently identify the putative promoter \(the transcription start region\, or TSR\) from a variety of TSS profiling data types\, including both single\-end \(e.g. CAGE\) as well as paired\-end \(RAMPAGE\, PEAT\). In addition\, \(new with version 1.2.0\) TSRchitect provides the ability to import aligned EST and cDNA data. Along with the coordiantes of identified TSRs\, TSRchitect also calculates the width\, abundance and Shape Index\, and handles biological replicates for expression profiling. Finally\, TSRchitect imports annotation files\, allowing the user to associate identified promoters with genes and other genomic features. Three detailed examples of TSRchitect\'s utility are provided in the User\'s Guide\, included with this package.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/TSRchitect.html
   :license: GPL-3
   :recipe: /`bioconductor-tsrchitect <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-tsrchitect>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-tsrchitect/meta.yaml>`_

   


.. conda:package:: bioconductor-tsrchitect

   |downloads_bioconductor-tsrchitect| |docker_bioconductor-tsrchitect|

   :versions: 1.10.0-1, 1.8.9-0
   
   :depends bioconductor-annotationhub: >=2.16.0,<2.17.0
   :depends bioconductor-biocgenerics: >=0.30.0,<0.31.0
   :depends bioconductor-biocparallel: >=1.18.0,<1.19.0
   :depends bioconductor-genomeinfodb: >=1.20.0,<1.21.0
   :depends bioconductor-genomicalignments: >=1.20.0,<1.21.0
   :depends bioconductor-genomicranges: >=1.36.0,<1.37.0
   :depends bioconductor-iranges: >=2.18.0,<2.19.0
   :depends bioconductor-rsamtools: >=2.0.0,<2.1.0
   :depends bioconductor-rtracklayer: >=1.44.0,<1.45.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends bioconductor-summarizedexperiment: >=1.14.0,<1.15.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-gtools: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-tsrchitect

   and update with::

      conda update bioconductor-tsrchitect

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-tsrchitect:<tag>

   (see `bioconductor-tsrchitect/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-tsrchitect| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-tsrchitect.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-tsrchitect
   :alt:   (downloads)
.. |docker_bioconductor-tsrchitect| image:: https://quay.io/repository/biocontainers/bioconductor-tsrchitect/status
   :target: https://quay.io/repository/biocontainers/bioconductor-tsrchitect
.. _`bioconductor-tsrchitect/tags`: https://quay.io/repository/biocontainers/bioconductor-tsrchitect?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-tsrchitect/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-tsrchitect/README.html