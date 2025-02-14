:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-qsmooth'
.. highlight: bash

bioconductor-qsmooth
====================

.. conda:recipe:: bioconductor-qsmooth
   :replaces_section_title:

   Smooth quantile normalization is a generalization of quantile normalization\, which is average of the two types of assumptions about the data generation process\: quantile normalization and quantile normalization between groups.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/qsmooth.html
   :license: CC BY 4.0
   :recipe: /`bioconductor-qsmooth <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-qsmooth>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-qsmooth/meta.yaml>`_

   


.. conda:package:: bioconductor-qsmooth

   |downloads_bioconductor-qsmooth| |docker_bioconductor-qsmooth|

   :versions: 1.0.0-1
   
   :depends bioconductor-summarizedexperiment: >=1.14.0,<1.15.0
   :depends bioconductor-sva: >=3.32.0,<3.33.0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-qsmooth

   and update with::

      conda update bioconductor-qsmooth

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-qsmooth:<tag>

   (see `bioconductor-qsmooth/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-qsmooth| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-qsmooth.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-qsmooth
   :alt:   (downloads)
.. |docker_bioconductor-qsmooth| image:: https://quay.io/repository/biocontainers/bioconductor-qsmooth/status
   :target: https://quay.io/repository/biocontainers/bioconductor-qsmooth
.. _`bioconductor-qsmooth/tags`: https://quay.io/repository/biocontainers/bioconductor-qsmooth?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-qsmooth/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-qsmooth/README.html