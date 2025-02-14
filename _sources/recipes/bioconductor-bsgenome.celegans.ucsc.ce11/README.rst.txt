:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-bsgenome.celegans.ucsc.ce11'
.. highlight: bash

bioconductor-bsgenome.celegans.ucsc.ce11
========================================

.. conda:recipe:: bioconductor-bsgenome.celegans.ucsc.ce11
   :replaces_section_title:

   Full genome sequences for Caenorhabditis elegans \(Worm\) as provided by UCSC \(ce11\, Feb. 2013\) and stored in Biostrings objects.

   :homepage: https://bioconductor.org/packages/3.9/data/annotation/html/BSgenome.Celegans.UCSC.ce11.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-bsgenome.celegans.ucsc.ce11 <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-bsgenome.celegans.ucsc.ce11>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-bsgenome.celegans.ucsc.ce11/meta.yaml>`_

   


.. conda:package:: bioconductor-bsgenome.celegans.ucsc.ce11

   |downloads_bioconductor-bsgenome.celegans.ucsc.ce11| |docker_bioconductor-bsgenome.celegans.ucsc.ce11|

   :versions: 1.4.2-2, 1.4.2-0
   
   :depends bioconductor-bsgenome: >=1.52.0,<1.53.0
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-bsgenome.celegans.ucsc.ce11

   and update with::

      conda update bioconductor-bsgenome.celegans.ucsc.ce11

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-bsgenome.celegans.ucsc.ce11:<tag>

   (see `bioconductor-bsgenome.celegans.ucsc.ce11/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-bsgenome.celegans.ucsc.ce11| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-bsgenome.celegans.ucsc.ce11.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-bsgenome.celegans.ucsc.ce11
   :alt:   (downloads)
.. |docker_bioconductor-bsgenome.celegans.ucsc.ce11| image:: https://quay.io/repository/biocontainers/bioconductor-bsgenome.celegans.ucsc.ce11/status
   :target: https://quay.io/repository/biocontainers/bioconductor-bsgenome.celegans.ucsc.ce11
.. _`bioconductor-bsgenome.celegans.ucsc.ce11/tags`: https://quay.io/repository/biocontainers/bioconductor-bsgenome.celegans.ucsc.ce11?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-bsgenome.celegans.ucsc.ce11/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-bsgenome.celegans.ucsc.ce11/README.html