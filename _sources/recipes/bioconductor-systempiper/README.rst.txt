:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-systempiper'
.. highlight: bash

bioconductor-systempiper
========================

.. conda:recipe:: bioconductor-systempiper
   :replaces_section_title:

   R package for building and running automated end\-to\-end analysis workflows for a wide range of next generation sequence \(NGS\) applications such as RNA\-Seq\, ChIP\-Seq\, VAR\-Seq and Ribo\-Seq. Important features include a uniform workflow interface across different NGS applications\, automated report generation\, and support for running both R and command\-line software\, such as NGS aligners or peak\/variant callers\, on local computers or compute clusters. Efficient handling of complex sample sets and experimental designs is facilitated by a consistently implemented sample annotation infrastructure. Instructions for using systemPipeR are given in the Overview Vignette \(HTML\). The remaining Vignettes\, linked below\, are workflow templates for common NGS use cases.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/systemPipeR.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-systempiper <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-systempiper>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-systempiper/meta.yaml>`_
   :links: biotools: :biotools:`systempiper`

   


.. conda:package:: bioconductor-systempiper

   |downloads_bioconductor-systempiper| |docker_bioconductor-systempiper|

   :versions: 1.18.2-0, 1.16.0-0, 1.14.0-0, 1.12.0-0, 1.10.2-0, 1.9.0-0, 1.4.8-0, 1.4.7-0
   
   :depends bioconductor-annotate: >=1.62.0,<1.63.0
   :depends bioconductor-biocgenerics: >=0.30.0,<0.31.0
   :depends bioconductor-biostrings: >=2.52.0,<2.53.0
   :depends bioconductor-deseq2: >=1.24.0,<1.25.0
   :depends bioconductor-edger: >=3.26.0,<3.27.0
   :depends bioconductor-genomicfeatures: >=1.36.0,<1.37.0
   :depends bioconductor-genomicranges: >=1.36.0,<1.37.0
   :depends bioconductor-go.db: >=3.8.0,<3.9.0
   :depends bioconductor-gostats: >=2.50.0,<2.51.0
   :depends bioconductor-limma: >=3.40.0,<3.41.0
   :depends bioconductor-rsamtools: >=2.0.0,<2.1.0
   :depends bioconductor-shortread: >=1.42.0,<1.43.0
   :depends bioconductor-summarizedexperiment: >=1.14.0,<1.15.0
   :depends bioconductor-variantannotation: >=1.30.0,<1.31.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-batchtools: 
   :depends r-ggplot2: 
   :depends r-pheatmap: 
   :depends r-rjson: 
   :depends r-yaml: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-systempiper

   and update with::

      conda update bioconductor-systempiper

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-systempiper:<tag>

   (see `bioconductor-systempiper/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-systempiper| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-systempiper.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-systempiper
   :alt:   (downloads)
.. |docker_bioconductor-systempiper| image:: https://quay.io/repository/biocontainers/bioconductor-systempiper/status
   :target: https://quay.io/repository/biocontainers/bioconductor-systempiper
.. _`bioconductor-systempiper/tags`: https://quay.io/repository/biocontainers/bioconductor-systempiper?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-systempiper/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-systempiper/README.html