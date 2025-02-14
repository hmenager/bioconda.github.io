:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-skewr'
.. highlight: bash

bioconductor-skewr
==================

.. conda:recipe:: bioconductor-skewr
   :replaces_section_title:

   The skewr package is a tool for visualizing the output of the Illumina Human Methylation 450k BeadChip to aid in quality control. It creates a panel of nine plots. Six of the plots represent the density of either the methylated intensity or the unmethylated intensity given by one of three subsets of the 485\,577 total probes. These subsets include Type I\-red\, Type I\-green\, and Type II.The remaining three distributions give the density of the Beta\-values for these same three subsets. Each of the nine plots optionally displays the distributions of the \"rs\" SNP probes and the probes associated with imprinted genes as series of \'tick\' marks located above the x\-axis.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/skewr.html
   :license: GPL-2
   :recipe: /`bioconductor-skewr <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-skewr>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-skewr/meta.yaml>`_

   


.. conda:package:: bioconductor-skewr

   |downloads_bioconductor-skewr| |docker_bioconductor-skewr|

   :versions: 1.16.0-1, 1.14.0-0
   
   :depends bioconductor-illuminahumanmethylation450kmanifest: >=0.4.0,<0.5.0
   :depends bioconductor-methylumi: >=2.30.0,<2.31.0
   :depends bioconductor-minfi: >=1.30.0,<1.31.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends bioconductor-watermelon: >=1.28.0,<1.29.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-mixsmsn: 
   :depends r-rcolorbrewer: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-skewr

   and update with::

      conda update bioconductor-skewr

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-skewr:<tag>

   (see `bioconductor-skewr/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-skewr| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-skewr.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-skewr
   :alt:   (downloads)
.. |docker_bioconductor-skewr| image:: https://quay.io/repository/biocontainers/bioconductor-skewr/status
   :target: https://quay.io/repository/biocontainers/bioconductor-skewr
.. _`bioconductor-skewr/tags`: https://quay.io/repository/biocontainers/bioconductor-skewr?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-skewr/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-skewr/README.html