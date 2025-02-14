:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-post'
.. highlight: bash

bioconductor-post
=================

.. conda:recipe:: bioconductor-post
   :replaces_section_title:

   Perform orthogonal projection of high dimensional data of a set\, and statistical modeling of phenotye with projected vectors as predictor.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/POST.html
   :license: GPL (>= 2)
   :recipe: /`bioconductor-post <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-post>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-post/meta.yaml>`_

   


.. conda:package:: bioconductor-post

   |downloads_bioconductor-post| |docker_bioconductor-post|

   :versions: 1.8.0-1, 1.6.0-0
   
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends bioconductor-gseabase: >=1.46.0,<1.47.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-compquadform: 
   :depends r-matrix: 
   :depends r-survival: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-post

   and update with::

      conda update bioconductor-post

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-post:<tag>

   (see `bioconductor-post/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-post| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-post.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-post
   :alt:   (downloads)
.. |docker_bioconductor-post| image:: https://quay.io/repository/biocontainers/bioconductor-post/status
   :target: https://quay.io/repository/biocontainers/bioconductor-post
.. _`bioconductor-post/tags`: https://quay.io/repository/biocontainers/bioconductor-post?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-post/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-post/README.html