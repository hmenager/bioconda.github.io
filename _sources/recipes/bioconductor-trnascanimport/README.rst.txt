:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-trnascanimport'
.. highlight: bash

bioconductor-trnascanimport
===========================

.. conda:recipe:: bioconductor-trnascanimport
   :replaces_section_title:

   The package imports the result of tRNAscan\-SE as a GRanges object.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/tRNAscanImport.html
   :license: GPL-3 + file LICENSE
   :recipe: /`bioconductor-trnascanimport <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-trnascanimport>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-trnascanimport/meta.yaml>`_

   


.. conda:package:: bioconductor-trnascanimport

   |downloads_bioconductor-trnascanimport| |docker_bioconductor-trnascanimport|

   :versions: 1.4.2-0, 1.2.0-0
   
   :depends bioconductor-biocgenerics: >=0.30.0,<0.31.0
   :depends bioconductor-biostrings: >=2.52.0,<2.53.0
   :depends bioconductor-genomeinfodb: >=1.20.0,<1.21.0
   :depends bioconductor-genomicranges: >=1.36.0,<1.37.0
   :depends bioconductor-rtracklayer: >=1.44.0,<1.45.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends bioconductor-structstrings: >=1.0.0,<1.1.0
   :depends bioconductor-trna: >=1.2.0,<1.3.0
   :depends r-assertive: 
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-stringr: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-trnascanimport

   and update with::

      conda update bioconductor-trnascanimport

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-trnascanimport:<tag>

   (see `bioconductor-trnascanimport/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-trnascanimport| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-trnascanimport.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-trnascanimport
   :alt:   (downloads)
.. |docker_bioconductor-trnascanimport| image:: https://quay.io/repository/biocontainers/bioconductor-trnascanimport/status
   :target: https://quay.io/repository/biocontainers/bioconductor-trnascanimport
.. _`bioconductor-trnascanimport/tags`: https://quay.io/repository/biocontainers/bioconductor-trnascanimport?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-trnascanimport/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-trnascanimport/README.html