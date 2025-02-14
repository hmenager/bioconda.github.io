:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-rprotobuflib'
.. highlight: bash

bioconductor-rprotobuflib
=========================

.. conda:recipe:: bioconductor-rprotobuflib
   :replaces_section_title:

   This package provides the headers and static library of Protocol buffers 2.6.0 for other R packages to compile and link against.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/RProtoBufLib.html
   :license: BSD_3_clause
   :recipe: /`bioconductor-rprotobuflib <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-rprotobuflib>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-rprotobuflib/meta.yaml>`_

   


.. conda:package:: bioconductor-rprotobuflib

   |downloads_bioconductor-rprotobuflib| |docker_bioconductor-rprotobuflib|

   :versions: 1.6.0-1, 1.6.0-0, 1.4.0-0, 1.2.0-0, 1.0.0-0
   
   :depends libgcc-ng: >=7.3.0
   :depends libstdcxx-ng: >=7.3.0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-rprotobuflib

   and update with::

      conda update bioconductor-rprotobuflib

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-rprotobuflib:<tag>

   (see `bioconductor-rprotobuflib/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-rprotobuflib| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-rprotobuflib.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-rprotobuflib
   :alt:   (downloads)
.. |docker_bioconductor-rprotobuflib| image:: https://quay.io/repository/biocontainers/bioconductor-rprotobuflib/status
   :target: https://quay.io/repository/biocontainers/bioconductor-rprotobuflib
.. _`bioconductor-rprotobuflib/tags`: https://quay.io/repository/biocontainers/bioconductor-rprotobuflib?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-rprotobuflib/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-rprotobuflib/README.html