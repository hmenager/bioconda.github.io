:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-rnbeads'
.. highlight: bash

bioconductor-rnbeads
====================

.. conda:recipe:: bioconductor-rnbeads
   :replaces_section_title:

   RnBeads facilitates comprehensive analysis of various types of DNA methylation data at the genome scale.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/RnBeads.html
   :license: GPL-3
   :recipe: /`bioconductor-rnbeads <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-rnbeads>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-rnbeads/meta.yaml>`_

   


.. conda:package:: bioconductor-rnbeads

   |downloads_bioconductor-rnbeads| |docker_bioconductor-rnbeads|

   :versions: 2.2.0-1, 2.0.0-0, 1.12.1-0, 1.10.8-0
   
   :depends bioconductor-biocgenerics: >=0.30.0,<0.31.0
   :depends bioconductor-genomicranges: >=1.36.0,<1.37.0
   :depends bioconductor-illuminaio: >=0.26.0,<0.27.0
   :depends bioconductor-iranges: >=2.18.0,<2.19.0
   :depends bioconductor-limma: >=3.40.0,<3.41.0
   :depends bioconductor-methylumi: >=2.30.0,<2.31.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-cluster: 
   :depends r-ff: 
   :depends r-fields: 
   :depends r-ggplot2: >=0.9.2
   :depends r-gplots: 
   :depends r-gridextra: 
   :depends r-mass: 
   :depends r-matrixstats: 
   :depends r-plyr: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-rnbeads

   and update with::

      conda update bioconductor-rnbeads

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-rnbeads:<tag>

   (see `bioconductor-rnbeads/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-rnbeads| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-rnbeads.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-rnbeads
   :alt:   (downloads)
.. |docker_bioconductor-rnbeads| image:: https://quay.io/repository/biocontainers/bioconductor-rnbeads/status
   :target: https://quay.io/repository/biocontainers/bioconductor-rnbeads
.. _`bioconductor-rnbeads/tags`: https://quay.io/repository/biocontainers/bioconductor-rnbeads?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-rnbeads/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-rnbeads/README.html