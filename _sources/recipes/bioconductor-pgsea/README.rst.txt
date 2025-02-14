:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-pgsea'
.. highlight: bash

bioconductor-pgsea
==================

.. conda:recipe:: bioconductor-pgsea
   :replaces_section_title:

   Parametric Analysis of Gene Set Enrichment

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/PGSEA.html
   :license: GPL-2
   :recipe: /`bioconductor-pgsea <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-pgsea>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-pgsea/meta.yaml>`_
   :links: biotools: :biotools:`pgsea`, doi: :doi:`10.1038/nmeth.3252`

   


.. conda:package:: bioconductor-pgsea

   |downloads_bioconductor-pgsea| |docker_bioconductor-pgsea|

   :versions: 1.58.0-1, 1.56.0-0, 1.54.0-0, 1.52.0-0, 1.51.0-0, 1.50.0-0
   
   :depends bioconductor-annaffy: >=1.56.0,<1.57.0
   :depends bioconductor-annotationdbi: >=1.46.0,<1.47.0
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends bioconductor-go.db: >=3.8.0,<3.9.0
   :depends bioconductor-kegg.db: >=3.2.0,<3.3.0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-pgsea

   and update with::

      conda update bioconductor-pgsea

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-pgsea:<tag>

   (see `bioconductor-pgsea/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-pgsea| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-pgsea.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-pgsea
   :alt:   (downloads)
.. |docker_bioconductor-pgsea| image:: https://quay.io/repository/biocontainers/bioconductor-pgsea/status
   :target: https://quay.io/repository/biocontainers/bioconductor-pgsea
.. _`bioconductor-pgsea/tags`: https://quay.io/repository/biocontainers/bioconductor-pgsea?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-pgsea/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-pgsea/README.html