:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-seqsetvis'
.. highlight: bash

bioconductor-seqsetvis
======================

.. conda:recipe:: bioconductor-seqsetvis
   :replaces_section_title:

   seqsetvis enables the visualization and analysis of multiple genomic samples. Although seqsetvis was designed for the comparison of mulitple ChIP\-seq samples\, this package is domain\-agnostic and allows the processing of multiple genomic coordinate files \(bed\-like files\) and signal files \(bigwig files or bam pileups\).

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/seqsetvis.html
   :license: MIT + file LICENSE
   :recipe: /`bioconductor-seqsetvis <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-seqsetvis>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-seqsetvis/meta.yaml>`_

   


.. conda:package:: bioconductor-seqsetvis

   |downloads_bioconductor-seqsetvis| |docker_bioconductor-seqsetvis|

   :versions: 1.4.0-1, 1.2.0-0
   
   :depends bioconductor-genomeinfodb: >=1.20.0,<1.21.0
   :depends bioconductor-genomicalignments: >=1.20.0,<1.21.0
   :depends bioconductor-genomicranges: >=1.36.0,<1.37.0
   :depends bioconductor-iranges: >=2.18.0,<2.19.0
   :depends bioconductor-limma: >=3.40.0,<3.41.0
   :depends bioconductor-rsamtools: >=2.0.0,<2.1.0
   :depends bioconductor-rtracklayer: >=1.44.0,<1.45.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-data.table: 
   :depends r-eulerr: 
   :depends r-ggplot2: 
   :depends r-pbapply: 
   :depends r-png: 
   :depends r-rcolorbrewer: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-seqsetvis

   and update with::

      conda update bioconductor-seqsetvis

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-seqsetvis:<tag>

   (see `bioconductor-seqsetvis/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-seqsetvis| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-seqsetvis.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-seqsetvis
   :alt:   (downloads)
.. |docker_bioconductor-seqsetvis| image:: https://quay.io/repository/biocontainers/bioconductor-seqsetvis/status
   :target: https://quay.io/repository/biocontainers/bioconductor-seqsetvis
.. _`bioconductor-seqsetvis/tags`: https://quay.io/repository/biocontainers/bioconductor-seqsetvis?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-seqsetvis/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-seqsetvis/README.html