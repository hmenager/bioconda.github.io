:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-mirintegrator'
.. highlight: bash

bioconductor-mirintegrator
==========================

.. conda:recipe:: bioconductor-mirintegrator
   :replaces_section_title:

   Tools for augmenting signaling pathways to perform pathway analysis of microRNA and mRNA expression levels.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/mirIntegrator.html
   :license: GPL (>=3)
   :recipe: /`bioconductor-mirintegrator <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-mirintegrator>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-mirintegrator/meta.yaml>`_
   :links: biotools: :biotools:`mirintegrator`, doi: :doi:`10.1038/srep29251`

   


.. conda:package:: bioconductor-mirintegrator

   |downloads_bioconductor-mirintegrator| |docker_bioconductor-mirintegrator|

   :versions: 1.14.0-1, 1.12.0-0, 1.10.0-0, 1.8.0-0
   
   :depends bioconductor-annotationdbi: >=1.46.0,<1.47.0
   :depends bioconductor-graph: >=1.62.0,<1.63.0
   :depends bioconductor-org.hs.eg.db: >=3.8.0,<3.9.0
   :depends bioconductor-rgraphviz: >=2.28.0,<2.29.0
   :depends bioconductor-rontotools: >=2.12.0,<2.13.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-ggplot2: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-mirintegrator

   and update with::

      conda update bioconductor-mirintegrator

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-mirintegrator:<tag>

   (see `bioconductor-mirintegrator/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-mirintegrator| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-mirintegrator.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-mirintegrator
   :alt:   (downloads)
.. |docker_bioconductor-mirintegrator| image:: https://quay.io/repository/biocontainers/bioconductor-mirintegrator/status
   :target: https://quay.io/repository/biocontainers/bioconductor-mirintegrator
.. _`bioconductor-mirintegrator/tags`: https://quay.io/repository/biocontainers/bioconductor-mirintegrator?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-mirintegrator/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-mirintegrator/README.html