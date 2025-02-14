:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-clippda'
.. highlight: bash

bioconductor-clippda
====================

.. conda:recipe:: bioconductor-clippda
   :replaces_section_title:

   Methods for the nalysis of data from clinical proteomic profiling studies. The focus is on the studies of human subjects\, which are often observational case\-control by design and have technical replicates. A method for sample size determination for planning these studies is proposed. It incorporates routines for adjusting for the expected heterogeneities and imbalances in the data and the within\-sample replicate correlations.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/clippda.html
   :license: GPL (>=2)
   :recipe: /`bioconductor-clippda <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-clippda>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-clippda/meta.yaml>`_

   


.. conda:package:: bioconductor-clippda

   |downloads_bioconductor-clippda| |docker_bioconductor-clippda|

   :versions: 1.34.0-1, 1.32.0-0
   
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends bioconductor-limma: >=3.40.0,<3.41.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-lattice: 
   :depends r-rgl: 
   :depends r-scatterplot3d: 
   :depends r-statmod: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-clippda

   and update with::

      conda update bioconductor-clippda

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-clippda:<tag>

   (see `bioconductor-clippda/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-clippda| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-clippda.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-clippda
   :alt:   (downloads)
.. |docker_bioconductor-clippda| image:: https://quay.io/repository/biocontainers/bioconductor-clippda/status
   :target: https://quay.io/repository/biocontainers/bioconductor-clippda
.. _`bioconductor-clippda/tags`: https://quay.io/repository/biocontainers/bioconductor-clippda?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-clippda/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-clippda/README.html