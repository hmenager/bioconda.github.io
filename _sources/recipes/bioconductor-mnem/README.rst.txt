:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-mnem'
.. highlight: bash

bioconductor-mnem
=================

.. conda:recipe:: bioconductor-mnem
   :replaces_section_title:

   Mixture Nested Effects Models \(mnem\) is an extension of Nested Effects Models and allows for the analysis of single cell perturbation data provided by methods like Perturb\-Seq \(Dixit et al.\, 2016\) or Crop\-Seq \(Datlinger et al.\, 2017\). In those experiments each of many cells is perturbed by a knock\-down of a specific gene\, i.e. several cells are perturbed by a knock\-down of gene A\, several by a knock\-down of gene B\, ... and so forth. The observed read\-out has to be multi\-trait and in the case of the Perturb\-\/Crop\-Seq gene are expression profiles for each cell. mnem uses a mixture model to simultaneously cluster the cell population into k clusters and and infer k networks causally linking the perturbed genes for each cluster. The mixture components are inferred via an expectation maximization algorithm.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/mnem.html
   :license: GPL-3
   :recipe: /`bioconductor-mnem <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-mnem>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-mnem/meta.yaml>`_

   


.. conda:package:: bioconductor-mnem

   |downloads_bioconductor-mnem| |docker_bioconductor-mnem|

   :versions: 
   
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-mnem

   and update with::

      conda update bioconductor-mnem

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-mnem:<tag>

   (see `bioconductor-mnem/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-mnem| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-mnem.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-mnem
   :alt:   (downloads)
.. |docker_bioconductor-mnem| image:: https://quay.io/repository/biocontainers/bioconductor-mnem/status
   :target: https://quay.io/repository/biocontainers/bioconductor-mnem
.. _`bioconductor-mnem/tags`: https://quay.io/repository/biocontainers/bioconductor-mnem?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-mnem/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-mnem/README.html