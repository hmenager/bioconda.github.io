:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'raven-assembler'
.. highlight: bash

raven-assembler
===============

.. conda:recipe:: raven-assembler
   :replaces_section_title:

   Raven is an assembler for raw reads generated by the third generation sequencing.

   :homepage: https://github.com/lbcb-sci/raven
   :license: MIT
   :recipe: /`raven-assembler <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/raven-assembler>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/raven-assembler/meta.yaml>`_

   


.. conda:package:: raven-assembler

   |downloads_raven-assembler| |docker_raven-assembler|

   :versions: 0.0.1-0, 0.0.0-0
   
   :depends libgcc-ng: >=7.3.0
   :depends libstdcxx-ng: >=7.3.0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install raven-assembler

   and update with::

      conda update raven-assembler

   or use the docker container::

      docker pull quay.io/biocontainers/raven-assembler:<tag>

   (see `raven-assembler/tags`_ for valid values for ``<tag>``)


.. |downloads_raven-assembler| image:: https://img.shields.io/conda/dn/bioconda/raven-assembler.svg?style=flat
   :target: https://anaconda.org/bioconda/raven-assembler
   :alt:   (downloads)
.. |docker_raven-assembler| image:: https://quay.io/repository/biocontainers/raven-assembler/status
   :target: https://quay.io/repository/biocontainers/raven-assembler
.. _`raven-assembler/tags`: https://quay.io/repository/biocontainers/raven-assembler?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/raven-assembler/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/raven-assembler/README.html