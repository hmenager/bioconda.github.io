:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-classifyr'
.. highlight: bash

bioconductor-classifyr
======================

.. conda:recipe:: bioconductor-classifyr
   :replaces_section_title:

   The software formalises a framework for classification in R. There are four stages\; Data transformation\, feature selection\, classifier training\, and prediction. The requirements of variable types and names are fixed\, but specialised variables for functions can also be provided. The classification framework is wrapped in a driver loop\, that reproducibly carries out a number of cross\-validation schemes. Functions for differential expression\, differential variability\, and differential distribution are included. Additional functions may be developed by the user\, by creating an interface to the framework.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/ClassifyR.html
   :license: GPL-3
   :recipe: /`bioconductor-classifyr <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-classifyr>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-classifyr/meta.yaml>`_
   :links: biotools: :biotools:`classifyr`

   


.. conda:package:: bioconductor-classifyr

   |downloads_bioconductor-classifyr| |docker_bioconductor-classifyr|

   :versions: 2.4.4-0, 2.2.6-0, 2.2.4-0, 2.0.10-0, 1.12.2-0
   
   :depends bioconductor-biocparallel: >=1.18.0,<1.19.0
   :depends bioconductor-multiassayexperiment: >=1.10.0,<1.11.0
   :depends bioconductor-s4vectors: >=0.22.0,<0.23.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-locfit: 
   :depends r-plyr: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-classifyr

   and update with::

      conda update bioconductor-classifyr

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-classifyr:<tag>

   (see `bioconductor-classifyr/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-classifyr| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-classifyr.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-classifyr
   :alt:   (downloads)
.. |docker_bioconductor-classifyr| image:: https://quay.io/repository/biocontainers/bioconductor-classifyr/status
   :target: https://quay.io/repository/biocontainers/bioconductor-classifyr
.. _`bioconductor-classifyr/tags`: https://quay.io/repository/biocontainers/bioconductor-classifyr?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-classifyr/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-classifyr/README.html