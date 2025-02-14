:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-ogsa'
.. highlight: bash

bioconductor-ogsa
=================

.. conda:recipe:: bioconductor-ogsa
   :replaces_section_title:

   OGSA provides a global estimate of pathway deregulation in cancer subtypes by integrating the estimates of significance for individual pathway members that have been identified by outlier analysis.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/OGSA.html
   :license: GPL (== 2)
   :recipe: /`bioconductor-ogsa <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-ogsa>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-ogsa/meta.yaml>`_
   :links: biotools: :biotools:`ogsa`, doi: :doi:`10.1109/TCBB.2013.153`

   


.. conda:package:: bioconductor-ogsa

   |downloads_bioconductor-ogsa| |docker_bioconductor-ogsa|

   :versions: 1.14.0-1, 1.12.0-0, 1.10.0-0, 1.8.0-0, 1.6.0-0
   
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends bioconductor-limma: >=3.40.0,<3.41.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-gplots: >=2.8.0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-ogsa

   and update with::

      conda update bioconductor-ogsa

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-ogsa:<tag>

   (see `bioconductor-ogsa/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-ogsa| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-ogsa.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-ogsa
   :alt:   (downloads)
.. |docker_bioconductor-ogsa| image:: https://quay.io/repository/biocontainers/bioconductor-ogsa/status
   :target: https://quay.io/repository/biocontainers/bioconductor-ogsa
.. _`bioconductor-ogsa/tags`: https://quay.io/repository/biocontainers/bioconductor-ogsa?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-ogsa/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-ogsa/README.html