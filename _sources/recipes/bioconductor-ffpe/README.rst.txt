:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-ffpe'
.. highlight: bash

bioconductor-ffpe
=================

.. conda:recipe:: bioconductor-ffpe
   :replaces_section_title:

   Identify low\-quality data using metrics developed for expression data derived from Formalin\-Fixed\, Paraffin\-Embedded \(FFPE\) data.  Also a function for making Concordance at the Top plots \(CAT\-plots\).

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/ffpe.html
   :license: GPL (>2)
   :recipe: /`bioconductor-ffpe <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-ffpe>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-ffpe/meta.yaml>`_
   :links: biotools: :biotools:`ffpe`

   


.. conda:package:: bioconductor-ffpe

   |downloads_bioconductor-ffpe| |docker_bioconductor-ffpe|

   :versions: 1.28.0-1, 1.26.0-0, 1.24.0-0, 1.22.0-0
   
   :depends bioconductor-affy: >=1.62.0,<1.63.0
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends bioconductor-biocgenerics: >=0.30.0,<0.31.0
   :depends bioconductor-lumi: >=2.36.0,<2.37.0
   :depends bioconductor-methylumi: >=2.30.0,<2.31.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-sfsmisc: 
   :depends r-ttr: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-ffpe

   and update with::

      conda update bioconductor-ffpe

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-ffpe:<tag>

   (see `bioconductor-ffpe/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-ffpe| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-ffpe.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-ffpe
   :alt:   (downloads)
.. |docker_bioconductor-ffpe| image:: https://quay.io/repository/biocontainers/bioconductor-ffpe/status
   :target: https://quay.io/repository/biocontainers/bioconductor-ffpe
.. _`bioconductor-ffpe/tags`: https://quay.io/repository/biocontainers/bioconductor-ffpe?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-ffpe/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-ffpe/README.html