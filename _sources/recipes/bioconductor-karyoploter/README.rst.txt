:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-karyoploter'
.. highlight: bash

bioconductor-karyoploter
========================

.. conda:recipe:: bioconductor-karyoploter
   :replaces_section_title:

   karyoploteR creates karyotype plots of arbitrary genomes and offers a complete set of functions to plot arbitrary data on them. It mimicks many R base graphics functions coupling them with a coordinate change function automatically mapping the chromosome and data coordinates into the plot coordinates. In addition to the provided data plotting functions\, it is easy to add new ones.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/karyoploteR.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-karyoploter <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-karyoploter>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-karyoploter/meta.yaml>`_

   


.. conda:package:: bioconductor-karyoploter

   |downloads_bioconductor-karyoploter| |docker_bioconductor-karyoploter|

   :versions: 1.10.4-0, 1.8.5-0
   
   :depends bioconductor-annotationdbi: >=1.46.0,<1.47.0
   :depends bioconductor-bamsignals: >=1.16.0,<1.17.0
   :depends bioconductor-biovizbase: >=1.32.0,<1.33.0
   :depends bioconductor-genomeinfodb: >=1.20.0,<1.21.0
   :depends bioconductor-genomicfeatures: >=1.36.0,<1.37.0
   :depends bioconductor-genomicranges: >=1.36.0,<1.37.0
   :depends bioconductor-iranges: >=2.18.0,<2.19.0
   :depends bioconductor-regioner: >=1.16.0,<1.17.0
   :depends bioconductor-rsamtools: >=2.0.0,<2.1.0
   :depends bioconductor-rtracklayer: >=1.44.0,<1.45.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-bezier: 
   :depends r-digest: 
   :depends r-memoise: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-karyoploter

   and update with::

      conda update bioconductor-karyoploter

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-karyoploter:<tag>

   (see `bioconductor-karyoploter/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-karyoploter| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-karyoploter.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-karyoploter
   :alt:   (downloads)
.. |docker_bioconductor-karyoploter| image:: https://quay.io/repository/biocontainers/bioconductor-karyoploter/status
   :target: https://quay.io/repository/biocontainers/bioconductor-karyoploter
.. _`bioconductor-karyoploter/tags`: https://quay.io/repository/biocontainers/bioconductor-karyoploter?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-karyoploter/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-karyoploter/README.html