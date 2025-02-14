:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-deco'
.. highlight: bash

bioconductor-deco
=================

.. conda:recipe:: bioconductor-deco
   :replaces_section_title:

   This package discovers differential features in hetero\- and homogeneous omic data by a two\-step method including subsampling LIMMA and NSCA. DECO reveals feature associations to hidden subclasses not exclusively related to higher deregulation levels.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/deco.html
   :license: GPL (>=3)
   :recipe: /`bioconductor-deco <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-deco>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-deco/meta.yaml>`_

   


.. conda:package:: bioconductor-deco

   |downloads_bioconductor-deco| |docker_bioconductor-deco|

   :versions: 1.0.0-1
   
   :depends bioconductor-annotationdbi: >=1.46.0,<1.47.0
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends bioconductor-biocparallel: >=1.18.0,<1.19.0
   :depends bioconductor-biocstyle: >=2.12.0,<2.13.0
   :depends bioconductor-limma: >=3.40.0,<3.41.0
   :depends bioconductor-made4: >=1.58.0,<1.59.0
   :depends bioconductor-summarizedexperiment: >=1.14.0,<1.15.0
   :depends r-ade4: 
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-cluster: 
   :depends r-foreign: 
   :depends r-gdata: 
   :depends r-ggplot2: 
   :depends r-gplots: 
   :depends r-gridextra: 
   :depends r-locfit: 
   :depends r-rcolorbrewer: 
   :depends r-reshape2: 
   :depends r-scatterplot3d: 
   :depends r-sfsmisc: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-deco

   and update with::

      conda update bioconductor-deco

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-deco:<tag>

   (see `bioconductor-deco/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-deco| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-deco.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-deco
   :alt:   (downloads)
.. |docker_bioconductor-deco| image:: https://quay.io/repository/biocontainers/bioconductor-deco/status
   :target: https://quay.io/repository/biocontainers/bioconductor-deco
.. _`bioconductor-deco/tags`: https://quay.io/repository/biocontainers/bioconductor-deco?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-deco/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-deco/README.html