:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-flowviz'
.. highlight: bash

bioconductor-flowviz
====================

.. conda:recipe:: bioconductor-flowviz
   :replaces_section_title:

   Provides visualization tools for flow cytometry data.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/flowViz.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-flowviz <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-flowviz>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-flowviz/meta.yaml>`_
   :links: biotools: :biotools:`flowviz`, doi: :doi:`10.1093/bioinformatics/btn021`

   


.. conda:package:: bioconductor-flowviz

   |downloads_bioconductor-flowviz| |docker_bioconductor-flowviz|

   :versions: 1.48.0-1, 1.46.1-0, 1.46.0-0, 1.44.0-0, 1.42.0-0, 1.40.0-0, 1.38.0-0
   
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends bioconductor-flowcore: >=1.50.0,<1.51.0
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-hexbin: 
   :depends r-idpmisc: 
   :depends r-kernsmooth: 
   :depends r-lattice: 
   :depends r-latticeextra: 
   :depends r-mass: 
   :depends r-rcolorbrewer: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-flowviz

   and update with::

      conda update bioconductor-flowviz

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-flowviz:<tag>

   (see `bioconductor-flowviz/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-flowviz| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-flowviz.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-flowviz
   :alt:   (downloads)
.. |docker_bioconductor-flowviz| image:: https://quay.io/repository/biocontainers/bioconductor-flowviz/status
   :target: https://quay.io/repository/biocontainers/bioconductor-flowviz
.. _`bioconductor-flowviz/tags`: https://quay.io/repository/biocontainers/bioconductor-flowviz?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-flowviz/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-flowviz/README.html