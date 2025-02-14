:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'nim-falcon'
.. highlight: bash

nim-falcon
==========

.. conda:recipe:: nim-falcon
   :replaces_section_title:

   Nim\-based executables used by Falcon assembly workflow

   :homepage: https://github.com/bio-nim/nim-falcon
   :license: MIT
   :recipe: /`nim-falcon <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/nim-falcon>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/nim-falcon/meta.yaml>`_

   


.. conda:package:: nim-falcon

   |downloads_nim-falcon| |docker_nim-falcon|

   :versions: 0.0.1-0, 0.0.0-0
   
   :depends htslib: >=1.9,<1.10.0a0
   :depends pcre: >=8.41,<9.0a0
   :depends zlib: >=1.2.11,<1.3.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install nim-falcon

   and update with::

      conda update nim-falcon

   or use the docker container::

      docker pull quay.io/biocontainers/nim-falcon:<tag>

   (see `nim-falcon/tags`_ for valid values for ``<tag>``)


.. |downloads_nim-falcon| image:: https://img.shields.io/conda/dn/bioconda/nim-falcon.svg?style=flat
   :target: https://anaconda.org/bioconda/nim-falcon
   :alt:   (downloads)
.. |docker_nim-falcon| image:: https://quay.io/repository/biocontainers/nim-falcon/status
   :target: https://quay.io/repository/biocontainers/nim-falcon
.. _`nim-falcon/tags`: https://quay.io/repository/biocontainers/nim-falcon?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/nim-falcon/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/nim-falcon/README.html