:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-bsgenome.scerevisiae.ucsc.saccer2'
.. highlight: bash

bioconductor-bsgenome.scerevisiae.ucsc.saccer2
==============================================

.. conda:recipe:: bioconductor-bsgenome.scerevisiae.ucsc.saccer2
   :replaces_section_title:

   Saccharomyces cerevisiae \(Yeast\) full genome as provided by UCSC \(sacCer2\, June 2008\) and stored in Biostrings objects.

   :homepage: https://bioconductor.org/packages/3.9/data/annotation/html/BSgenome.Scerevisiae.UCSC.sacCer2.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-bsgenome.scerevisiae.ucsc.saccer2 <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-bsgenome.scerevisiae.ucsc.saccer2>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-bsgenome.scerevisiae.ucsc.saccer2/meta.yaml>`_

   


.. conda:package:: bioconductor-bsgenome.scerevisiae.ucsc.saccer2

   |downloads_bioconductor-bsgenome.scerevisiae.ucsc.saccer2| |docker_bioconductor-bsgenome.scerevisiae.ucsc.saccer2|

   :versions: 1.4.0-2, 1.4.0-0
   
   :depends bioconductor-bsgenome: >=1.52.0,<1.53.0
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-bsgenome.scerevisiae.ucsc.saccer2

   and update with::

      conda update bioconductor-bsgenome.scerevisiae.ucsc.saccer2

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-bsgenome.scerevisiae.ucsc.saccer2:<tag>

   (see `bioconductor-bsgenome.scerevisiae.ucsc.saccer2/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-bsgenome.scerevisiae.ucsc.saccer2| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-bsgenome.scerevisiae.ucsc.saccer2.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-bsgenome.scerevisiae.ucsc.saccer2
   :alt:   (downloads)
.. |docker_bioconductor-bsgenome.scerevisiae.ucsc.saccer2| image:: https://quay.io/repository/biocontainers/bioconductor-bsgenome.scerevisiae.ucsc.saccer2/status
   :target: https://quay.io/repository/biocontainers/bioconductor-bsgenome.scerevisiae.ucsc.saccer2
.. _`bioconductor-bsgenome.scerevisiae.ucsc.saccer2/tags`: https://quay.io/repository/biocontainers/bioconductor-bsgenome.scerevisiae.ucsc.saccer2?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-bsgenome.scerevisiae.ucsc.saccer2/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-bsgenome.scerevisiae.ucsc.saccer2/README.html