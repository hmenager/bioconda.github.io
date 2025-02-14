:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-streamer'
.. highlight: bash

bioconductor-streamer
=====================

.. conda:recipe:: bioconductor-streamer
   :replaces_section_title:

   Large data files can be difficult to work with in R\, where data generally resides in memory. This package encourages a style of programming where data is \'streamed\' from disk into R via a \`producer\' and through a series of \`consumers\' that\, typically reduce the original data to a manageable size. The package provides useful Producer and Consumer stream components for operations such as data input\, sampling\, indexing\, and transformation\; see package\?Streamer for details.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/Streamer.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-streamer <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-streamer>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-streamer/meta.yaml>`_
   :links: biotools: :biotools:`streamer`, doi: :doi:`10.1038/nmeth.3252`

   


.. conda:package:: bioconductor-streamer

   |downloads_bioconductor-streamer| |docker_bioconductor-streamer|

   :versions: 1.30.0-1, 1.28.0-0, 1.26.0-0, 1.24.0-0, 1.22.0-0
   
   :depends bioconductor-biocgenerics: >=0.30.0,<0.31.0
   :depends bioconductor-graph: >=1.62.0,<1.63.0
   :depends bioconductor-rbgl: >=1.60.0,<1.61.0
   :depends libgcc-ng: >=7.3.0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-streamer

   and update with::

      conda update bioconductor-streamer

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-streamer:<tag>

   (see `bioconductor-streamer/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-streamer| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-streamer.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-streamer
   :alt:   (downloads)
.. |docker_bioconductor-streamer| image:: https://quay.io/repository/biocontainers/bioconductor-streamer/status
   :target: https://quay.io/repository/biocontainers/bioconductor-streamer
.. _`bioconductor-streamer/tags`: https://quay.io/repository/biocontainers/bioconductor-streamer?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-streamer/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-streamer/README.html