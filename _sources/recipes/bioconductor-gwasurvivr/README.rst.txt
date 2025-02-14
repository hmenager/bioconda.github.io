:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-gwasurvivr'
.. highlight: bash

bioconductor-gwasurvivr
=======================

.. conda:recipe:: bioconductor-gwasurvivr
   :replaces_section_title:

   gwasurvivr is a package to perform survival analysis using Cox proportional hazard models on imputed genetic data.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/gwasurvivr.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-gwasurvivr <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-gwasurvivr>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-gwasurvivr/meta.yaml>`_

   


.. conda:package:: bioconductor-gwasurvivr

   |downloads_bioconductor-gwasurvivr| |docker_bioconductor-gwasurvivr|

   :versions: 1.2.0-1, 1.0.0-1, 1.0.0-0
   
   :depends bioconductor-gwastools: >=1.30.0,<1.31.0
   :depends bioconductor-snprelate: >=1.18.0,<1.19.0
   :depends bioconductor-summarizedexperiment: >=1.14.0,<1.15.0
   :depends bioconductor-variantannotation: >=1.30.0,<1.31.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-matrixstats: 
   :depends r-survival: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-gwasurvivr

   and update with::

      conda update bioconductor-gwasurvivr

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-gwasurvivr:<tag>

   (see `bioconductor-gwasurvivr/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-gwasurvivr| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-gwasurvivr.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-gwasurvivr
   :alt:   (downloads)
.. |docker_bioconductor-gwasurvivr| image:: https://quay.io/repository/biocontainers/bioconductor-gwasurvivr/status
   :target: https://quay.io/repository/biocontainers/bioconductor-gwasurvivr
.. _`bioconductor-gwasurvivr/tags`: https://quay.io/repository/biocontainers/bioconductor-gwasurvivr?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-gwasurvivr/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-gwasurvivr/README.html