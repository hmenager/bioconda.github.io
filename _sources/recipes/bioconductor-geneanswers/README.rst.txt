:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-geneanswers'
.. highlight: bash

bioconductor-geneanswers
========================

.. conda:recipe:: bioconductor-geneanswers
   :replaces_section_title:

   GeneAnswers provides an integrated tool for biological or medical interpretation of the given one or more groups of genes by means of statistical test.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/GeneAnswers.html
   :license: LGPL (>= 2)
   :recipe: /`bioconductor-geneanswers <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-geneanswers>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-geneanswers/meta.yaml>`_

   


.. conda:package:: bioconductor-geneanswers

   |downloads_bioconductor-geneanswers| |docker_bioconductor-geneanswers|

   :versions: 2.26.0-1, 2.24.0-0
   
   :depends bioconductor-annotate: >=1.62.0,<1.63.0
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends bioconductor-heatplus: >=2.30.0,<2.31.0
   :depends bioconductor-rbgl: >=1.60.0,<1.61.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-downloader: 
   :depends r-igraph: 
   :depends r-mass: 
   :depends r-rcolorbrewer: 
   :depends r-rcurl: 
   :depends r-rsqlite: 
   :depends r-xml: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-geneanswers

   and update with::

      conda update bioconductor-geneanswers

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-geneanswers:<tag>

   (see `bioconductor-geneanswers/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-geneanswers| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-geneanswers.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-geneanswers
   :alt:   (downloads)
.. |docker_bioconductor-geneanswers| image:: https://quay.io/repository/biocontainers/bioconductor-geneanswers/status
   :target: https://quay.io/repository/biocontainers/bioconductor-geneanswers
.. _`bioconductor-geneanswers/tags`: https://quay.io/repository/biocontainers/bioconductor-geneanswers?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-geneanswers/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-geneanswers/README.html