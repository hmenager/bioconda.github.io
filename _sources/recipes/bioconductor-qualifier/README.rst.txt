:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-qualifier'
.. highlight: bash

bioconductor-qualifier
======================

.. conda:recipe:: bioconductor-qualifier
   :replaces_section_title:

   Provides quality control and quality assessment tools for gated flow cytometry data.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/QUALIFIER.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-qualifier <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-qualifier>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-qualifier/meta.yaml>`_
   :links: biotools: :biotools:`qualifier`, doi: :doi:`10.1186/1471-2105-13-252`

   


.. conda:package:: bioconductor-qualifier

   |downloads_bioconductor-qualifier| |docker_bioconductor-qualifier|

   :versions: 1.28.0-1, 1.26.0-0, 1.24.1-0, 1.22.0-0, 1.20.0-0
   
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends bioconductor-flowcore: >=1.50.0,<1.51.0
   :depends bioconductor-flowviz: >=1.48.0,<1.49.0
   :depends bioconductor-flowworkspace: >=3.32.0,<3.33.0
   :depends bioconductor-ncdfflow: >=2.30.0,<2.31.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-data.table: 
   :depends r-hwriter: 
   :depends r-lattice: 
   :depends r-latticeextra: 
   :depends r-mass: 
   :depends r-reshape: 
   :depends r-xml: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-qualifier

   and update with::

      conda update bioconductor-qualifier

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-qualifier:<tag>

   (see `bioconductor-qualifier/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-qualifier| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-qualifier.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-qualifier
   :alt:   (downloads)
.. |docker_bioconductor-qualifier| image:: https://quay.io/repository/biocontainers/bioconductor-qualifier/status
   :target: https://quay.io/repository/biocontainers/bioconductor-qualifier
.. _`bioconductor-qualifier/tags`: https://quay.io/repository/biocontainers/bioconductor-qualifier?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-qualifier/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-qualifier/README.html