:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'maxentpy'
.. highlight: bash

maxentpy
========

.. conda:recipe:: maxentpy
   :replaces_section_title:

   maxentpy is a python wrapper for MaxEntScan to calculate splice site strength.

   :homepage: https://github.com/kepbod/maxentpy
   :license: MIT
   :recipe: /`maxentpy <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/maxentpy>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/maxentpy/meta.yaml>`_

   


.. conda:package:: maxentpy

   |downloads_maxentpy| |docker_maxentpy|

   :versions: 0.0.1-2, 0.0.1-1, 0.0.1-0
   
   :depends cython: 
   :depends msgpack-python: 
   :depends python: >=2.7,<2.8.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install maxentpy

   and update with::

      conda update maxentpy

   or use the docker container::

      docker pull quay.io/biocontainers/maxentpy:<tag>

   (see `maxentpy/tags`_ for valid values for ``<tag>``)


.. |downloads_maxentpy| image:: https://img.shields.io/conda/dn/bioconda/maxentpy.svg?style=flat
   :target: https://anaconda.org/bioconda/maxentpy
   :alt:   (downloads)
.. |docker_maxentpy| image:: https://quay.io/repository/biocontainers/maxentpy/status
   :target: https://quay.io/repository/biocontainers/maxentpy
.. _`maxentpy/tags`: https://quay.io/repository/biocontainers/maxentpy?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/maxentpy/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/maxentpy/README.html