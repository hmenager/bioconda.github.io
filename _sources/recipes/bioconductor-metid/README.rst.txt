:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-metid'
.. highlight: bash

bioconductor-metid
==================

.. conda:recipe:: bioconductor-metid
   :replaces_section_title:

   This package uses an innovative network\-based approach that will enhance our ability to determine the identities of significant ions detected by LC\-MS.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/MetID.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-metid <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-metid>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-metid/meta.yaml>`_

   


.. conda:package:: bioconductor-metid

   |downloads_bioconductor-metid| |docker_bioconductor-metid|

   :versions: 1.2.0-1, 1.0.0-0
   
   :depends bioconductor-chemminer: >=3.36.0,<3.37.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-devtools: >=1.13.0
   :depends r-igraph: >=1.2.1
   :depends r-matrix: >=1.2-12
   :depends r-stringr: >=1.3.0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-metid

   and update with::

      conda update bioconductor-metid

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-metid:<tag>

   (see `bioconductor-metid/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-metid| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-metid.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-metid
   :alt:   (downloads)
.. |docker_bioconductor-metid| image:: https://quay.io/repository/biocontainers/bioconductor-metid/status
   :target: https://quay.io/repository/biocontainers/bioconductor-metid
.. _`bioconductor-metid/tags`: https://quay.io/repository/biocontainers/bioconductor-metid?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-metid/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-metid/README.html