:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-bioconcotk'
.. highlight: bash

bioconductor-bioconcotk
=======================

.. conda:recipe:: bioconductor-bioconcotk
   :replaces_section_title:

   Provide a central interface to various tools for genome\-scale analysis of cancer studies.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/BiocOncoTK.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-bioconcotk <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-bioconcotk>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-bioconcotk/meta.yaml>`_

   


.. conda:package:: bioconductor-bioconcotk

   |downloads_bioconductor-bioconcotk| |docker_bioconductor-bioconcotk|

   :versions: 1.4.0-1, 1.2.0-0
   
   :depends bioconductor-complexheatmap: >=2.0.0,<2.1.0
   :depends bioconductor-genomicfeatures: >=1.36.0,<1.37.0
   :depends bioconductor-genomicranges: >=1.36.0,<1.37.0
   :depends bioconductor-iranges: >=2.18.0,<2.19.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends bioconductor-summarizedexperiment: >=1.14.0,<1.15.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-bigrquery: 
   :depends r-dbi: 
   :depends r-dplyr: 
   :depends r-dt: 
   :depends r-ggplot2: 
   :depends r-httr: 
   :depends r-magrittr: 
   :depends r-rjson: 
   :depends r-shiny: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-bioconcotk

   and update with::

      conda update bioconductor-bioconcotk

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-bioconcotk:<tag>

   (see `bioconductor-bioconcotk/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-bioconcotk| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-bioconcotk.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-bioconcotk
   :alt:   (downloads)
.. |docker_bioconductor-bioconcotk| image:: https://quay.io/repository/biocontainers/bioconductor-bioconcotk/status
   :target: https://quay.io/repository/biocontainers/bioconductor-bioconcotk
.. _`bioconductor-bioconcotk/tags`: https://quay.io/repository/biocontainers/bioconductor-bioconcotk?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-bioconcotk/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-bioconcotk/README.html