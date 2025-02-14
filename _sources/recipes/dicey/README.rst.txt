:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'dicey'
.. highlight: bash

dicey
=====

.. conda:recipe:: dicey
   :replaces_section_title:

   In\-silico PCR and variant primer design

   :homepage: https://github.com/gear-genomics/dicey
   :license: GPL / GPL-3.0
   :recipe: /`dicey <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/dicey>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/dicey/meta.yaml>`_

   


.. conda:package:: dicey

   |downloads_dicey| |docker_dicey|

   :versions: 0.1.6-1, 0.1.6-0
   
   :depends boost: >=1.68.0,<1.68.1.0a0
   :depends bzip2: >=1.0.6,<2.0a0
   :depends htslib: >=1.9,<1.10.0a0
   :depends libgcc-ng: >=7.3.0
   :depends libstdcxx-ng: >=7.3.0
   :depends sdsl-lite: 
   :depends zlib: >=1.2.11,<1.3.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install dicey

   and update with::

      conda update dicey

   or use the docker container::

      docker pull quay.io/biocontainers/dicey:<tag>

   (see `dicey/tags`_ for valid values for ``<tag>``)


.. |downloads_dicey| image:: https://img.shields.io/conda/dn/bioconda/dicey.svg?style=flat
   :target: https://anaconda.org/bioconda/dicey
   :alt:   (downloads)
.. |docker_dicey| image:: https://quay.io/repository/biocontainers/dicey/status
   :target: https://quay.io/repository/biocontainers/dicey
.. _`dicey/tags`: https://quay.io/repository/biocontainers/dicey?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/dicey/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/dicey/README.html