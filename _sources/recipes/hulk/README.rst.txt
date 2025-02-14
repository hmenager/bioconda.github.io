:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'hulk'
.. highlight: bash

hulk
====

.. conda:recipe:: hulk
   :replaces_section_title:

   Histosketching Using Little Kmers

   :homepage: https://github.com/will-rowe/hulk
   :license: MIT
   :recipe: /`hulk <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/hulk>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/hulk/meta.yaml>`_

   


.. conda:package:: hulk

   |downloads_hulk| |docker_hulk|

   :versions: 1.0.0-0, 0.1.2-1, 0.1.0-1, 0.0.2-1, 0.0.1-1
   
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install hulk

   and update with::

      conda update hulk

   or use the docker container::

      docker pull quay.io/biocontainers/hulk:<tag>

   (see `hulk/tags`_ for valid values for ``<tag>``)


.. |downloads_hulk| image:: https://img.shields.io/conda/dn/bioconda/hulk.svg?style=flat
   :target: https://anaconda.org/bioconda/hulk
   :alt:   (downloads)
.. |docker_hulk| image:: https://quay.io/repository/biocontainers/hulk/status
   :target: https://quay.io/repository/biocontainers/hulk
.. _`hulk/tags`: https://quay.io/repository/biocontainers/hulk?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/hulk/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/hulk/README.html