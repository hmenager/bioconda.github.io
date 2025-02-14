:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-crisprseekplus'
.. highlight: bash

bioconductor-crisprseekplus
===========================

.. conda:recipe:: bioconductor-crisprseekplus
   :replaces_section_title:

   Bioinformatics platform containing interface to work with offTargetAnalysis and compare2Sequences in the CRISPRseek package\, and GUIDEseqAnalysis.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/crisprseekplus.html
   :license: GPL-3 + file LICENSE
   :recipe: /`bioconductor-crisprseekplus <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-crisprseekplus>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-crisprseekplus/meta.yaml>`_
   :links: biotools: :biotools:`crisprseekplus`, doi: :doi:`10.1371/journal.pone.0108424`

   


.. conda:package:: bioconductor-crisprseekplus

   |downloads_bioconductor-crisprseekplus| |docker_bioconductor-crisprseekplus|

   :versions: 1.10.0-1, 1.8.0-0, 1.6.0-0, 1.4.1-0
   
   :depends bioconductor-annotationdbi: >=1.46.0,<1.47.0
   :depends bioconductor-bsgenome: >=1.52.0,<1.53.0
   :depends bioconductor-crisprseek: >=1.24.0,<1.25.0
   :depends bioconductor-genomicfeatures: >=1.36.0,<1.37.0
   :depends bioconductor-genomicranges: >=1.36.0,<1.37.0
   :depends bioconductor-guideseq: >=1.14.0,<1.15.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-biocmanager: 
   :depends r-dt: 
   :depends r-hash: 
   :depends r-shiny: 
   :depends r-shinyjs: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-crisprseekplus

   and update with::

      conda update bioconductor-crisprseekplus

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-crisprseekplus:<tag>

   (see `bioconductor-crisprseekplus/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-crisprseekplus| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-crisprseekplus.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-crisprseekplus
   :alt:   (downloads)
.. |docker_bioconductor-crisprseekplus| image:: https://quay.io/repository/biocontainers/bioconductor-crisprseekplus/status
   :target: https://quay.io/repository/biocontainers/bioconductor-crisprseekplus
.. _`bioconductor-crisprseekplus/tags`: https://quay.io/repository/biocontainers/bioconductor-crisprseekplus?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-crisprseekplus/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-crisprseekplus/README.html