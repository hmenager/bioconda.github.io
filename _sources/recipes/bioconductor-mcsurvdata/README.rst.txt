:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-mcsurvdata'
.. highlight: bash

bioconductor-mcsurvdata
=======================

.. conda:recipe:: bioconductor-mcsurvdata
   :replaces_section_title:

   This package stores two merged expressionSet objects that contain the gene expression profile and clinical information of \-a\- six breast cancer cohorts and \-b\- four colorectal cancer cohorts. Breast cancer data are employed in the vignette of the hrunbiased package for survival analysis of gene signatures.

   :homepage: https://bioconductor.org/packages/3.9/data/experiment/html/mcsurvdata.html
   :license: GPL (>=2)
   :recipe: /`bioconductor-mcsurvdata <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-mcsurvdata>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-mcsurvdata/meta.yaml>`_

   


.. conda:package:: bioconductor-mcsurvdata

   |downloads_bioconductor-mcsurvdata| |docker_bioconductor-mcsurvdata|

   :versions: 1.2.0-1, 1.0.0-1, 1.0.0-0
   
   :depends bioconductor-annotationhub: >=2.16.0,<2.17.0
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends bioconductor-experimenthub: >=1.10.0,<1.11.0
   :depends curl: >=7.65.3,<8.0a0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-mcsurvdata

   and update with::

      conda update bioconductor-mcsurvdata

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-mcsurvdata:<tag>

   (see `bioconductor-mcsurvdata/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-mcsurvdata| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-mcsurvdata.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-mcsurvdata
   :alt:   (downloads)
.. |docker_bioconductor-mcsurvdata| image:: https://quay.io/repository/biocontainers/bioconductor-mcsurvdata/status
   :target: https://quay.io/repository/biocontainers/bioconductor-mcsurvdata
.. _`bioconductor-mcsurvdata/tags`: https://quay.io/repository/biocontainers/bioconductor-mcsurvdata?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-mcsurvdata/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-mcsurvdata/README.html