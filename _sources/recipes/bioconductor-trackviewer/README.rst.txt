:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-trackviewer'
.. highlight: bash

bioconductor-trackviewer
========================

.. conda:recipe:: bioconductor-trackviewer
   :replaces_section_title:

   Visualize mapped reads along with annotation as track layers for NGS dataset such as ChIP\-seq\, RNA\-seq\, miRNA\-seq\, DNA\-seq\, SNPs and methylation data.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/trackViewer.html
   :license: GPL (>= 2)
   :recipe: /`bioconductor-trackviewer <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-trackviewer>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-trackviewer/meta.yaml>`_
   :links: biotools: :biotools:`trackviewer`, doi: :doi:`10.1038/nmeth.3252`

   


.. conda:package:: bioconductor-trackviewer

   |downloads_bioconductor-trackviewer| |docker_bioconductor-trackviewer|

   :versions: 1.20.5-0, 1.18.0-1, 1.18.0-0, 1.16.1-0, 1.14.1-0
   
   :depends bioconductor-annotationdbi: >=1.46.0,<1.47.0
   :depends bioconductor-biocgenerics: >=0.30.0,<0.31.0
   :depends bioconductor-genomeinfodb: >=1.20.0,<1.21.0
   :depends bioconductor-genomicalignments: >=1.20.0,<1.21.0
   :depends bioconductor-genomicfeatures: >=1.36.0,<1.37.0
   :depends bioconductor-genomicranges: >=1.36.0,<1.37.0
   :depends bioconductor-graph: >=1.62.0,<1.63.0
   :depends bioconductor-gviz: >=1.28.0,<1.29.0
   :depends bioconductor-interactionset: >=1.12.0,<1.13.0
   :depends bioconductor-iranges: >=2.18.0,<2.19.0
   :depends bioconductor-rgraphviz: >=2.28.0,<2.29.0
   :depends bioconductor-rsamtools: >=2.0.0,<2.1.0
   :depends bioconductor-rtracklayer: >=1.44.0,<1.45.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-grimport: 
   :depends r-htmlwidgets: 
   :depends r-plotrix: 
   :depends r-scales: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-trackviewer

   and update with::

      conda update bioconductor-trackviewer

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-trackviewer:<tag>

   (see `bioconductor-trackviewer/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-trackviewer| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-trackviewer.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-trackviewer
   :alt:   (downloads)
.. |docker_bioconductor-trackviewer| image:: https://quay.io/repository/biocontainers/bioconductor-trackviewer/status
   :target: https://quay.io/repository/biocontainers/bioconductor-trackviewer
.. _`bioconductor-trackviewer/tags`: https://quay.io/repository/biocontainers/bioconductor-trackviewer?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-trackviewer/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-trackviewer/README.html