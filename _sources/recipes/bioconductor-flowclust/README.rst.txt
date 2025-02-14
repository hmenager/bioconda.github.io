:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-flowclust'
.. highlight: bash

bioconductor-flowclust
======================

.. conda:recipe:: bioconductor-flowclust
   :replaces_section_title:

   Robust model\-based clustering using a t\-mixture model with Box\-Cox transformation. Note\: users should have GSL installed. Windows users\: \'consult the README file available in the inst directory of the source distribution for necessary configuration instructions\'.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/flowClust.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-flowclust <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-flowclust>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-flowclust/meta.yaml>`_

   


.. conda:package:: bioconductor-flowclust

   |downloads_bioconductor-flowclust| |docker_bioconductor-flowclust|

   :versions: 3.22.0-1, 3.20.0-0
   
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends bioconductor-biocgenerics: >=0.30.0,<0.31.0
   :depends bioconductor-flowcore: >=1.50.0,<1.51.0
   :depends bioconductor-flowviz: >=1.48.0,<1.49.0
   :depends bioconductor-graph: >=1.62.0,<1.63.0
   :depends libgcc-ng: >=7.3.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-clue: 
   :depends r-corpcor: 
   :depends r-ellipse: 
   :depends r-mnormt: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-flowclust

   and update with::

      conda update bioconductor-flowclust

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-flowclust:<tag>

   (see `bioconductor-flowclust/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-flowclust| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-flowclust.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-flowclust
   :alt:   (downloads)
.. |docker_bioconductor-flowclust| image:: https://quay.io/repository/biocontainers/bioconductor-flowclust/status
   :target: https://quay.io/repository/biocontainers/bioconductor-flowclust
.. _`bioconductor-flowclust/tags`: https://quay.io/repository/biocontainers/bioconductor-flowclust?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-flowclust/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-flowclust/README.html