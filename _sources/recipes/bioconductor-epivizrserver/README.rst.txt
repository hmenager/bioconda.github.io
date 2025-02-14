:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-epivizrserver'
.. highlight: bash

bioconductor-epivizrserver
==========================

.. conda:recipe:: bioconductor-epivizrserver
   :replaces_section_title:

   This package provides objects to manage WebSocket connections to epiviz apps. Other epivizr package use this infrastructure.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/epivizrServer.html
   :license: MIT + file LICENSE
   :recipe: /`bioconductor-epivizrserver <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-epivizrserver>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-epivizrserver/meta.yaml>`_
   :links: biotools: :biotools:`epivizrserver`, doi: :doi:`10.1038/nmeth.3252`

   


.. conda:package:: bioconductor-epivizrserver

   |downloads_bioconductor-epivizrserver| |docker_bioconductor-epivizrserver|

   :versions: 1.12.0-1, 1.12.0-0, 1.10.0-0, 1.8.1-0, 1.6.0-0
   
   :depends r-base: >=3.6,<3.7.0a0
   :depends r-httpuv: >=1.3.0
   :depends r-mime: >=0.2
   :depends r-r6: >=2.0.0
   :depends r-rjson: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-epivizrserver

   and update with::

      conda update bioconductor-epivizrserver

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-epivizrserver:<tag>

   (see `bioconductor-epivizrserver/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-epivizrserver| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-epivizrserver.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-epivizrserver
   :alt:   (downloads)
.. |docker_bioconductor-epivizrserver| image:: https://quay.io/repository/biocontainers/bioconductor-epivizrserver/status
   :target: https://quay.io/repository/biocontainers/bioconductor-epivizrserver
.. _`bioconductor-epivizrserver/tags`: https://quay.io/repository/biocontainers/bioconductor-epivizrserver?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-epivizrserver/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-epivizrserver/README.html