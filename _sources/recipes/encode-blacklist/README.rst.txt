:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'encode-blacklist'
.. highlight: bash

encode-blacklist
================

.. conda:recipe:: encode-blacklist
   :replaces_section_title:

   The ENCODE Blacklist\: Identification of Problematic Regions of the Genome

   :homepage: https://github.com/Boyle-Lab/Blacklist
   :license: GPL3
   :recipe: /`encode-blacklist <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/encode-blacklist>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/encode-blacklist/meta.yaml>`_
   :links: doi: :doi:`10.7717/10.1038/s41598-019-45839-z`

   


.. conda:package:: encode-blacklist

   |downloads_encode-blacklist| |docker_encode-blacklist|

   :versions: 2.0-0
   
   :depends bamtools: >=2.5.1,<2.5.2.0a0
   :depends libgcc-ng: >=7.3.0
   :depends libstdcxx-ng: >=7.3.0
   :depends zlib: >=1.2.11,<1.3.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install encode-blacklist

   and update with::

      conda update encode-blacklist

   or use the docker container::

      docker pull quay.io/biocontainers/encode-blacklist:<tag>

   (see `encode-blacklist/tags`_ for valid values for ``<tag>``)


.. |downloads_encode-blacklist| image:: https://img.shields.io/conda/dn/bioconda/encode-blacklist.svg?style=flat
   :target: https://anaconda.org/bioconda/encode-blacklist
   :alt:   (downloads)
.. |docker_encode-blacklist| image:: https://quay.io/repository/biocontainers/encode-blacklist/status
   :target: https://quay.io/repository/biocontainers/encode-blacklist
.. _`encode-blacklist/tags`: https://quay.io/repository/biocontainers/encode-blacklist?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/encode-blacklist/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/encode-blacklist/README.html