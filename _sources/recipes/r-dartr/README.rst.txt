:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'r-dartr'
.. highlight: bash

r-dartr
=======

.. conda:recipe:: r-dartr
   :replaces_section_title:

   Functions are provided that facilitate the import and analysis of SNP \(single nucleotide polymorphism\) and silicodart \(presence\/absence\) data. The main focus is on data generated by DarT \(Diversity Arrays Technology\). However\, once SNP or related fragment presence\/absence data from any source is imported into a genlight object many of the functions can be used. Functions are available for input and output of SNP and silicodart data\, for reporting on and filtering on various criteria \(e.g. CallRate\, Heterozygosity\, Reproducibility\, maximum allele frequency\). Advanced filtering is based on Linkage Disequilibrium and HWE \(Hardy\-Weinberg equilibrium\). Other functions are available for visualization after PCoA \(Principle Coordinate Analysis\)\, or to facilitate transfer of data between genlight\/genind objects and newhybrids\, related\, phylip\, structure\, faststructure packages.

   :homepage: https://CRAN.R-project.org/package=dartR
   :license: GPL2 / GPL-2
   :recipe: /`r-dartr <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/r-dartr>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/r-dartr/meta.yaml>`_

   


.. conda:package:: r-dartr

   |downloads_r-dartr| |docker_r-dartr|

   :versions: 1.1.11-0, 1.0.5-1, 1.0.5-0, 1.0-0
   
   :depends bioconductor-qvalue: 
   :depends bioconductor-snprelate: 
   :depends r-adegenet: >=2.0.0
   :depends r-ape: 
   :depends r-base: >=3.5.1,<3.5.2.0a0
   :depends r-data.table: 
   :depends r-directlabels: 
   :depends r-dismo: 
   :depends r-doparallel: 
   :depends r-foreach: 
   :depends r-gdistance: 
   :depends r-ggplot2: 
   :depends r-hierfstat: 
   :depends r-igraph: 
   :depends r-leaflet: 
   :depends r-mass: 
   :depends r-mmod: 
   :depends r-pca3d: 
   :depends r-pegas: 
   :depends r-plyr: 
   :depends r-popgenreport: 
   :depends r-reshape2: 
   :depends r-rgdal: 
   :depends r-rrblup: 
   :depends r-seqinr: 
   :depends r-snpassoc: 
   :depends r-sp: 
   :depends r-stampp: 
   :depends r-stringr: 
   :depends r-tidyr: 
   :depends r-vegan: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install r-dartr

   and update with::

      conda update r-dartr

   or use the docker container::

      docker pull quay.io/biocontainers/r-dartr:<tag>

   (see `r-dartr/tags`_ for valid values for ``<tag>``)


.. |downloads_r-dartr| image:: https://img.shields.io/conda/dn/bioconda/r-dartr.svg?style=flat
   :target: https://anaconda.org/bioconda/r-dartr
   :alt:   (downloads)
.. |docker_r-dartr| image:: https://quay.io/repository/biocontainers/r-dartr/status
   :target: https://quay.io/repository/biocontainers/r-dartr
.. _`r-dartr/tags`: https://quay.io/repository/biocontainers/r-dartr?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/r-dartr/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/r-dartr/README.html