:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-cpvsnp'
.. highlight: bash

bioconductor-cpvsnp
===================

.. conda:recipe:: bioconductor-cpvsnp
   :replaces_section_title:

   Gene set analysis methods exist to combine SNP\-level association p\-values into gene sets\, calculating a single association p\-value for each gene set. This package implements two such methods that require only the calculated SNP p\-values\, the gene set\(s\) of interest\, and a correlation matrix \(if desired\). One method \(GLOSSI\) requires independent SNPs and the other \(VEGAS\) can take into account correlation \(LD\) among the SNPs. Built\-in plotting functions are available to help users visualize results.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/cpvSNP.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-cpvsnp <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-cpvsnp>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-cpvsnp/meta.yaml>`_
   :links: biotools: :biotools:`cpvsnp`, doi: :doi:`10.1038/nmeth.3252`

   


.. conda:package:: bioconductor-cpvsnp

   |downloads_bioconductor-cpvsnp| |docker_bioconductor-cpvsnp|

   :versions: 1.16.0-1, 1.14.0-0, 1.12.0-0, 1.10.0-0
   
   :depends bioconductor-biocparallel: >=1.18.0,<1.19.0
   :depends bioconductor-genomicfeatures: >=1.36.0,<1.37.0
   :depends bioconductor-gseabase: >=1.46.0,<1.47.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-corpcor: 
   :depends r-ggplot2: 
   :depends r-plyr: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-cpvsnp

   and update with::

      conda update bioconductor-cpvsnp

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-cpvsnp:<tag>

   (see `bioconductor-cpvsnp/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-cpvsnp| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-cpvsnp.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-cpvsnp
   :alt:   (downloads)
.. |docker_bioconductor-cpvsnp| image:: https://quay.io/repository/biocontainers/bioconductor-cpvsnp/status
   :target: https://quay.io/repository/biocontainers/bioconductor-cpvsnp
.. _`bioconductor-cpvsnp/tags`: https://quay.io/repository/biocontainers/bioconductor-cpvsnp?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-cpvsnp/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-cpvsnp/README.html