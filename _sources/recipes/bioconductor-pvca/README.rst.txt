:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-pvca'
.. highlight: bash

bioconductor-pvca
=================

.. conda:recipe:: bioconductor-pvca
   :replaces_section_title:

   This package contains the function to assess the batch sourcs by fitting all \"sources\" as random effects including two\-way interaction terms in the Mixed Model\(depends on lme4 package\) to selected principal components\, which were obtained from the original data correlation matrix. This package accompanies the book \"Batch Effects and Noise in Microarray Experiements\, chapter 12.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/pvca.html
   :license: LGPL (>= 2.0)
   :recipe: /`bioconductor-pvca <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-pvca>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-pvca/meta.yaml>`_
   :links: biotools: :biotools:`pvca`, doi: :doi:`10.1002/9780470685983.ch12`

   


.. conda:package:: bioconductor-pvca

   |downloads_bioconductor-pvca| |docker_bioconductor-pvca|

   :versions: 1.24.0-1, 1.22.0-0, 1.20.0-0, 1.18.0-0
   
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends bioconductor-vsn: >=3.52.0,<3.53.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-lme4: 
   :depends r-matrix: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-pvca

   and update with::

      conda update bioconductor-pvca

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-pvca:<tag>

   (see `bioconductor-pvca/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-pvca| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-pvca.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-pvca
   :alt:   (downloads)
.. |docker_bioconductor-pvca| image:: https://quay.io/repository/biocontainers/bioconductor-pvca/status
   :target: https://quay.io/repository/biocontainers/bioconductor-pvca
.. _`bioconductor-pvca/tags`: https://quay.io/repository/biocontainers/bioconductor-pvca?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-pvca/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-pvca/README.html