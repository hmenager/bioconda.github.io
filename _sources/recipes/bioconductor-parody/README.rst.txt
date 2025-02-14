:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-parody'
.. highlight: bash

bioconductor-parody
===================

.. conda:recipe:: bioconductor-parody
   :replaces_section_title:

   routines for univariate and multivariate outlier detection with a focus on parametric methods\, but support for some methods based on resistant statistics

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/parody.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-parody <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-parody>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-parody/meta.yaml>`_
   :links: biotools: :biotools:`parody`, doi: :doi:`10.1038/nmeth.3252`

   


.. conda:package:: bioconductor-parody

   |downloads_bioconductor-parody| |docker_bioconductor-parody|

   :versions: 1.42.0-1, 1.42.0-0, 1.40.0-0, 1.38.0-0, 1.36.0-0, 1.34.0-0
   
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-parody

   and update with::

      conda update bioconductor-parody

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-parody:<tag>

   (see `bioconductor-parody/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-parody| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-parody.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-parody
   :alt:   (downloads)
.. |docker_bioconductor-parody| image:: https://quay.io/repository/biocontainers/bioconductor-parody/status
   :target: https://quay.io/repository/biocontainers/bioconductor-parody
.. _`bioconductor-parody/tags`: https://quay.io/repository/biocontainers/bioconductor-parody?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-parody/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-parody/README.html