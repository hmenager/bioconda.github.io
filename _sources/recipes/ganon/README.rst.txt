:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'ganon'
.. highlight: bash

ganon
=====

.. conda:recipe:: ganon
   :replaces_section_title:

   ganon\: a read classification tool using Interleaved Bloom Filters

   :homepage: https://github.com/pirovc/ganon
   :license: MIT / MIT License
   :recipe: /`ganon <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/ganon>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/ganon/meta.yaml>`_
   :links: doi: :doi:`10.1101/406017`

   ganon is a k\-mer based read classification tool which uses Interleaved Bloom Filters
   in conjunction with a taxonomic clustering and a k\-mer counting\-filtering scheme



.. conda:package:: ganon

   |downloads_ganon| |docker_ganon|

   :versions: 0.1.4-0, 0.1.3-1, 0.1.3-0, 0.1.2-0
   
   :depends coreutils: 
   :depends gawk: 
   :depends libgcc-ng: >=7.3.0
   :depends libstdcxx-ng: >=7.3.0
   :depends pandas: 
   :depends pylca: >=1.0.0
   :depends python: >=3.4
   :depends taxsbp: >=0.1.2
   :depends zlib: >=1.2.11,<1.3.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install ganon

   and update with::

      conda update ganon

   or use the docker container::

      docker pull quay.io/biocontainers/ganon:<tag>

   (see `ganon/tags`_ for valid values for ``<tag>``)


.. |downloads_ganon| image:: https://img.shields.io/conda/dn/bioconda/ganon.svg?style=flat
   :target: https://anaconda.org/bioconda/ganon
   :alt:   (downloads)
.. |docker_ganon| image:: https://quay.io/repository/biocontainers/ganon/status
   :target: https://quay.io/repository/biocontainers/ganon
.. _`ganon/tags`: https://quay.io/repository/biocontainers/ganon?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/ganon/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/ganon/README.html