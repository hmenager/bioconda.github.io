:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-gsri'
.. highlight: bash

bioconductor-gsri
=================

.. conda:recipe:: bioconductor-gsri
   :replaces_section_title:

   The GSRI package estimates the number of differentially expressed genes in gene sets\, utilizing the concept of the Gene Set Regulation Index \(GSRI\).

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/GSRI.html
   :license: GPL-3
   :recipe: /`bioconductor-gsri <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-gsri>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-gsri/meta.yaml>`_
   :links: biotools: :biotools:`gsri`, doi: :doi:`10.1038/nmeth.3252`

   


.. conda:package:: bioconductor-gsri

   |downloads_bioconductor-gsri| |docker_bioconductor-gsri|

   :versions: 2.32.0-1, 2.30.0-0, 2.28.0-0, 2.26.0-0
   
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends bioconductor-genefilter: >=1.66.0,<1.67.0
   :depends bioconductor-gseabase: >=1.46.0,<1.47.0
   :depends bioconductor-les: >=1.34.0,<1.35.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-fdrtool: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-gsri

   and update with::

      conda update bioconductor-gsri

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-gsri:<tag>

   (see `bioconductor-gsri/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-gsri| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-gsri.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-gsri
   :alt:   (downloads)
.. |docker_bioconductor-gsri| image:: https://quay.io/repository/biocontainers/bioconductor-gsri/status
   :target: https://quay.io/repository/biocontainers/bioconductor-gsri
.. _`bioconductor-gsri/tags`: https://quay.io/repository/biocontainers/bioconductor-gsri?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-gsri/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-gsri/README.html