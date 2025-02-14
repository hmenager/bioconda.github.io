:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'gapfiller'
.. highlight: bash

gapfiller
=========

.. conda:recipe:: gapfiller
   :replaces_section_title:

   GapFiller is a seed\-and\-extend local assembler to fill the gap within paired reads.

   :homepage: https://sourceforge.net/projects/gapfiller
   :license: GPL / GPLv3
   :recipe: /`gapfiller <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/gapfiller>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/gapfiller/meta.yaml>`_

   


.. conda:package:: gapfiller

   |downloads_gapfiller| |docker_gapfiller|

   :versions: 2.1.1-0
   
   :depends boost: >=1.57.0,<1.57.1.0a0
   :depends libgcc: 
   :depends zlib: >=1.2.11,<1.3.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install gapfiller

   and update with::

      conda update gapfiller

   or use the docker container::

      docker pull quay.io/biocontainers/gapfiller:<tag>

   (see `gapfiller/tags`_ for valid values for ``<tag>``)


.. |downloads_gapfiller| image:: https://img.shields.io/conda/dn/bioconda/gapfiller.svg?style=flat
   :target: https://anaconda.org/bioconda/gapfiller
   :alt:   (downloads)
.. |docker_gapfiller| image:: https://quay.io/repository/biocontainers/gapfiller/status
   :target: https://quay.io/repository/biocontainers/gapfiller
.. _`gapfiller/tags`: https://quay.io/repository/biocontainers/gapfiller?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/gapfiller/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/gapfiller/README.html