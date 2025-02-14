:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-myvariant'
.. highlight: bash

bioconductor-myvariant
======================

.. conda:recipe:: bioconductor-myvariant
   :replaces_section_title:

   MyVariant.info is a comprehensive aggregation of variant annotation resources. myvariant is a wrapper for querying MyVariant.info services

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/myvariant.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-myvariant <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-myvariant>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-myvariant/meta.yaml>`_
   :links: biotools: :biotools:`myvariant`, doi: :doi:`10.1101/035667`

   


.. conda:package:: bioconductor-myvariant

   |downloads_bioconductor-myvariant| |docker_bioconductor-myvariant|

   :versions: 1.14.0-1, 1.12.0-1, 1.12.0-0, 1.10.0-0, 1.8.0-0, 1.6.0-0
   
   :depends bioconductor-genomeinfodb: >=1.20.0,<1.21.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends bioconductor-variantannotation: >=1.30.0,<1.31.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-hmisc: 
   :depends r-httr: 
   :depends r-jsonlite: 
   :depends r-magrittr: 
   :depends r-plyr: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-myvariant

   and update with::

      conda update bioconductor-myvariant

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-myvariant:<tag>

   (see `bioconductor-myvariant/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-myvariant| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-myvariant.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-myvariant
   :alt:   (downloads)
.. |docker_bioconductor-myvariant| image:: https://quay.io/repository/biocontainers/bioconductor-myvariant/status
   :target: https://quay.io/repository/biocontainers/bioconductor-myvariant
.. _`bioconductor-myvariant/tags`: https://quay.io/repository/biocontainers/bioconductor-myvariant?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-myvariant/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-myvariant/README.html