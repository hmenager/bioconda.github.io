:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-atsnp'
.. highlight: bash

bioconductor-atsnp
==================

.. conda:recipe:: bioconductor-atsnp
   :replaces_section_title:

   atSNP performs affinity tests of motif matches with the SNP or the reference genomes and SNP\-led changes in motif matches.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/atSNP.html
   :license: GPL-2
   :recipe: /`bioconductor-atsnp <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-atsnp>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-atsnp/meta.yaml>`_

   


.. conda:package:: bioconductor-atsnp

   |downloads_bioconductor-atsnp| |docker_bioconductor-atsnp|

   :versions: 1.0.0-1
   
   :depends bioconductor-biocfilecache: >=1.8.0,<1.9.0
   :depends bioconductor-biocparallel: >=1.18.0,<1.19.0
   :depends bioconductor-bsgenome: >=1.52.0,<1.53.0
   :depends bioconductor-motifstack: >=1.28.0,<1.29.0
   :depends libgcc-ng: >=7.3.0
   :depends libstdcxx-ng: >=7.3.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-data.table: 
   :depends r-rappdirs: 
   :depends r-rcpp: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-atsnp

   and update with::

      conda update bioconductor-atsnp

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-atsnp:<tag>

   (see `bioconductor-atsnp/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-atsnp| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-atsnp.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-atsnp
   :alt:   (downloads)
.. |docker_bioconductor-atsnp| image:: https://quay.io/repository/biocontainers/bioconductor-atsnp/status
   :target: https://quay.io/repository/biocontainers/bioconductor-atsnp
.. _`bioconductor-atsnp/tags`: https://quay.io/repository/biocontainers/bioconductor-atsnp?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-atsnp/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-atsnp/README.html