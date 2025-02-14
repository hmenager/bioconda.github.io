:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-methylmnm'
.. highlight: bash

bioconductor-methylmnm
======================

.. conda:recipe:: bioconductor-methylmnm
   :replaces_section_title:

   To give the exactly p\-value and q\-value of MeDIP\-seq and MRE\-seq data for different samples comparation.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/methylMnM.html
   :license: GPL-3
   :recipe: /`bioconductor-methylmnm <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-methylmnm>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-methylmnm/meta.yaml>`_
   :links: biotools: :biotools:`methylmnm`, doi: :doi:`10.1101/gr.156539.113`

   


.. conda:package:: bioconductor-methylmnm

   |downloads_bioconductor-methylmnm| |docker_bioconductor-methylmnm|

   :versions: 1.22.0-1, 1.22.0-0, 1.20.0-0, 1.18.0-0, 1.16.0-0, 1.14.0-0
   
   :depends bioconductor-edger: >=3.26.0,<3.27.0
   :depends libgcc-ng: >=7.3.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-statmod: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-methylmnm

   and update with::

      conda update bioconductor-methylmnm

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-methylmnm:<tag>

   (see `bioconductor-methylmnm/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-methylmnm| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-methylmnm.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-methylmnm
   :alt:   (downloads)
.. |docker_bioconductor-methylmnm| image:: https://quay.io/repository/biocontainers/bioconductor-methylmnm/status
   :target: https://quay.io/repository/biocontainers/bioconductor-methylmnm
.. _`bioconductor-methylmnm/tags`: https://quay.io/repository/biocontainers/bioconductor-methylmnm?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-methylmnm/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-methylmnm/README.html