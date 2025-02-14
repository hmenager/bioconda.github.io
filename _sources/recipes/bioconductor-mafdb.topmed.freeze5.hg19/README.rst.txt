:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-mafdb.topmed.freeze5.hg19'
.. highlight: bash

bioconductor-mafdb.topmed.freeze5.hg19
======================================

.. conda:recipe:: bioconductor-mafdb.topmed.freeze5.hg19
   :replaces_section_title:

   Store minor allele frequency data from NHLBI TOPMed for the human genome version hg19.

   :homepage: https://bioconductor.org/packages/3.9/data/annotation/html/MafDb.TOPMed.freeze5.hg19.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-mafdb.topmed.freeze5.hg19 <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-mafdb.topmed.freeze5.hg19>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-mafdb.topmed.freeze5.hg19/meta.yaml>`_

   


.. conda:package:: bioconductor-mafdb.topmed.freeze5.hg19

   |downloads_bioconductor-mafdb.topmed.freeze5.hg19| |docker_bioconductor-mafdb.topmed.freeze5.hg19|

   :versions: 3.9.0-1, 3.7.1-0
   
   :depends bioconductor-bsgenome: >=1.52.0,<1.53.0
   :depends bioconductor-genomeinfodb: >=1.20.0,<1.21.0
   :depends bioconductor-genomicranges: >=1.36.0,<1.37.0
   :depends bioconductor-genomicscores: >=1.8.0,<1.9.0
   :depends bioconductor-iranges: >=2.18.0,<2.19.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-mafdb.topmed.freeze5.hg19

   and update with::

      conda update bioconductor-mafdb.topmed.freeze5.hg19

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-mafdb.topmed.freeze5.hg19:<tag>

   (see `bioconductor-mafdb.topmed.freeze5.hg19/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-mafdb.topmed.freeze5.hg19| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-mafdb.topmed.freeze5.hg19.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-mafdb.topmed.freeze5.hg19
   :alt:   (downloads)
.. |docker_bioconductor-mafdb.topmed.freeze5.hg19| image:: https://quay.io/repository/biocontainers/bioconductor-mafdb.topmed.freeze5.hg19/status
   :target: https://quay.io/repository/biocontainers/bioconductor-mafdb.topmed.freeze5.hg19
.. _`bioconductor-mafdb.topmed.freeze5.hg19/tags`: https://quay.io/repository/biocontainers/bioconductor-mafdb.topmed.freeze5.hg19?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-mafdb.topmed.freeze5.hg19/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-mafdb.topmed.freeze5.hg19/README.html