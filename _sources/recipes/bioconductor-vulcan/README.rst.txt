:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-vulcan'
.. highlight: bash

bioconductor-vulcan
===================

.. conda:recipe:: bioconductor-vulcan
   :replaces_section_title:

   Vulcan \(VirtUaL ChIP\-Seq Analysis through Networks\) is a package that interrogates gene regulatory networks to infer cofactors significantly enriched in a differential binding signature coming from ChIP\-Seq data. In order to do so\, our package combines strategies from different BioConductor packages\: DESeq for data normalization\, ChIPpeakAnno and DiffBind for annotation and definition of ChIP\-Seq genomic peaks\, csaw to define optimal peak width and viper for applying a regulatory network over a differential binding signature.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/vulcan.html
   :license: LGPL-3
   :recipe: /`bioconductor-vulcan <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-vulcan>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-vulcan/meta.yaml>`_

   


.. conda:package:: bioconductor-vulcan

   |downloads_bioconductor-vulcan| |docker_bioconductor-vulcan|

   :versions: 1.6.0-1, 1.4.0-0
   
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends bioconductor-chippeakanno: >=3.18.0,<3.19.0
   :depends bioconductor-csaw: >=1.18.0,<1.19.0
   :depends bioconductor-deseq: >=1.36.0,<1.37.0
   :depends bioconductor-diffbind: >=2.12.0,<2.13.0
   :depends bioconductor-genomicranges: >=1.36.0,<1.37.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends bioconductor-txdb.hsapiens.ucsc.hg19.knowngene: >=3.2.0,<3.3.0
   :depends bioconductor-viper: >=1.18.0,<1.19.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-catools: 
   :depends r-gplots: 
   :depends r-locfit: 
   :depends r-wordcloud: 
   :depends r-zoo: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-vulcan

   and update with::

      conda update bioconductor-vulcan

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-vulcan:<tag>

   (see `bioconductor-vulcan/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-vulcan| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-vulcan.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-vulcan
   :alt:   (downloads)
.. |docker_bioconductor-vulcan| image:: https://quay.io/repository/biocontainers/bioconductor-vulcan/status
   :target: https://quay.io/repository/biocontainers/bioconductor-vulcan
.. _`bioconductor-vulcan/tags`: https://quay.io/repository/biocontainers/bioconductor-vulcan?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-vulcan/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-vulcan/README.html