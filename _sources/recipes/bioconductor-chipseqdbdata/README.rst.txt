:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-chipseqdbdata'
.. highlight: bash

bioconductor-chipseqdbdata
==========================

.. conda:recipe:: bioconductor-chipseqdbdata
   :replaces_section_title:

   Sorted and indexed BAM files for ChIP\-seq libraries\, for use in the chipseqDB workflow. BAM indices are also included.

   :homepage: https://bioconductor.org/packages/3.9/data/experiment/html/chipseqDBData.html
   :license: CC BY 4.0
   :recipe: /`bioconductor-chipseqdbdata <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-chipseqdbdata>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-chipseqdbdata/meta.yaml>`_

   


.. conda:package:: bioconductor-chipseqdbdata

   |downloads_bioconductor-chipseqdbdata| |docker_bioconductor-chipseqdbdata|

   :versions: 1.0.0-1
   
   :depends bioconductor-annotationhub: >=2.16.0,<2.17.0
   :depends bioconductor-experimenthub: >=1.10.0,<1.11.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-chipseqdbdata

   and update with::

      conda update bioconductor-chipseqdbdata

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-chipseqdbdata:<tag>

   (see `bioconductor-chipseqdbdata/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-chipseqdbdata| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-chipseqdbdata.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-chipseqdbdata
   :alt:   (downloads)
.. |docker_bioconductor-chipseqdbdata| image:: https://quay.io/repository/biocontainers/bioconductor-chipseqdbdata/status
   :target: https://quay.io/repository/biocontainers/bioconductor-chipseqdbdata
.. _`bioconductor-chipseqdbdata/tags`: https://quay.io/repository/biocontainers/bioconductor-chipseqdbdata?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-chipseqdbdata/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-chipseqdbdata/README.html