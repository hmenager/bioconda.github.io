:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-bags'
.. highlight: bash

bioconductor-bags
=================

.. conda:recipe:: bioconductor-bags
   :replaces_section_title:

   R package providing functions to perform geneset significance analysis over simple cross\-sectional data between 2 and 5 phenotypes of interest.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/BAGS.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-bags <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-bags>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-bags/meta.yaml>`_

   


.. conda:package:: bioconductor-bags

   |downloads_bioconductor-bags| |docker_bioconductor-bags|

   :versions: 2.24.0-1, 2.22.0-0
   
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends bioconductor-breastcancervdx: >=1.22.0,<1.23.0
   :depends libgcc-ng: >=7.3.0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-bags

   and update with::

      conda update bioconductor-bags

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-bags:<tag>

   (see `bioconductor-bags/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-bags| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-bags.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-bags
   :alt:   (downloads)
.. |docker_bioconductor-bags| image:: https://quay.io/repository/biocontainers/bioconductor-bags/status
   :target: https://quay.io/repository/biocontainers/bioconductor-bags
.. _`bioconductor-bags/tags`: https://quay.io/repository/biocontainers/bioconductor-bags?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-bags/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-bags/README.html