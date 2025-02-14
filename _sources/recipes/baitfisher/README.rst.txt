:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'baitfisher'
.. highlight: bash

baitfisher
==========

.. conda:recipe:: baitfisher
   :replaces_section_title:

   The BaitFisher\-package is a software package for designing hybrid enrichment probes.

   :homepage: https://github.com/cmayer/BaitFisher-package
   :license: GPL3
   :recipe: /`baitfisher <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/baitfisher>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/baitfisher/meta.yaml>`_

   


.. conda:package:: baitfisher

   |downloads_baitfisher| |docker_baitfisher|

   :versions: 1.0-1, 1.0-0
   
   :depends libstdcxx-ng: >=4.9
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install baitfisher

   and update with::

      conda update baitfisher

   or use the docker container::

      docker pull quay.io/biocontainers/baitfisher:<tag>

   (see `baitfisher/tags`_ for valid values for ``<tag>``)


.. |downloads_baitfisher| image:: https://img.shields.io/conda/dn/bioconda/baitfisher.svg?style=flat
   :target: https://anaconda.org/bioconda/baitfisher
   :alt:   (downloads)
.. |docker_baitfisher| image:: https://quay.io/repository/biocontainers/baitfisher/status
   :target: https://quay.io/repository/biocontainers/baitfisher
.. _`baitfisher/tags`: https://quay.io/repository/biocontainers/baitfisher?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/baitfisher/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/baitfisher/README.html