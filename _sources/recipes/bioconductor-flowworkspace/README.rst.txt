:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-flowworkspace'
.. highlight: bash

bioconductor-flowworkspace
==========================

.. conda:recipe:: bioconductor-flowworkspace
   :replaces_section_title:

   This package is designed to facilitate comparison of automated gating methods against manual gating done in flowJo. This package allows you to import basic flowJo workspaces into BioConductor and replicate the gating from flowJo using the flowCore functionality. Gating hierarchies\, groups of samples\, compensation\, and transformation are performed so that the output matches the flowJo analysis.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/flowWorkspace.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-flowworkspace <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-flowworkspace>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-flowworkspace/meta.yaml>`_
   :links: biotools: :biotools:`flowworkspace`, doi: :doi:`10.1186/1471-2105-13-252`

   


.. conda:package:: bioconductor-flowworkspace

   |downloads_bioconductor-flowworkspace| |docker_bioconductor-flowworkspace|

   :versions: 3.32.0-1, 3.30.2-0, 3.30.1-0, 3.28.2-0, 3.26.2-0, 3.24.4-0
   
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends bioconductor-biocgenerics: >=0.30.0,<0.31.0
   :depends bioconductor-cytolib: >=1.6.0,<1.7.0
   :depends bioconductor-flowcore: >=1.50.0,<1.51.0
   :depends bioconductor-flowviz: >=1.48.0,<1.49.0
   :depends bioconductor-graph: >=1.62.0,<1.63.0
   :depends bioconductor-ncdfflow: >=2.30.0,<2.31.0
   :depends bioconductor-rbgl: >=1.60.0,<1.61.0
   :depends bioconductor-rgraphviz: >=2.28.0,<2.29.0
   :depends bioconductor-rprotobuflib: >=1.6.0,<1.7.0
   :depends libgcc-ng: >=7.3.0
   :depends libstdcxx-ng: >=7.3.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-bh: >=1.62.0-1
   :depends r-data.table: 
   :depends r-digest: 
   :depends r-dplyr: 
   :depends r-gridextra: 
   :depends r-lattice: 
   :depends r-latticeextra: 
   :depends r-matrixstats: 
   :depends r-rcolorbrewer: 
   :depends r-rcpp: 
   :depends r-rcppparallel: 
   :depends r-scales: 
   :depends r-stringr: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-flowworkspace

   and update with::

      conda update bioconductor-flowworkspace

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-flowworkspace:<tag>

   (see `bioconductor-flowworkspace/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-flowworkspace| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-flowworkspace.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-flowworkspace
   :alt:   (downloads)
.. |docker_bioconductor-flowworkspace| image:: https://quay.io/repository/biocontainers/bioconductor-flowworkspace/status
   :target: https://quay.io/repository/biocontainers/bioconductor-flowworkspace
.. _`bioconductor-flowworkspace/tags`: https://quay.io/repository/biocontainers/bioconductor-flowworkspace?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-flowworkspace/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-flowworkspace/README.html