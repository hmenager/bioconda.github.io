:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-clst'
.. highlight: bash

bioconductor-clst
=================

.. conda:recipe:: bioconductor-clst
   :replaces_section_title:

   Package for modified nearest\-neighbor classification based on calculation of a similarity threshold distinguishing within\-group from between\-group comparisons.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/clst.html
   :license: GPL-3
   :recipe: /`bioconductor-clst <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-clst>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-clst/meta.yaml>`_
   :links: biotools: :biotools:`clst`, doi: :doi:`10.1038/nmeth.3252`

   


.. conda:package:: bioconductor-clst

   |downloads_bioconductor-clst| |docker_bioconductor-clst|

   :versions: 1.32.0-1, 1.32.0-0, 1.30.0-0, 1.28.0-0, 1.26.0-0
   
   :depends bioconductor-roc: >=1.60.0,<1.61.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-lattice: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-clst

   and update with::

      conda update bioconductor-clst

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-clst:<tag>

   (see `bioconductor-clst/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-clst| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-clst.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-clst
   :alt:   (downloads)
.. |docker_bioconductor-clst| image:: https://quay.io/repository/biocontainers/bioconductor-clst/status
   :target: https://quay.io/repository/biocontainers/bioconductor-clst
.. _`bioconductor-clst/tags`: https://quay.io/repository/biocontainers/bioconductor-clst?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-clst/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-clst/README.html