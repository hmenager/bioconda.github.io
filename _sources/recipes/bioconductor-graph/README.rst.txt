:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-graph'
.. highlight: bash

bioconductor-graph
==================

.. conda:recipe:: bioconductor-graph
   :replaces_section_title:

   A package that implements some simple graph handling capabilities.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/graph.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-graph <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-graph>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-graph/meta.yaml>`_
   :links: biotools: :biotools:`graph`, doi: :doi:`10.1038/nmeth.3252`

   


.. conda:package:: bioconductor-graph

   |downloads_bioconductor-graph| |docker_bioconductor-graph|

   :versions: 1.62.0-1, 1.60.0-0, 1.58.2-0, 1.56.0-0, 1.54.0-0, 1.50.0-1, 1.48.0-1, 1.48.0-0
   
   :depends bioconductor-biocgenerics: >=0.30.0,<0.31.0
   :depends libgcc-ng: >=7.3.0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-graph

   and update with::

      conda update bioconductor-graph

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-graph:<tag>

   (see `bioconductor-graph/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-graph| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-graph.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-graph
   :alt:   (downloads)
.. |docker_bioconductor-graph| image:: https://quay.io/repository/biocontainers/bioconductor-graph/status
   :target: https://quay.io/repository/biocontainers/bioconductor-graph
.. _`bioconductor-graph/tags`: https://quay.io/repository/biocontainers/bioconductor-graph?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-graph/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-graph/README.html