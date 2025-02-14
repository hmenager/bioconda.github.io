:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-chipseqr'
.. highlight: bash

bioconductor-chipseqr
=====================

.. conda:recipe:: bioconductor-chipseqr
   :replaces_section_title:

   ChIPseqR identifies protein binding sites from ChIP\-seq and nucleosome positioning experiments. The model used to describe binding events was developed to locate nucleosomes but should flexible enough to handle other types of experiments as well.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/ChIPseqR.html
   :license: GPL (>= 2)
   :recipe: /`bioconductor-chipseqr <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-chipseqr>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-chipseqr/meta.yaml>`_

   


.. conda:package:: bioconductor-chipseqr

   |downloads_bioconductor-chipseqr| |docker_bioconductor-chipseqr|

   :versions: 1.38.0-1, 1.36.0-1, 1.36.0-0
   
   :depends bioconductor-biocgenerics: >=0.30.0,<0.31.0
   :depends bioconductor-biostrings: >=2.52.0,<2.53.0
   :depends bioconductor-genomicranges: >=1.36.0,<1.37.0
   :depends bioconductor-hilbertvis: >=1.42.0,<1.43.0
   :depends bioconductor-iranges: >=2.18.0,<2.19.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends bioconductor-shortread: >=1.42.0,<1.43.0
   :depends libgcc-ng: >=7.3.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-fbasics: 
   :depends r-timsac: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-chipseqr

   and update with::

      conda update bioconductor-chipseqr

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-chipseqr:<tag>

   (see `bioconductor-chipseqr/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-chipseqr| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-chipseqr.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-chipseqr
   :alt:   (downloads)
.. |docker_bioconductor-chipseqr| image:: https://quay.io/repository/biocontainers/bioconductor-chipseqr/status
   :target: https://quay.io/repository/biocontainers/bioconductor-chipseqr
.. _`bioconductor-chipseqr/tags`: https://quay.io/repository/biocontainers/bioconductor-chipseqr?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-chipseqr/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-chipseqr/README.html