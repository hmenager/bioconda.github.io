:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'radsex'
.. highlight: bash

radsex
======

.. conda:recipe:: radsex
   :replaces_section_title:

   RADSex \(currently under development\) is a software package for the analysis of sex\-determination using RAD\-Sequencing data.

   :homepage: https://github.com/RomainFeron/RadSex
   :license: GPL3
   :recipe: /`radsex <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/radsex>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/radsex/meta.yaml>`_

   


.. conda:package:: radsex

   |downloads_radsex| |docker_radsex|

   :versions: 0.2.0-0
   
   :depends libgcc-ng: >=7.3.0
   :depends libstdcxx-ng: >=7.3.0
   :depends zlib: >=1.2.11,<1.3.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install radsex

   and update with::

      conda update radsex

   or use the docker container::

      docker pull quay.io/biocontainers/radsex:<tag>

   (see `radsex/tags`_ for valid values for ``<tag>``)


.. |downloads_radsex| image:: https://img.shields.io/conda/dn/bioconda/radsex.svg?style=flat
   :target: https://anaconda.org/bioconda/radsex
   :alt:   (downloads)
.. |docker_radsex| image:: https://quay.io/repository/biocontainers/radsex/status
   :target: https://quay.io/repository/biocontainers/radsex
.. _`radsex/tags`: https://quay.io/repository/biocontainers/radsex?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/radsex/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/radsex/README.html