:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-edaseq'
.. highlight: bash

bioconductor-edaseq
===================

.. conda:recipe:: bioconductor-edaseq
   :replaces_section_title:

   Numerical and graphical summaries of RNA\-Seq read data. Within\-lane normalization procedures to adjust for GC\-content effect \(or other gene\-level effects\) on read counts\: loess robust local regression\, global\-scaling\, and full\-quantile normalization \(Risso et al.\, 2011\). Between\-lane normalization procedures to adjust for distributional differences between lanes \(e.g.\, sequencing depth\)\: global\-scaling and full\-quantile normalization \(Bullard et al.\, 2010\).

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/EDASeq.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-edaseq <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-edaseq>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-edaseq/meta.yaml>`_
   :links: biotools: :biotools:`edaseq`

   


.. conda:package:: bioconductor-edaseq

   |downloads_bioconductor-edaseq| |docker_bioconductor-edaseq|

   :versions: 2.18.0-1, 2.16.0-0, 2.14.1-0, 2.12.0-0, 2.10.0-0, 2.8.0-0
   
   :depends bioconductor-annotationdbi: >=1.46.0,<1.47.0
   :depends bioconductor-aroma.light: >=3.14.0,<3.15.0
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends bioconductor-biocgenerics: >=0.30.0,<0.31.0
   :depends bioconductor-biomart: >=2.40.0,<2.41.0
   :depends bioconductor-biostrings: >=2.52.0,<2.53.0
   :depends bioconductor-deseq: >=1.36.0,<1.37.0
   :depends bioconductor-genomicfeatures: >=1.36.0,<1.37.0
   :depends bioconductor-genomicranges: >=1.36.0,<1.37.0
   :depends bioconductor-iranges: >=2.18.0,<2.19.0
   :depends bioconductor-rsamtools: >=2.0.0,<2.1.0
   :depends bioconductor-shortread: >=1.42.0,<1.43.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-biocmanager: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-edaseq

   and update with::

      conda update bioconductor-edaseq

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-edaseq:<tag>

   (see `bioconductor-edaseq/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-edaseq| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-edaseq.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-edaseq
   :alt:   (downloads)
.. |docker_bioconductor-edaseq| image:: https://quay.io/repository/biocontainers/bioconductor-edaseq/status
   :target: https://quay.io/repository/biocontainers/bioconductor-edaseq
.. _`bioconductor-edaseq/tags`: https://quay.io/repository/biocontainers/bioconductor-edaseq?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-edaseq/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-edaseq/README.html