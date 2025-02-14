:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-cgdv17'
.. highlight: bash

bioconductor-cgdv17
===================

.. conda:recipe:: bioconductor-cgdv17
   :replaces_section_title:

   Complete Genomics Diversity Panel\, chr17 on 46 individuals

   :homepage: https://bioconductor.org/packages/3.9/data/experiment/html/cgdv17.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-cgdv17 <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-cgdv17>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-cgdv17/meta.yaml>`_

   


.. conda:package:: bioconductor-cgdv17

   |downloads_bioconductor-cgdv17| |docker_bioconductor-cgdv17|

   :versions: 0.22.0-1, 0.20.0-0
   
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends bioconductor-biocgenerics: >=0.30.0,<0.31.0
   :depends bioconductor-genomicranges: >=1.36.0,<1.37.0
   :depends bioconductor-iranges: >=2.18.0,<2.19.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends bioconductor-variantannotation: >=1.30.0,<1.31.0
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-cgdv17

   and update with::

      conda update bioconductor-cgdv17

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-cgdv17:<tag>

   (see `bioconductor-cgdv17/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-cgdv17| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-cgdv17.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-cgdv17
   :alt:   (downloads)
.. |docker_bioconductor-cgdv17| image:: https://quay.io/repository/biocontainers/bioconductor-cgdv17/status
   :target: https://quay.io/repository/biocontainers/bioconductor-cgdv17
.. _`bioconductor-cgdv17/tags`: https://quay.io/repository/biocontainers/bioconductor-cgdv17?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-cgdv17/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-cgdv17/README.html