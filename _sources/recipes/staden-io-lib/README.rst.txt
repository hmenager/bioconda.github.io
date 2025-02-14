:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'staden_io_lib'
.. highlight: bash

staden_io_lib
=============

.. conda:recipe:: staden-io-lib
   :replaces_section_title:

   Staden io\_lib is a library of file reading and writing code e.g. for SAM\/BAM\/CRAM

   :homepage: https://github.com/jkbonfield/io_lib/
   :license: BSD
   :recipe: /`staden-io-lib <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/staden-io-lib>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/staden-io-lib/meta.yaml>`_

   


.. conda:package:: staden_io_lib

   |downloads_staden_io_lib| |docker_staden_io_lib|

   :versions: 1.14.11-0
   
   :depends curl: >=7.64.1,<8.0a0
   :depends libdeflate: >=1.0,<1.1.0a0
   :depends libgcc-ng: >=7.3.0
   :depends xz: >=5.2.4,<5.3.0a0
   :depends zlib: >=1.2.11,<1.3.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install staden_io_lib

   and update with::

      conda update staden_io_lib

   or use the docker container::

      docker pull quay.io/biocontainers/staden_io_lib:<tag>

   (see `staden_io_lib/tags`_ for valid values for ``<tag>``)


.. |downloads_staden_io_lib| image:: https://img.shields.io/conda/dn/bioconda/staden_io_lib.svg?style=flat
   :target: https://anaconda.org/bioconda/staden_io_lib
   :alt:   (downloads)
.. |docker_staden_io_lib| image:: https://quay.io/repository/biocontainers/staden_io_lib/status
   :target: https://quay.io/repository/biocontainers/staden_io_lib
.. _`staden_io_lib/tags`: https://quay.io/repository/biocontainers/staden_io_lib?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/staden_io_lib/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/staden_io_lib/README.html