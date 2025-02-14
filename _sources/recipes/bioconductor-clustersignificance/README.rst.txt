:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-clustersignificance'
.. highlight: bash

bioconductor-clustersignificance
================================

.. conda:recipe:: bioconductor-clustersignificance
   :replaces_section_title:

   The ClusterSignificance package provides tools to assess if class clusters in dimensionality reduced data representations have a separation different from permuted data. The term class clusters here refers to\, clusters of points representing known classes in the data. This is particularly useful to determine if a subset of the variables\, e.g. genes in a specific pathway\, alone can separate samples into these established classes. ClusterSignificance accomplishes this by\, projecting all points onto a one dimensional line. Cluster separations are then scored and the probability of the seen separation being due to chance is evaluated using a permutation method.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/ClusterSignificance.html
   :license: GPL-3
   :recipe: /`bioconductor-clustersignificance <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-clustersignificance>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-clustersignificance/meta.yaml>`_
   :links: biotools: :biotools:`clustersignificance`, doi: :doi:`10.1038/nmeth.3252`

   


.. conda:package:: bioconductor-clustersignificance

   |downloads_bioconductor-clustersignificance| |docker_bioconductor-clustersignificance|

   :versions: 1.12.0-1, 1.12.0-0, 1.10.0-0, 1.8.2-0, 1.6.0-0
   
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-pracma: 
   :depends r-princurve: >=2.0.5
   :depends r-rcolorbrewer: 
   :depends r-scatterplot3d: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-clustersignificance

   and update with::

      conda update bioconductor-clustersignificance

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-clustersignificance:<tag>

   (see `bioconductor-clustersignificance/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-clustersignificance| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-clustersignificance.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-clustersignificance
   :alt:   (downloads)
.. |docker_bioconductor-clustersignificance| image:: https://quay.io/repository/biocontainers/bioconductor-clustersignificance/status
   :target: https://quay.io/repository/biocontainers/bioconductor-clustersignificance
.. _`bioconductor-clustersignificance/tags`: https://quay.io/repository/biocontainers/bioconductor-clustersignificance?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-clustersignificance/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-clustersignificance/README.html