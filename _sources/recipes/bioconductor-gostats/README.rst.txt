:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-gostats'
.. highlight: bash

bioconductor-gostats
====================

.. conda:recipe:: bioconductor-gostats
   :replaces_section_title:

   A set of tools for interacting with GO and microarray data. A variety of basic manipulation tools for graphs\, hypothesis testing and other simple calculations.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/GOstats.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-gostats <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-gostats>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-gostats/meta.yaml>`_
   :links: biotools: :biotools:`gostats`

   


.. conda:package:: bioconductor-gostats

   |downloads_bioconductor-gostats| |docker_bioconductor-gostats|

   :versions: 2.50.0-1, 2.48.0-0, 2.46.0-0, 2.44.0-0, 2.42.0-0, 2.38.1-1, 2.38.1-0, 2.36.0-0
   
   :depends bioconductor-annotate: >=1.62.0,<1.63.0
   :depends bioconductor-annotationdbi: >=1.46.0,<1.47.0
   :depends bioconductor-annotationforge: >=1.26.0,<1.27.0
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends bioconductor-category: >=2.50.0,<2.51.0
   :depends bioconductor-go.db: >=3.8.0,<3.9.0
   :depends bioconductor-graph: >=1.62.0,<1.63.0
   :depends bioconductor-rbgl: >=1.60.0,<1.61.0
   :depends bioconductor-rgraphviz: >=2.28.0,<2.29.0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-gostats

   and update with::

      conda update bioconductor-gostats

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-gostats:<tag>

   (see `bioconductor-gostats/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-gostats| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-gostats.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-gostats
   :alt:   (downloads)
.. |docker_bioconductor-gostats| image:: https://quay.io/repository/biocontainers/bioconductor-gostats/status
   :target: https://quay.io/repository/biocontainers/bioconductor-gostats
.. _`bioconductor-gostats/tags`: https://quay.io/repository/biocontainers/bioconductor-gostats?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-gostats/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-gostats/README.html