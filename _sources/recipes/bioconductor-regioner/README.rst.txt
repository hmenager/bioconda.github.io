:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-regioner'
.. highlight: bash

bioconductor-regioner
=====================

.. conda:recipe:: bioconductor-regioner
   :replaces_section_title:

   regioneR offers a statistical framework based on customizable permutation tests to assess the association between genomic region sets and other genomic features.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/regioneR.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-regioner <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-regioner>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-regioner/meta.yaml>`_
   :links: biotools: :biotools:`regioner`

   


.. conda:package:: bioconductor-regioner

   |downloads_bioconductor-regioner| |docker_bioconductor-regioner|

   :versions: 1.16.2-0, 1.14.0-0, 1.12.0-0, 1.10.0-0, 1.8.1-0, 1.6.2-0, 1.2.0-0
   
   :depends bioconductor-biostrings: >=2.52.0,<2.53.0
   :depends bioconductor-bsgenome: >=1.52.0,<1.53.0
   :depends bioconductor-genomeinfodb: >=1.20.0,<1.21.0
   :depends bioconductor-genomicranges: >=1.36.0,<1.37.0
   :depends bioconductor-iranges: >=2.18.0,<2.19.0
   :depends bioconductor-rtracklayer: >=1.44.0,<1.45.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-memoise: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-regioner

   and update with::

      conda update bioconductor-regioner

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-regioner:<tag>

   (see `bioconductor-regioner/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-regioner| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-regioner.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-regioner
   :alt:   (downloads)
.. |docker_bioconductor-regioner| image:: https://quay.io/repository/biocontainers/bioconductor-regioner/status
   :target: https://quay.io/repository/biocontainers/bioconductor-regioner
.. _`bioconductor-regioner/tags`: https://quay.io/repository/biocontainers/bioconductor-regioner?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-regioner/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-regioner/README.html