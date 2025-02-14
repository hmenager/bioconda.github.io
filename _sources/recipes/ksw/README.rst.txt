:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'ksw'
.. highlight: bash

ksw
===

.. conda:recipe:: ksw
   :replaces_section_title:

   Ksw\: \(interactive\) smith\-waterman in C

   :homepage: https://github.com/nh13/ksw
   :license: MIT
   :recipe: /`ksw <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/ksw>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/ksw/meta.yaml>`_
   :links: biotools: :biotools:`ksw`

   


.. conda:package:: ksw

   |downloads_ksw| |docker_ksw|

   :versions: 0.2.1-0, 0.2.0-0, 0.1.0a-0, 0.0.2-0
   
   :depends libgcc-ng: >=4.9
   :depends libstdcxx-ng: >=4.9
   :depends zlib: >=1.2.11,<1.3.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install ksw

   and update with::

      conda update ksw

   or use the docker container::

      docker pull quay.io/biocontainers/ksw:<tag>

   (see `ksw/tags`_ for valid values for ``<tag>``)


.. |downloads_ksw| image:: https://img.shields.io/conda/dn/bioconda/ksw.svg?style=flat
   :target: https://anaconda.org/bioconda/ksw
   :alt:   (downloads)
.. |docker_ksw| image:: https://quay.io/repository/biocontainers/ksw/status
   :target: https://quay.io/repository/biocontainers/ksw
.. _`ksw/tags`: https://quay.io/repository/biocontainers/ksw?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/ksw/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/ksw/README.html