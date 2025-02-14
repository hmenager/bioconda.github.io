:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-genomeinfodb'
.. highlight: bash

bioconductor-genomeinfodb
=========================

.. conda:recipe:: bioconductor-genomeinfodb
   :replaces_section_title:

   Contains data and functions that define and allow translation between different chromosome sequence naming conventions \(e.g.\, \"chr1\" versus \"1\"\)\, including a function that attempts to place sequence names in their natural\, rather than lexicographic\, order.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/GenomeInfoDb.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-genomeinfodb <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-genomeinfodb>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-genomeinfodb/meta.yaml>`_
   :links: biotools: :biotools:`genomeinfodb`, doi: :doi:`10.1038/nmeth.3252`

   


.. conda:package:: bioconductor-genomeinfodb

   |downloads_bioconductor-genomeinfodb| |docker_bioconductor-genomeinfodb|

   :versions: 1.20.0-1, 1.18.1-0, 1.16.0-0, 1.14.0-0, 1.12.3-0, 1.10.3-0, 1.8.7-0, 1.6.3-0, 1.6.1-0, 1.6.0-0, 1.4.3-0
   
   :depends bioconductor-biocgenerics: >=0.30.0,<0.31.0
   :depends bioconductor-genomeinfodbdata: >=1.2.0,<1.3.0
   :depends bioconductor-iranges: >=2.18.0,<2.19.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-rcurl: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-genomeinfodb

   and update with::

      conda update bioconductor-genomeinfodb

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-genomeinfodb:<tag>

   (see `bioconductor-genomeinfodb/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-genomeinfodb| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-genomeinfodb.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-genomeinfodb
   :alt:   (downloads)
.. |docker_bioconductor-genomeinfodb| image:: https://quay.io/repository/biocontainers/bioconductor-genomeinfodb/status
   :target: https://quay.io/repository/biocontainers/bioconductor-genomeinfodb
.. _`bioconductor-genomeinfodb/tags`: https://quay.io/repository/biocontainers/bioconductor-genomeinfodb?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-genomeinfodb/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-genomeinfodb/README.html