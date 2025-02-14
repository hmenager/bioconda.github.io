:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-rhisat2'
.. highlight: bash

bioconductor-rhisat2
====================

.. conda:recipe:: bioconductor-rhisat2
   :replaces_section_title:

   An R interface to the HISAT2 spliced short\-read aligner by Kim et al. \(2015\). The package contains wrapper functions to create a genome index and to perform the read alignment to the generated index.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/Rhisat2.html
   :license: GPL-3
   :recipe: /`bioconductor-rhisat2 <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-rhisat2>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-rhisat2/meta.yaml>`_

   


.. conda:package:: bioconductor-rhisat2

   |downloads_bioconductor-rhisat2| |docker_bioconductor-rhisat2|

   :versions: 1.0.3-0
   
   :depends bioconductor-genomicfeatures: >=1.36.0,<1.37.0
   :depends bioconductor-genomicranges: >=1.36.0,<1.37.0
   :depends bioconductor-sgseq: >=1.18.0,<1.19.0
   :depends libgcc-ng: >=7.3.0
   :depends libstdcxx-ng: >=7.3.0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-rhisat2

   and update with::

      conda update bioconductor-rhisat2

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-rhisat2:<tag>

   (see `bioconductor-rhisat2/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-rhisat2| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-rhisat2.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-rhisat2
   :alt:   (downloads)
.. |docker_bioconductor-rhisat2| image:: https://quay.io/repository/biocontainers/bioconductor-rhisat2/status
   :target: https://quay.io/repository/biocontainers/bioconductor-rhisat2
.. _`bioconductor-rhisat2/tags`: https://quay.io/repository/biocontainers/bioconductor-rhisat2?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-rhisat2/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-rhisat2/README.html