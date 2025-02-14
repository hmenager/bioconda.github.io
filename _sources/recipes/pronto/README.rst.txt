:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'pronto'
.. highlight: bash

pronto
======

.. conda:recipe:: pronto
   :replaces_section_title:

   Python frontend to ontologies

   :homepage: http://github.com/althonos/pronto
   :license: MIT / MIT License
   :recipe: /`pronto <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/pronto>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/pronto/meta.yaml>`_

   


.. conda:package:: pronto

   |downloads_pronto| |docker_pronto|

   :versions: 0.12.2-0, 0.12.1-0, 0.12.0-0, 0.11.1-0, 0.11.0-0, 0.10.2-1, 0.10.2-0, 0.3.3-2, 0.3.3-1, 0.3.3-0
   
   :depends python: 
   :depends six: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install pronto

   and update with::

      conda update pronto

   or use the docker container::

      docker pull quay.io/biocontainers/pronto:<tag>

   (see `pronto/tags`_ for valid values for ``<tag>``)


.. |downloads_pronto| image:: https://img.shields.io/conda/dn/bioconda/pronto.svg?style=flat
   :target: https://anaconda.org/bioconda/pronto
   :alt:   (downloads)
.. |docker_pronto| image:: https://quay.io/repository/biocontainers/pronto/status
   :target: https://quay.io/repository/biocontainers/pronto
.. _`pronto/tags`: https://quay.io/repository/biocontainers/pronto?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/pronto/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/pronto/README.html