:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-usort'
.. highlight: bash

bioconductor-usort
==================

.. conda:recipe:: bioconductor-usort
   :replaces_section_title:

   This package is designed to uncover the intrinsic cell progression path from single\-cell RNA\-seq data. It incorporates data pre\-processing\, preliminary PCA gene selection\, preliminary cell ordering\, feature selection\, refined cell ordering\, and post\-analysis interpretation and visualization.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/uSORT.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-usort <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-usort>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-usort/meta.yaml>`_

   


.. conda:package:: bioconductor-usort

   |downloads_bioconductor-usort| |docker_bioconductor-usort|

   :versions: 1.10.0-1, 1.8.0-0
   
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends bioconductor-biocgenerics: >=0.30.0,<0.31.0
   :depends bioconductor-monocle: >=2.12.0,<2.13.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-cluster: 
   :depends r-fpc: 
   :depends r-gplots: 
   :depends r-igraph: 
   :depends r-matrix: 
   :depends r-plyr: 
   :depends r-rann: 
   :depends r-rspectra: 
   :depends r-vgam: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-usort

   and update with::

      conda update bioconductor-usort

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-usort:<tag>

   (see `bioconductor-usort/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-usort| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-usort.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-usort
   :alt:   (downloads)
.. |docker_bioconductor-usort| image:: https://quay.io/repository/biocontainers/bioconductor-usort/status
   :target: https://quay.io/repository/biocontainers/bioconductor-usort
.. _`bioconductor-usort/tags`: https://quay.io/repository/biocontainers/bioconductor-usort?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-usort/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-usort/README.html