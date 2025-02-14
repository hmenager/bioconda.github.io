:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-plgem'
.. highlight: bash

bioconductor-plgem
==================

.. conda:recipe:: bioconductor-plgem
   :replaces_section_title:

   The Power Law Global Error Model \(PLGEM\) has been shown to faithfully model the variance\-versus\-mean dependence that exists in a variety of genome\-wide datasets\, including microarray and proteomics data. The use of PLGEM has been shown to improve the detection of differentially expressed genes or proteins in these datasets.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/plgem.html
   :license: GPL-2
   :recipe: /`bioconductor-plgem <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-plgem>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-plgem/meta.yaml>`_
   :links: biotools: :biotools:`plgem`

   


.. conda:package:: bioconductor-plgem

   |downloads_bioconductor-plgem| |docker_bioconductor-plgem|

   :versions: 1.56.0-1, 1.54.1-0, 1.54.0-0, 1.52.0-0, 1.50.0-0, 1.48.0-0
   
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-mass: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-plgem

   and update with::

      conda update bioconductor-plgem

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-plgem:<tag>

   (see `bioconductor-plgem/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-plgem| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-plgem.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-plgem
   :alt:   (downloads)
.. |docker_bioconductor-plgem| image:: https://quay.io/repository/biocontainers/bioconductor-plgem/status
   :target: https://quay.io/repository/biocontainers/bioconductor-plgem
.. _`bioconductor-plgem/tags`: https://quay.io/repository/biocontainers/bioconductor-plgem?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-plgem/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-plgem/README.html