:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'openslide-python'
.. highlight: bash

openslide-python
================

.. conda:recipe:: openslide-python
   :replaces_section_title:

   Python interface to OpenSlide

   :homepage: http://openslide.org/
   :license: LGPL / GNU Lesser General Public v2 (LGPLv2)
   :recipe: /`openslide-python <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/openslide-python>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/openslide-python/meta.yaml>`_

   


.. conda:package:: openslide-python

   |downloads_openslide-python| |docker_openslide-python|

   :versions: 1.1.1-0
   
   :depends libgcc-ng: >=4.9
   :depends openslide: 
   :depends pillow: 
   :depends python: >=2.7,<2.8.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install openslide-python

   and update with::

      conda update openslide-python

   or use the docker container::

      docker pull quay.io/biocontainers/openslide-python:<tag>

   (see `openslide-python/tags`_ for valid values for ``<tag>``)


.. |downloads_openslide-python| image:: https://img.shields.io/conda/dn/bioconda/openslide-python.svg?style=flat
   :target: https://anaconda.org/bioconda/openslide-python
   :alt:   (downloads)
.. |docker_openslide-python| image:: https://quay.io/repository/biocontainers/openslide-python/status
   :target: https://quay.io/repository/biocontainers/openslide-python
.. _`openslide-python/tags`: https://quay.io/repository/biocontainers/openslide-python?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/openslide-python/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/openslide-python/README.html