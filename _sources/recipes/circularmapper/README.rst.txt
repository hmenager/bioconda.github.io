:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'circularmapper'
.. highlight: bash

circularmapper
==============

.. conda:recipe:: circularmapper
   :replaces_section_title:

    A method to improve mappings on circular genomes\, using the BWA mapper.

   :homepage: https://github.com/apeltzer/CircularMapper
   :license: GPLv3
   :recipe: /`circularmapper <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/circularmapper>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/circularmapper/meta.yaml>`_

   


.. conda:package:: circularmapper

   |downloads_circularmapper| |docker_circularmapper|

   :versions: 1.93.4-1, 1.93.4-0
   
   :depends openjdk: 
   :depends python: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install circularmapper

   and update with::

      conda update circularmapper

   or use the docker container::

      docker pull quay.io/biocontainers/circularmapper:<tag>

   (see `circularmapper/tags`_ for valid values for ``<tag>``)


.. |downloads_circularmapper| image:: https://img.shields.io/conda/dn/bioconda/circularmapper.svg?style=flat
   :target: https://anaconda.org/bioconda/circularmapper
   :alt:   (downloads)
.. |docker_circularmapper| image:: https://quay.io/repository/biocontainers/circularmapper/status
   :target: https://quay.io/repository/biocontainers/circularmapper
.. _`circularmapper/tags`: https://quay.io/repository/biocontainers/circularmapper?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/circularmapper/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/circularmapper/README.html