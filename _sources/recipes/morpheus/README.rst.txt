:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'morpheus'
.. highlight: bash

morpheus
========

.. conda:recipe:: morpheus
   :replaces_section_title:

   mass spectrometry–based proteomics database search algorithm

   :homepage: https://github.com/cwenger/Morpheus/
   :license: MIT / MIT
   :recipe: /`morpheus <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/morpheus>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/morpheus/meta.yaml>`_
   :links: doi: :doi:`10.1021/pr301024c`

   


.. conda:package:: morpheus

   |downloads_morpheus| |docker_morpheus|

   :versions: 272-1, 272-0, 255-0
   
   :depends mono: >=4.0.0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install morpheus

   and update with::

      conda update morpheus

   or use the docker container::

      docker pull quay.io/biocontainers/morpheus:<tag>

   (see `morpheus/tags`_ for valid values for ``<tag>``)


.. |downloads_morpheus| image:: https://img.shields.io/conda/dn/bioconda/morpheus.svg?style=flat
   :target: https://anaconda.org/bioconda/morpheus
   :alt:   (downloads)
.. |docker_morpheus| image:: https://quay.io/repository/biocontainers/morpheus/status
   :target: https://quay.io/repository/biocontainers/morpheus
.. _`morpheus/tags`: https://quay.io/repository/biocontainers/morpheus?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/morpheus/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/morpheus/README.html