:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'wtdbg'
.. highlight: bash

wtdbg
=====

.. conda:recipe:: wtdbg
   :replaces_section_title:

   Wtdbg2\: A fuzzy Bruijn graph approach to long noisy reads assembly

   :homepage: https://github.com/ruanjue/wtdbg2
   :license: GPL / GPL-3.0+
   :recipe: /`wtdbg <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/wtdbg>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/wtdbg/meta.yaml>`_

   


.. conda:package:: wtdbg

   |downloads_wtdbg| |docker_wtdbg|

   :versions: 2.5-0, 2.3-0, 2.1-0, 2.0-0, 1.2.8.1-2, 1.2.8.1-0
   
   :depends libgcc-ng: >=7.3.0
   :depends libstdcxx-ng: >=7.3.0
   :depends zlib: >=1.2.11,<1.3.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install wtdbg

   and update with::

      conda update wtdbg

   or use the docker container::

      docker pull quay.io/biocontainers/wtdbg:<tag>

   (see `wtdbg/tags`_ for valid values for ``<tag>``)


.. |downloads_wtdbg| image:: https://img.shields.io/conda/dn/bioconda/wtdbg.svg?style=flat
   :target: https://anaconda.org/bioconda/wtdbg
   :alt:   (downloads)
.. |docker_wtdbg| image:: https://quay.io/repository/biocontainers/wtdbg/status
   :target: https://quay.io/repository/biocontainers/wtdbg
.. _`wtdbg/tags`: https://quay.io/repository/biocontainers/wtdbg?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/wtdbg/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/wtdbg/README.html