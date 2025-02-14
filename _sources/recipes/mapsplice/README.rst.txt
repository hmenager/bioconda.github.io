:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'mapsplice'
.. highlight: bash

mapsplice
=========

.. conda:recipe:: mapsplice
   :replaces_section_title:

   MapSplice is a software for mapping RNA\-seq data to reference genome for splice junction discovery that depends only on reference genome\, and not on any further annotations.

   :homepage: http://www.netlab.uky.edu/p/bioinfo/MapSplice2
   :license: Custom
   :recipe: /`mapsplice <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/mapsplice>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/mapsplice/meta.yaml>`_
   :links: biotools: :biotools:`mapsplice`

   


.. conda:package:: mapsplice

   |downloads_mapsplice| |docker_mapsplice|

   :versions: 2.2.1-0, 2.2.0-1, 2.2.0-0
   
   :depends libgcc-ng: >=7.3.0
   :depends libstdcxx-ng: >=7.3.0
   :depends ncurses: >=6.1,<6.2.0a0
   :depends python: >=2.7,<2.8.0a0
   :depends zlib: >=1.2.11,<1.3.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install mapsplice

   and update with::

      conda update mapsplice

   or use the docker container::

      docker pull quay.io/biocontainers/mapsplice:<tag>

   (see `mapsplice/tags`_ for valid values for ``<tag>``)


.. |downloads_mapsplice| image:: https://img.shields.io/conda/dn/bioconda/mapsplice.svg?style=flat
   :target: https://anaconda.org/bioconda/mapsplice
   :alt:   (downloads)
.. |docker_mapsplice| image:: https://quay.io/repository/biocontainers/mapsplice/status
   :target: https://quay.io/repository/biocontainers/mapsplice
.. _`mapsplice/tags`: https://quay.io/repository/biocontainers/mapsplice?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/mapsplice/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/mapsplice/README.html